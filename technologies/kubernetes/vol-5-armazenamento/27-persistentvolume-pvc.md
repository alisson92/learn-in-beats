# 🎵 PersistentVolume & PersistentVolumeClaim

> **Volume:** Vol. 5 — Armazenamento
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/storage/persistent-volumes/
> **Música gerada:** [Versão A](https://suno.com/s/LjUV1E3gYPhNvp8v) · [Versão B](https://suno.com/s/0cPfTfcXWwhozSGv)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: reliable, steady, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: PersistentVolume & PersistentVolumeClaim

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of PersistentVolume & PersistentVolumeClaim in Kubernetes.
The lyrics must:
- Verse 1: explique a separação — o PersistentVolume (PV) é o armazenamento
  real provisionado pelo admin ou dinamicamente; o PersistentVolumeClaim (PVC)
  é o pedido feito pelo desenvolvedor: preciso de 10Gi com ReadWriteOnce;
  o Kubernetes faz o binding entre PVC e PV automaticamente
- Chorus: algo memorável como "PV é o disco, PVC é o pedido /
  Kubernetes faz o match — armazenamento provisionado, Pod servido"
- Verse 2: o ciclo de vida — o PVC é criado, o Kubernetes busca um PV
  compatível e faz o binding; o Pod monta o PVC como Volume; quando o PVC
  é deletado, o que acontece com o PV depende da reclaim policy:
  Retain (mantém), Delete (apaga tudo), Recycle (deprecated)
- Bridge: o erro clássico — deletar um PVC sem verificar a reclaim policy;
  com Delete policy o disco some junto; em produção sempre verifique antes
  de deletar qualquer PVC
- Use analogies (ex: PV é o apartamento disponível; PVC é o contrato de
  locação — o inquilino não precisa saber como foi construído)
- Keep PersistentVolume, PersistentVolumeClaim, PV, PVC, Pod, binding,
  ReadWriteOnce, reclaim policy, Retain, Delete, StorageClass em inglês;
  rest in Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Conceitos cobertos

- PersistentVolume (PV) como armazenamento real e PVC como pedido do desenvolvedor
- Binding automático entre PVC e PV compatível pelo Kubernetes
- Reclaim policies e seus impactos: Retain (mantém dados), Delete (apaga tudo)
- Risco de deletar PVC sem verificar a reclaim policy em produção
