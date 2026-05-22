# 🎵 ConfigMap

> **Volume:** Vol. 4 — Configuração & Segurança
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/configuration/configmap/
> **Música gerada:** [Versão A](https://suno.com/s/LRoLCNuthlnMgpDj) · [Versão B](https://suno.com/s/w7vw4jp94MMcIofI)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: organized, calm, practical, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: ConfigMap

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of ConfigMap in Kubernetes.
The lyrics must:
- Verse 1: explique o problema que o ConfigMap resolve — hardcodar configurações
  dentro da imagem é uma má prática; o ConfigMap armazena dados de configuração
  não sensíveis em pares chave-valor, separando config do código; a mesma imagem
  roda em dev, staging e prod com configs diferentes
- Chorus: algo memorável como "config fora da imagem, ConfigMap guarda /
  chave e valor no cluster — a app lê sem saber de onde vem"
- Verse 2: as formas de consumir um ConfigMap — como variável de ambiente,
  como arquivo montado em um volume, ou via API; volume mount é o mais flexível
  pois permite atualização sem restart do Pod
- Bridge: o que NÃO guardar em ConfigMap — dados sensíveis como senhas,
  tokens e chaves de API; para isso existe o Secret; misturar os dois é
  um risco de segurança
- Use analogies (ex: ConfigMap é como um arquivo .env do cluster — a app
  lê as configs sem precisar saber onde estão armazenadas)
- Keep ConfigMap, Secret, Pod, volume, environment variable, key-value
  em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
