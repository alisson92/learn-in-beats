# 🎵 Volume

> **Volume:** Vol. 5 — Armazenamento
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/storage/volumes/
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: grounded, calm, foundational, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Volume

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Volume in Kubernetes.
The lyrics must:
- Verse 1: explique o problema — containers são efêmeros; quando um container
  reinicia, tudo que foi escrito no filesystem se perde; Volume é a solução:
  um diretório acessível aos containers de um Pod que sobrevive ao restart
- Chorus: algo memorável como "container morreu, o Volume ficou /
  dados não se perdem — Volume é a memória que o Pod carregou"
- Verse 2: os tipos mais comuns — emptyDir (temporário, vive enquanto o Pod
  viver), hostPath (monta diretório do node), configMap e secret (montam configs
  como arquivos), persistentVolumeClaim (acessa armazenamento persistente externo)
- Bridge: Volume vs PersistentVolume — Volume tem ciclo de vida do Pod;
  PersistentVolume tem ciclo de vida independente; para dados que precisam
  sobreviver além do Pod, sempre use PersistentVolumeClaim
- Use analogies (ex: Volume é como um pendrive plugado no container —
  o computador pode reiniciar, mas o pendrive continua com os dados)
- Keep Volume, emptyDir, hostPath, configMap, secret,
  PersistentVolumeClaim, Pod, container em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
