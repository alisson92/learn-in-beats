# 🛠️ Como criar prompts para uma nova tecnologia

Guia completo para expandir o **learn-in-beats** com uma nova tecnologia.

---

## O processo em 5 passos

### 1. Defina o currículo

Antes de escrever qualquer prompt, mapeie os conceitos da tecnologia em ordem didática:

- Do mais fundamental ao mais avançado
- Agrupe em volumes temáticos (ex: fundamentos, rede, segurança)
- Cada conceito = uma música

**Exemplo de currículo (Kubernetes):**
```
Vol. 1 — Fundamentos
  - O que é Kubernetes
  - Control Plane
  - kube-apiserver
  - etcd
  ...
```

---

### 2. Para cada conceito, busque a documentação oficial

- Prefira URLs da documentação oficial da tecnologia
- Páginas conceituais são melhores que páginas de referência de flags/CLI
- Seções úteis: "What is X", "How it works", "Why it matters"
- Evite: listas de parâmetros, changelogs, FAQs

---

### 3. Extraia os conceitos-chave

Da documentação, identifique:

| Elemento | Pergunta guia |
|---|---|
| **O que é** | Como definiria em uma frase? |
| **Por que existe** | Qual problema resolve? |
| **Como funciona** | Qual o mecanismo central? |
| **Erro clássico** | O que iniciantes erram com frequência? |
| **Analogia** | A que objeto/situação do mundo real se parece? |

---

### 4. Preencha o template

Use o template em [`prompt-template.md`](./prompt-template.md) e preencha:

```
[TOPIC]: <nome do conceito>

[INSTRUCTIONS]:
- Verse 1: <o que é e por que existe>
- Chorus: <ideia central em uma frase rimada>
- Verse 2: <como funciona na prática>
- Bridge: <erro clássico ou armadilha>
- Analogia: <comparação com o mundo real>
- Termos técnicos em inglês: <lista dos termos>
```

---

### 5. Estruture os arquivos

Crie a pasta da tecnologia seguindo esta estrutura:

```
technologies/
└── <nome-da-tech>/
    ├── README.md                    # Visão geral + tabela de músicas + links do Suno
    ├── vol-1-<tema>/
    │   ├── 01-<conceito>.md
    │   ├── 02-<conceito>.md
    │   └── ...
    ├── vol-2-<tema>/
    │   └── ...
    └── ...
```

---

## Estrutura de cada arquivo de prompt

```markdown
# 🎵 <Nome do Conceito>

> **Volume:** Vol. X — <Tema>
> **Tecnologia:** <Nome da Tech>
> **Documentação oficial:** <URL>
> **Música gerada:** <Link do Suno — preencher após gerar>

---

## Prompt

```
[STYLE]: ...
[MOOD]: ...
...
```

---

## Conceitos cobertos

- Conceito 1
- Conceito 2
- Conceito 3

---

## Notas

Observações sobre o prompt, ajustes feitos, variações testadas.
```

---

## Estrutura do README da tecnologia

```markdown
# 🎵 <Tecnologia> — learn-in-beats

> Descrição breve

## Playlist completa

| # | Música | Volume | Suno |
|---|---|---|---|
| 1 | Nome do conceito | Vol. 1 | 🔗 link |
| 2 | Nome do conceito | Vol. 1 | 🔗 link |
...

## Volumes

### Vol. 1 — <Tema>
Descrição do volume.

...

## Fonte
Documentação oficial: <URL base>
```

---

## Checklist antes de abrir o PR

- [ ] Currículo definido e ordenado didaticamente
- [ ] Pelo menos um volume completo
- [ ] README da tecnologia criado com tabela de músicas
- [ ] Cada prompt em arquivo `.md` separado
- [ ] Links do Suno preenchidos (se músicas já geradas)
- [ ] Documentação oficial referenciada em cada prompt

