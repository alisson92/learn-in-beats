# 🎵 ServiceAccount

> **Volume:** Vol. 4 — Configuração & Segurança
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/security/service-accounts/
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: methodical, calm, security-minded, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: ServiceAccount

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of ServiceAccount in Kubernetes.
The lyrics must:
- Verse 1: explique o que é um ServiceAccount — é a identidade que um Pod
  usa para se autenticar no kube-apiserver; todo Pod roda com um ServiceAccount
  (default se nenhum for especificado); é por meio do ServiceAccount que o
  RBAC controla o que um Pod pode fazer no cluster
- Chorus: algo memorável como "ServiceAccount é a identidade do Pod /
  sem ela o cluster não sabe quem tá pedindo — RBAC decide o que pode"
- Verse 2: como funciona na prática — o Kubernetes monta automaticamente
  um token do ServiceAccount dentro do Pod; aplicações que interagem com
  a API do Kubernetes usam esse token para se autenticar; operators e
  controllers dependem disso para funcionar
- Bridge: o risco do default ServiceAccount — por padrão todos os Pods
  de um namespace usam o mesmo default; se ele tiver permissões demais,
  qualquer Pod comprometido vira vetor de ataque; sempre crie ServiceAccounts
  dedicados com least privilege
- Use analogies (ex: ServiceAccount é como o crachá do Pod — identifica
  quem ele é dentro do cluster e define onde ele pode entrar)
- Keep ServiceAccount, Pod, kube-apiserver, RBAC, token, namespace,
  least privilege em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
