# 🎵 PodSecurity & SecurityContext

> **Volume:** Vol. 4 — Configuração & Segurança
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/security/pod-security-standards/
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: serious, vigilant, security-minded, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: PodSecurity & SecurityContext

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of PodSecurity & SecurityContext in Kubernetes.
The lyrics must:
- Verse 1: explique o SecurityContext — é a configuração que define como
  um container roda no nível do SO; permite definir se roda como root ou não,
  se o filesystem é read-only, quais capabilities Linux são permitidas,
  e se o container pode escalar privilégios
- Chorus: algo memorável como "não roda como root, filesystem read-only /
  SecurityContext define os limites — container seguro é container bem definido"
- Verse 2: o Pod Security Admission — aplica políticas de segurança em
  namespaces inteiros; três perfis: Privileged (sem restrições), Baseline
  (restrições mínimas), Restricted (mais seguro); aplicado via label no namespace
- Bridge: o erro clássico — rodar containers como root porque é mais fácil;
  se o container for comprometido, o atacante tem acesso root no node; sempre
  defina runAsNonRoot: true e drop de capabilities desnecessárias
- Use analogies (ex: SecurityContext é como as regras de acesso de um laboratório —
  você pode entrar, mas não pode tocar em tudo e precisa usar EPI)
- Keep SecurityContext, Pod Security Admission, Privileged, Baseline,
  Restricted, runAsNonRoot, capabilities, read-only, namespace em inglês;
  rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
