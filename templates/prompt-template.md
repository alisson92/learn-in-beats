# 🎵 Template Genérico de Prompt — Suno AI

Use este template para criar prompts musicais para qualquer tecnologia ou conceito.

---

## Template

```
[STYLE]: lo-fi hip hop                    ← troque pelo estilo desejado
[MOOD]: focused, motivating, slightly epic
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: {ASSUNTO AQUI}

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of {ASSUNTO AQUI}.
The lyrics must:
- Explain what it is and why it matters (verse 1)
- Summarize the core idea in a catchy, memorable chorus
- Go deeper into how it works or how to use it (verse 2)
- Add a contrasting insight or common mistake to avoid (bridge)
- Use analogies and real-world examples embedded in the rhymes
- Keep technical terms in English, rest in Brazilian Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Campos personalizáveis

| Campo | Descrição | Exemplos |
|---|---|---|
| `[STYLE]` | Gênero musical | `lo-fi hip hop`, `rap`, `rock`, `synthwave`, `orchestral dubstep` |
| `[MOOD]` | Clima da música | `focused`, `epic`, `dark`, `motivating`, `calm` |
| `[TOPIC]` | Conceito a ensinar | `kubectl dry-run`, `kube-apiserver`, `Git rebase` |

---

## Estilos testados e aprovados

### Lo-fi Hip Hop (recomendado para estudo)
```
[STYLE]: lo-fi hip hop
[MOOD]: focused, calm, educational
```

### Orchestral Dubstep (recomendado para energia)
```
[STYLE]: orchestral dubstep, heavy trap, grime
[MOOD]: epic, tense, powerful, cinematic
```

### Alternative Metal (referência: Bring Me The Horizon - Doomed)
```
[STYLE]: alternative metal, cinematic rock, stoner rock, orchestral rock
[MOOD]: dark, claustrophobic, epic, emotionally intense
```

---

## Estrutura da letra recomendada

| Seção | Conteúdo |
|---|---|
| **Verse 1** | O que é e por que existe |
| **Chorus** | A ideia central — simples, memorável, grudenta |
| **Verse 2** | Como funciona na prática |
| **Bridge** | Erro clássico, armadilha ou insight de contraste |
| **Chorus** | Reforço da ideia central |

---

## Dicas para um bom prompt

- **Analogias funcionam muito bem** — compare o conceito técnico com algo do mundo real
- **Chorus deve ser curto e rimar** — é o que vai ficar na cabeça
- **Bridge deve ter tensão** — o "e se der errado?" cria contraste emocional
- **Mantenha termos técnicos em inglês** — facilita a memorização dos termos reais
- **Não tente colocar tudo** — escolha 2-3 conceitos-chave por música

---

## Exemplo preenchido

```
[STYLE]: lo-fi hip hop
[MOOD]: focused, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: kubectl dry-run

[INSTRUCTIONS]:
Write a song that teaches the concept of kubectl dry-run.
The lyrics must:
- Explain what dry-run is and why you use it before applying changes (verse 1)
- A catchy chorus: "testa antes de aplicar, dry-run é seu parceiro no cluster"
- Explain the difference between --dry-run=client and --dry-run=server (verse 2)
- Bridge: the danger of applying without testing — o cluster não perdoa erro
- Use analogies (ex: like a rehearsal before the real show)
- Keep kubectl, dry-run, apply, manifest in English; rest in Portuguese
- Educational but feel like a real song
```

