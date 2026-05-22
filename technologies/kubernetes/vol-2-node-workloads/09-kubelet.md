# 🎵 kubelet

> **Volume:** Vol. 2 — Node & Workloads
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/architecture/#kubelet
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: focused, reliable, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: kubelet

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of kubelet in Kubernetes.
The lyrics must:
- Verse 1: explique o que é o kubelet — é o agente primário que roda em cada
  node; ele recebe PodSpecs via kube-apiserver e garante que os containers
  descritos nesses Pods estejam rodando e saudáveis; é o ponto de contato
  entre o Control Plane e o node
- Chorus: algo memorável como "kubelet recebe a spec, sobe o container /
  monitora, reporta — o node tá vivo porque ele não para"
- Verse 2: o que o kubelet faz continuamente — verifica se os containers estão
  saudáveis via liveness e readiness probes; reporta o status do node e dos
  Pods de volta ao kube-apiserver; se um container morrer, o kubelet age para
  reiniciá-lo conforme a restartPolicy
- Bridge: o que o kubelet NÃO gerencia — containers que não foram criados pelo
  Kubernetes; ele só cuida do que o cluster mandou ele cuidar
- Use analogies (ex: kubelet é como um encarregado de turno — recebe a ordem
  de serviço, executa, monitora e reporta tudo de volta para a gestão)
- Keep kubelet, PodSpec, kube-apiserver, liveness probe, readiness probe,
  restartPolicy, container, node em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
