# 🎵 StorageClass

> **Volume:** Vol. 5 — Armazenamento
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/storage/storage-classes/
> **Música gerada:** [Versão A](https://suno.com/s/b91CTlBmpWx8oSua) · [Versão B](https://suno.com/s/vQ8jTp9hzHYCBAaL)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: dynamic, efficient, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: StorageClass

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of StorageClass in Kubernetes.
The lyrics must:
- Verse 1: explique o problema — sem StorageClass, alguém precisa criar PVs
  manualmente antes que os Pods possam usá-los; StorageClass habilita o
  provisionamento dinâmico: quando um PVC é criado, o Kubernetes automaticamente
  provisiona o PV correspondente no cloud provider
- Chorus: algo memorável como "PVC criou, StorageClass agiu /
  disco provisionado automático — sem StorageClass alguém ia ter que criar"
- Verse 2: como configurar — a StorageClass define o provisioner (quem cria
  o disco: aws-ebs, gce-pd), os parâmetros (tipo: gp3, ssd) e a reclaim policy;
  um cluster pode ter múltiplas StorageClasses; uma é marcada como default
- Bridge: o erro clássico — usar a StorageClass default do cloud provider sem
  verificar o tipo e custo; em EKS o default pode provisionar gp2 quando gp3
  é mais barato e performático; sempre revise antes de ir para produção
- Use analogies (ex: StorageClass é como um cardápio de armazenamento —
  você escolhe o tipo via PVC e a cozinha provisiona sem você ir ao supermercado)
- Keep StorageClass, PersistentVolume, PersistentVolumeClaim, PV, PVC,
  provisioner, reclaim policy, EKS, gp2, gp3 em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
