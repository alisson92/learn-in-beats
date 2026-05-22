# 🎵 kube-controller-manager

> **Volume:** Vol. 1 — Fundamentos do Cluster
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/architecture/#kube-controller-manager
> **Música gerada:** [Versão A](https://suno.com/s/QGoYH3yWdfnF2jhK) · [Versão B](https://suno.com/s/nr24Dv7QClCxyUxY)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: focused, steady, vigilant, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: kube-controller-manager

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of kube-controller-manager in Kubernetes.
The lyrics must:
- Verse 1: explique o que é o kube-controller-manager — ele roda múltiplos
  controllers em um único processo; cada controller observa o estado atual do
  cluster e age para aproximá-lo do estado desejado (desired state); é o loop
  de controle contínuo do Kubernetes
- Chorus: algo memorável como "estado atual, estado desejado — o controller
  não para, ele sempre está olhando / se algo mudou, ele age, reconverge,
  o cluster volta pro lugar"
- Verse 2: exemplos de controllers que ele gerencia — Node controller (detecta
  nodes que caem), Job controller (garante que Jobs completem), Endpoints
  controller (popula endpoints de Services), ServiceAccount controller
- Bridge: a filosofia por trás — reconciliation loop; o controller nunca
  empurra mudanças diretamente, ele observa via kube-apiserver e age
  de forma declarativa; é idempotente por design
- Use analogies (ex: kube-controller-manager é como um inspetor de qualidade
  numa linha de produção — fica checando se tudo está como deveria e corrige
  o que está fora do padrão)
- Keep kube-controller-manager, controller, desired state, reconciliation loop,
  Node controller, Job controller, kube-apiserver em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
