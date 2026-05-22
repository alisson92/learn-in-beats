# 🎵 RBAC

> **Volume:** Vol. 4 — Configuração & Segurança
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/reference/access-authn-authz/rbac/
> **Música gerada:** [Versão A](https://suno.com/s/B7lJcg0YQNSo9CGW) · [Versão B](https://suno.com/s/5JY5PuWN915kPwcs)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: serious, structured, security-minded, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: RBAC

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of RBAC in Kubernetes.
The lyrics must:
- Verse 1: explique o que é RBAC — Role-Based Access Control é o sistema
  de permissões do Kubernetes; define quem pode fazer o quê em quais recursos;
  sem RBAC qualquer ServiceAccount teria acesso a tudo, o que é um risco enorme
- Chorus: algo memorável como "Role define o que pode, RoleBinding liga quem é /
  least privilege é a lei — só acessa quem precisa, nada além"
- Verse 2: os quatro objetos principais — Role (permissões em um namespace),
  ClusterRole (permissões em todo o cluster), RoleBinding (liga um Role a um
  usuário ou ServiceAccount), ClusterRoleBinding (liga um ClusterRole globalmente)
- Bridge: o erro clássico — dar wildcard (*) em verbs e resources por preguiça;
  equivale a dar acesso root no cluster; em produção isso é uma vulnerabilidade
  crítica; sempre aplique least privilege
- Use analogies (ex: RBAC é como crachá de acesso corporativo — cada funcionário
  entra só onde o crachá permite, nem mais, nem menos)
- Keep RBAC, Role, ClusterRole, RoleBinding, ClusterRoleBinding,
  ServiceAccount, namespace, wildcard, least privilege em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
