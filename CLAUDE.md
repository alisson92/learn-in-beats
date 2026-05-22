# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## O que é este projeto

**learn-in-beats** é um repositório de prompts para o Suno AI que transformam documentação técnica oficial em músicas educativas. Não há código executável — o produto são arquivos `.md` contendo prompts estruturados.

## Estrutura e convenções

```
technologies/
└── <nome-da-tech>/
    ├── README.md                   # Visão geral + tabela completa de músicas + links Suno
    ├── vol-1-<tema>/
    │   ├── 01-<conceito>.md        # Um arquivo por conceito = uma música
    │   └── ...
    └── vol-N-<tema>/
```

Numeração dos arquivos é global dentro da tecnologia (01, 02, 03…), não reinicia por volume.

## Estrutura obrigatória de cada arquivo de prompt

```markdown
# 🎵 <Nome do Conceito>

> **Volume:** Vol. X — <Tema>
> **Tecnologia:** <Nome da Tech>
> **Documentação oficial:** <URL>
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: ...
[MOOD]: ...
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus
[TOPIC]: ...
[INSTRUCTIONS]:
...
```

---

## Conceitos cobertos

- ...

---

## Notas   ← opcional; use para variações testadas ou ajustes
```

## Estrutura do prompt (conteúdo do [INSTRUCTIONS])

| Seção | Propósito |
|---|---|
| Verse 1 | O que é e por que existe |
| Chorus | Ideia central — curta, rimada, memorável |
| Verse 2 | Como funciona na prática |
| Bridge | Erro clássico ou insight de contraste |
| Chorus | Reforço — repetido 3× no total |

Regras de conteúdo:
- Termos técnicos do setor **sempre em inglês** na letra (kubectl, pod, deployment…)
- Resto da letra em **português brasileiro**
- Analogia com o mundo real obrigatória em algum ponto
- Bridge deve trazer tensão: "o que não fazer" ou "o que acontece se errar"
- Um conceito principal por música (2-3 pontos-chave no máximo)

## Estilos musicais disponíveis

| Estilo | `[STYLE]` + `[MOOD]` |
|---|---|
| Lo-fi Hip Hop (padrão de estudo) | `lo-fi hip hop` / `focused, calm, educational` |
| Orchestral Dubstep (energia/treino) | `orchestral dubstep, heavy trap, grime` / `epic, tense, powerful, cinematic` |
| Alternative Metal (plantão/intenso) | `alternative metal, cinematic rock, stoner rock, orchestral rock` / `dark, claustrophobic, epic, emotionally intense` |

O currículo de Kubernetes usa Lo-fi Hip Hop como padrão.

## Como adicionar uma nova tecnologia

1. Defina o currículo em ordem didática, agrupado em volumes temáticos
2. Crie `technologies/<nome>/README.md` com a tabela de músicas (links Suno como "em breve" até gerar)
3. Para cada conceito: leia a documentação oficial, extraia — definição, mecanismo, erro clássico, analogia — e preencha o template
4. Siga o guia detalhado em `templates/how-to-create.md`

## Conventional Commits

Todo commit deve seguir o padrão `<tipo>(<escopo>): <descrição>`.

**Tipos usados neste projeto:**

| Tipo | Quando usar |
|---|---|
| `feat` | Novo prompt de música, nova tecnologia, novo volume |
| `fix` | Correção em prompt existente, link quebrado, erro de conteúdo |
| `docs` | Atualização de README, methodology, templates, CLAUDE.md |
| `chore` | Renomear arquivos, reorganizar pastas, ajustes sem impacto em conteúdo |
| `refactor` | Reestruturação de prompt sem alterar o conteúdo ensinado |

**Escopos sugeridos:** `kubernetes`, `helm`, `templates`, `docs`, `repo`

**Exemplos:**
```
feat(kubernetes): add prompt for NetworkPolicy (vol-3 #20)
fix(kubernetes): correct bridge content in 14-statefulset
docs(templates): add orchestral dubstep style example
chore(repo): rename file with double extension in vol-6
```

## Convenções de nomenclatura de arquivos

- Todos os arquivos `.md` em **kebab-case**: palavras em minúsculo separadas por hífen
- Arquivos de prompt: prefixo numérico global por tecnologia → `NN-nome-do-conceito.md`
- Pastas de volume: `vol-N-nome-do-tema/`
- Pasta de tecnologia: `technologies/nome-da-tech/`

## Checklist antes de abrir PR

- [ ] Currículo ordenado didaticamente (fundamentos → avançado)
- [ ] README da tecnologia com tabela de músicas criado
- [ ] Cada prompt em arquivo `.md` separado com frontmatter completo
- [ ] Documentação oficial referenciada em cada arquivo
- [ ] Nomenclatura de arquivos: `NN-kebab-case.md`
- [ ] Commits seguindo Conventional Commits
