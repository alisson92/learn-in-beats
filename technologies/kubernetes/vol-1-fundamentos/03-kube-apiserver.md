# 🎵 kube-apiserver

> **Volume:** Vol. 1 — Fundamentos do Cluster
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: focused, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: kube-apiserver — a porta de entrada do cluster Kubernetes

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of the kube-apiserver.
The lyrics must:
- Verse 1: explique o que é o kube-apiserver — ele valida e configura dados de todos
  os objetos da API (pods, services, replicationcontrollers e outros); é o frontend
  do estado compartilhado do cluster, e todos os outros componentes passam por ele
- Chorus: algo memorável como "tudo passa pelo API Server, nada acontece sem ele saber /
  ele valida, ele responde, é a porta do cluster que você vai bater"
- Verse 2: como ele funciona na prática — recebe chamadas REST do kubectl, do scheduler,
  do controller-manager, do kubelet; autentica, autoriza, e persiste no etcd;
  sem o API Server o cluster para
- Bridge: o erro clássico — tentar interagir direto com o etcd ou com outro componente
  sem passar pelo API Server; ele existe por um motivo: controle, segurança, consistência
- Use analogies (ex: kube-apiserver é como a recepção de um prédio corporativo —
  tudo e todos passam por ela, ninguém acessa direto as salas sem antes ser validado)
- Keep kube-apiserver, REST, kubectl, etcd, scheduler, controller-manager, kubelet,
  authentication, authorization em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Conceitos cobertos

- Validação e configuração de objetos da API
- Frontend do estado compartilhado do cluster
- Fluxo: autenticação → autorização → persistência no etcd
- Por que todos os componentes passam pelo API Server

