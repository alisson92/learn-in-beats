# 🎵 Deployment & ReplicaSet

> **Volume:** Vol. 2 — Node & Workloads
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/workloads/controllers/deployment/
> **Música gerada:** [Versão A](https://suno.com/s/PkgAjGBRoAsxhEfz) · [Versão B](https://suno.com/s/9pZ8FJwuRm8RYxp1)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: confident, steady, motivating, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Deployment & ReplicaSet

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Deployment & ReplicaSet in Kubernetes.
The lyrics must:
- Verse 1: explique o Deployment — você declara o estado desejado (quantas
  réplicas, qual imagem), e o Deployment garante que o cluster convirja para
  esse estado; ele cria e gerencia ReplicaSets, que por sua vez garantem o
  número correto de Pods rodando
- Chorus: algo memorável como "declara o estado, o Deployment age /
  rolling update sem downtime — replica sempre em pé, rollback se errar"
- Verse 2: o processo de atualização — rolling update substitui Pods antigos
  por novos gradualmente, garantindo zero downtime; se algo der errado,
  o rollback volta para a versão anterior com um comando
- Bridge: a hierarquia que não se deve ignorar — Deployment gerencia
  ReplicaSet, ReplicaSet gerencia Pod; nunca edite o ReplicaSet diretamente,
  o Deployment vai sobrescrever; respeite a cadeia de comando
- Use analogies (ex: Deployment é o diretor, ReplicaSet é o supervisor,
  Pod é o colaborador — cada um tem seu papel na hierarquia)
- Keep Deployment, ReplicaSet, Pod, rolling update, rollback, desired state,
  replica em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
