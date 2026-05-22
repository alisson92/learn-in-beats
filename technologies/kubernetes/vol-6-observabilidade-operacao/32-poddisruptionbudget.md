# 🎵 PodDisruptionBudget

> **Volume:** Vol. 6 — Observabilidade & Operação
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/workloads/pods/disruptions/
> **Música gerada:** [Versão A](https://suno.com/s/ovXORpUUPJ6oJoaq) · [Versão B](https://suno.com/s/DcNDOmNgEZLhhyER)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: careful, steady, protective, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: PodDisruptionBudget

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of PodDisruptionBudget in Kubernetes.
The lyrics must:
- Verse 1: explique o problema — durante manutenções planejadas como atualizações
  de nodes ou drain, o Kubernetes pode remover vários Pods ao mesmo tempo; sem
  controle isso pode derrubar uma aplicação inteira; PodDisruptionBudget define
  quantos Pods podem ser removidos simultaneamente de forma segura
- Chorus: algo memorável como "PDB protege na hora da manutenção /
  minAvailable define o mínimo — o cluster respeita, não derruba sem razão"
- Verse 2: as duas formas de configurar — minAvailable (mínimo de Pods que
  devem permanecer durante a disrupção) e maxUnavailable (máximo que pode
  ficar indisponível); valores absolutos ou percentuais; essencial para apps
  críticas com poucas réplicas
- Bridge: o erro clássico — ter replicas: 1 sem PDB em produção; qualquer
  drain de node derruba o único Pod; PDB com minAvailable: 1 força o cluster
  a esperar um novo Pod estar pronto antes de remover o atual
- Use analogies (ex: PDB é como a regra de segurança de uma ponte —
  define quantos carros podem sair ao mesmo tempo sem comprometer a estrutura)
- Keep PodDisruptionBudget, PDB, Pod, minAvailable, maxUnavailable,
  drain, node, replicas em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Conceitos cobertos

- PDB para proteger apps durante manutenções planejadas (drain de nodes, atualizações)
- Configuração via minAvailable (mínimo online) ou maxUnavailable (máximo offline)
- Valores absolutos ou percentuais para aplicações críticas
- Combinação perigosa em produção: replicas: 1 sem PDB definido
