# 🎵 Control Plane

> **Volume:** Vol. 1 — Fundamentos do Cluster
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/architecture/
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: focused, authoritative, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Control Plane — visão geral e papel no cluster Kubernetes

[INSTRUCTIONS]:
Write a song that teaches and reinforces what the Kubernetes Control Plane is.
The lyrics must:
- Verse 1: explique o que é o Control Plane — é o cérebro do cluster; é ele
  que toma as decisões globais sobre o cluster (como scheduling), detecta e
  responde a eventos (como um Pod que caiu e precisa ser reiniciado); sem o
  Control Plane, o cluster não tem direção
- Chorus: algo memorável como "Control Plane decide, observa e age /
  kube-apiserver, etcd, scheduler — tudo junto, o cluster se faz"
- Verse 2: os componentes que formam o Control Plane e seus papéis resumidos —
  kube-apiserver (porta de entrada), etcd (memória do cluster),
  kube-scheduler (decide onde o Pod vai), kube-controller-manager (fiscal
  do estado desejado), cloud-controller-manager (ponte com a nuvem)
- Bridge: a diferença entre Control Plane e worker nodes — o Control Plane
  pensa e decide, os nodes executam; em produção o Control Plane roda em
  máquinas separadas dos workloads para garantir disponibilidade e segurança
- Use analogies (ex: Control Plane é como a torre de controle de um aeroporto —
  ela não voa, mas sem ela nenhum avião sabe onde pousar)
- Keep Control Plane, kube-apiserver, etcd, kube-scheduler, kube-controller-manager,
  cloud-controller-manager, worker node, scheduling em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Conceitos cobertos

- Papel do Control Plane no cluster
- Componentes que formam o Control Plane
- Separação entre Control Plane e worker nodes
- Alta disponibilidade em produção

