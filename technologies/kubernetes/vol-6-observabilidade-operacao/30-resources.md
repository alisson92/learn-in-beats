# 🎵 Resources (requests & limits)

> **Volume:** Vol. 6 — Observabilidade & Operação
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: balanced, focused, practical, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Resources (requests & limits)

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Resources (requests & limits) in Kubernetes.
The lyrics must:
- Verse 1: explique a diferença — request é o que o container garante que vai
  ter (usado pelo scheduler para decidir em qual node o Pod vai); limit é o
  máximo que pode consumir; sem definir esses valores o scheduler age no escuro
  e nodes podem ser sobrecarregados
- Chorus: algo memorável como "request é o mínimo garantido, limit é o teto /
  scheduler usa o request — sem definir isso o cluster vira caos completo"
- Verse 2: o que acontece ao ultrapassar os limites — CPU é throttled (container
  fica mais lento mas não morre); memória é diferente: se ultrapassar o limit,
  o container recebe OOMKilled e é reiniciado; essa diferença é fundamental
  para debugar problemas de performance
- Bridge: o erro clássico — não definir resources.limits em produção; um
  container com memory leak consome toda a memória do node e derruba outros Pods;
  sempre defina requests e limits, especialmente em EKS
- Use analogies (ex: request é a mesa reservada — garantida para você;
  limit é a capacidade máxima do restaurante — ninguém passa disso)
- Keep resources, requests, limits, CPU, memory, scheduler, OOMKilled,
  throttling, node, Pod em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
