# 🎵 Namespaces & Contexts

> **Volume:** Vol. 6 — Observabilidade & Operação
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/
> **Música gerada:** [Versão A](https://suno.com/s/l03i9iHGphMBlJON) · [Versão B](https://suno.com/s/XdpQlZiEzuR9Zwbh)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: organized, calm, practical, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Namespaces & Contexts

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Namespaces & Contexts in Kubernetes.
The lyrics must:
- Verse 1: explique o que são Namespaces — são divisões lógicas dentro do
  cluster que isolam recursos; permitem que múltiplas equipes ou ambientes
  (dev, staging, prod) coexistam no mesmo cluster sem interferência;
  RBAC e ResourceQuota se aplicam por namespace
- Chorus: algo memorável como "namespace divide, organiza o cluster /
  dev não enxerga prod — cada time no seu espaço, tudo no lugar"
- Verse 2: o kubectl context — é a combinação de cluster, namespace e usuário
  que o kubectl usa para saber com quem está falando; trocar de contexto é
  trocar de ambiente; kubectl config use-context e kubectx são seus melhores
  amigos no dia a dia
- Bridge: o erro clássico — trabalhar no contexto errado e aplicar um manifest
  em produção achando que estava em dev; sempre confirme o contexto antes de
  qualquer comando destrutivo; um alias que mostra o contexto no terminal
  salva vidas em plantão noturno
- Use analogies (ex: namespace é como um andar de um prédio corporativo —
  cada time tem seu andar; o context é o crachá que define em qual andar você entra)
- Keep namespace, context, kubectl, RBAC, ResourceQuota, kubectx,
  kubectl config use-context em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
