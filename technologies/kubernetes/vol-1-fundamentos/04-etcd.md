# 🎵 etcd

> **Volume:** Vol. 1 — Fundamentos do Cluster
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/architecture/#etcd
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: focused, calm, slightly mysterious, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: etcd

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of etcd in Kubernetes.
The lyrics must:
- Verse 1: explique o que é o etcd — um armazenamento chave-valor consistente e
  de alta disponibilidade que guarda todos os dados do cluster; é a única fonte
  de verdade do Kubernetes, onde tudo que existe no cluster está registrado
- Chorus: algo memorável como "etcd guarda tudo, não esquece nada /
  chave e valor, a memória do cluster que nunca falha"
- Verse 2: como o etcd funciona na prática — só o kube-apiserver fala diretamente
  com ele; usa o protocolo Raft para garantir consistência entre múltiplas instâncias;
  backup do etcd é backup do cluster inteiro
- Bridge: o que acontece se o etcd for perdido sem backup — o cluster perde todo
  o seu estado, Pods, Deployments, Secrets, tudo some; etcd é sagrado em produção
- Use analogies (ex: etcd é o cartório do cluster — tudo que existe precisa estar
  registrado lá, e o que não está registrado, não existe)
- Keep etcd, kube-apiserver, key-value, Raft, backup, cluster state em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
