# 🎵 learn-in-beats

> Aprenda tecnologia no ritmo. Prompts para transformar documentação oficial em músicas educativas.

---

## 💡 O que é isso?

**learn-in-beats** é um projeto que transforma documentação técnica oficial em prompts musicais para o [Suno AI](https://suno.com), gerando músicas que ensinam e fixam conceitos de tecnologia.

A ideia é simples: música cria âncoras cognitivas — rima, ritmo e melodia ajudam a fixar conceitos muito mais rápido do que reler documentação. Cada música é uma "aula" que você ouve no trajeto, no treino ou no plantão.

---

## 🎯 Metodologia

```
URL da documentação oficial
        ↓
  Extração dos conceitos-chave
        ↓
  Geração do prompt estruturado
        ↓
    Suno AI gera a música
        ↓
    Playlist de aprendizado
```

Todo prompt segue um template genérico e reutilizável. A estrutura da letra cobre:

- **Verse 1** → O que é e por que existe
- **Chorus** → A ideia central, memorável e grudenta
- **Verse 2** → Como funciona na prática
- **Bridge** → Erro clássico ou insight de contraste
- **Chorus** → Reforço da ideia central

---

## 🗂️ Estrutura do repositório

```
learn-in-beats/
├── README.md
├── templates/
│   ├── prompt-template.md        # Template genérico reutilizável
│   └── how-to-create.md          # Guia: como criar prompts para novas tecnologias
├── docs/
│   └── methodology.md            # Metodologia detalhada do projeto
└── technologies/
    └── kubernetes/
        ├── README.md              # Visão geral + playlist completa
        ├── vol-1-fundamentos/
        ├── vol-2-node-workloads/
        ├── vol-3-rede-exposicao/
        ├── vol-4-configuracao-seguranca/
        ├── vol-5-armazenamento/
        └── vol-6-observabilidade-operacao/
```

---

## 🎵 Tecnologias disponíveis

| Tecnologia | Volumes | Músicas | Playlist |
|---|---|---|---|
| [Kubernetes](./technologies/kubernetes/README.md) | 6 | 33 | 🔗 Em breve |

---

## 🚀 Como usar

1. Acesse a pasta da tecnologia que deseja estudar
2. Escolha o volume (recomendamos seguir a ordem)
3. Copie o prompt do conceito desejado
4. Cole no [Suno AI](https://suno.com) e gere a música
5. Adicione à sua playlist de estudos

---

## ➕ Como contribuir com uma nova tecnologia

Veja o guia completo em [`templates/how-to-create.md`](./templates/how-to-create.md).

O processo é simples:
1. Defina o currículo (quais conceitos, em que ordem)
2. Para cada conceito, busque a URL da documentação oficial
3. Use o template em [`templates/prompt-template.md`](./templates/prompt-template.md)
4. Abra um PR com a nova pasta em `technologies/<nome-da-tech>/`

---

## 🎼 Estilos musicais suportados

O projeto foi desenvolvido e testado com três estilos:

| Estilo | Clima | Melhor para |
|---|---|---|
| **Lo-fi Hip Hop** | Calmo, focado | Estudar, revisar conceitos |
| **Orchestral Dubstep** | Épico, enérgico | Treino, adrenalina |
| **Alternative Metal** | Sombrio, intenso | Madrugada no plantão 👀 |

---

## 📄 Licença

MIT — use, adapte e compartilhe à vontade.

---

> Projeto nascido de uma conversa sobre como fixar Kubernetes de vez.
> Feito com 🎵 e documentação oficial.

