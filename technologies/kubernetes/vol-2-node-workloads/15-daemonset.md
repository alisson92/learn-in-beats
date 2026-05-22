# 🎵 DaemonSet

> **Volume:** Vol. 2 — Node & Workloads
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/
> **Música gerada:** [Versão A](https://suno.com/s/CzgFldCPaYUhy9xd) · [Versão B](https://suno.com/s/E9Umr39OpqjIPZiL)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: vigilant, steady, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: DaemonSet

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of DaemonSet in Kubernetes.
The lyrics must:
- Verse 1: explique o que é um DaemonSet — garante que uma cópia de um Pod
  rode em todos (ou em alguns) nodes do cluster; quando um novo node entra
  no cluster, o DaemonSet automaticamente adiciona o Pod nele; quando o node
  sai, o Pod é removido junto
- Chorus: algo memorável como "DaemonSet em todo node, sem exceção /
  novo node entrou — Pod já tá lá, automático, sem intervenção"
- Verse 2: os casos de uso clássicos — agentes de log (Fluentd, Filebeat),
  agentes de monitoramento (node-exporter do Prometheus), plugins de rede
  (CNI), agentes de segurança; qualquer coisa que precisa estar em todo node
- Bridge: DaemonSet vs Deployment — Deployment define quantas réplicas você
  quer; DaemonSet define que você quer um por node; são ferramentas diferentes
  para propósitos diferentes
- Use analogies (ex: DaemonSet é como o serviço de limpeza de um prédio —
  toda sala precisa ser limpa, então tem um funcionário designado para cada andar)
- Keep DaemonSet, Pod, node, Deployment, Fluentd, Prometheus, node-exporter,
  CNI em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
