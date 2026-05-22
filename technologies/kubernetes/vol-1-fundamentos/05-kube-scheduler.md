# 🎵 kube-scheduler

> **Volume:** Vol. 1 — Fundamentos do Cluster
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/architecture/#kube-scheduler
> **Música gerada:** [Versão A](https://suno.com/s/BCPiNM7rk9nd49Sq) · [Versão B](https://suno.com/s/swreGsQoWRGTxcVH)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: focused, calm, decisive, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: kube-scheduler

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of kube-scheduler in Kubernetes.
The lyrics must:
- Verse 1: explique o papel do kube-scheduler — ele observa Pods recém-criados
  que ainda não têm um node atribuído (unscheduled) e decide em qual node cada
  Pod vai rodar, levando em conta recursos disponíveis, constraints e políticas
- Chorus: algo memorável como "scheduler vê o Pod esperando, analisa o cluster
  inteiro / encontra o node certo, faz o match, nada é ao acaso aqui"
- Verse 2: os critérios de decisão — filtering (quais nodes podem receber o Pod)
  e scoring (qual node é o mais adequado); considera resources requests/limits,
  nodeSelector, affinity, taints e tolerations
- Bridge: o erro clássico — Pod preso em Pending porque nenhum node passou no
  filtering; insuficiência de CPU/memória, taint sem toleration, nodeSelector
  que não casa com nenhum node disponível
- Use analogies (ex: scheduler é como um gerente de hotel — verifica quais quartos
  têm espaço, qual se encaixa melhor no perfil do hóspede, e faz o check-in)
- Keep kube-scheduler, node, Pod, Pending, filtering, scoring, affinity,
  nodeSelector, taints, tolerations, resources em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
