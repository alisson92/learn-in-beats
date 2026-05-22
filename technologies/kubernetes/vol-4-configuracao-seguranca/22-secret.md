# 🎵 Secret

> **Volume:** Vol. 4 — Configuração & Segurança
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/configuration/secret/
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: serious, careful, security-minded, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Secret

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Secret in Kubernetes.
The lyrics must:
- Verse 1: explique o que é um Secret — é o objeto para armazenar dados
  sensíveis como senhas, tokens OAuth, chaves SSH e certificados TLS;
  os dados são codificados em base64 (não criptografados por padrão) e
  injetados nos Pods via variável de ambiente ou volume
- Chorus: algo memorável como "Secret guarda o que não pode aparecer /
  base64 não é segurança — encryption at rest é o que você precisa ter"
- Verse 2: como usar com segurança — habilitar encryption at rest no etcd;
  usar RBAC para restringir quem pode ler Secrets; considerar soluções
  externas como HashiCorp Vault ou AWS Secrets Manager para ambientes críticos
- Bridge: o erro clássico — commitar Secrets em YAML no Git; base64 é
  facilmente decodificado; um Secret no Git é um Secret exposto; use
  Sealed Secrets ou External Secrets Operator
- Use analogies (ex: Secret é como um cofre no cluster — existe para guardar
  o que é valioso, mas a segurança depende de quem tem a chave)
- Keep Secret, base64, etcd, encryption at rest, RBAC, Vault,
  Sealed Secrets, External Secrets Operator em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
