# 🎵 Container Runtime

> **Volume:** Vol. 2 — Node & Workloads
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/architecture/#container-runtime
> **Música gerada:** [Versão A](https://suno.com/s/DbUz7k8lAM9NSWlN) · [Versão B](https://suno.com/s/t0uXMJbU7j8MdU4S)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: grounded, calm, foundational, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Container Runtime

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Container Runtime in Kubernetes.
The lyrics must:
- Verse 1: explique o que é o container runtime — é o software responsável por
  executar os containers no node; o Kubernetes não roda containers diretamente,
  ele delega ao runtime via CRI (Container Runtime Interface); exemplos: containerd, CRI-O
- Chorus: algo memorável como "Kubernetes decide, o runtime executa /
  containerd sobe o container — a imagem vira processo, a app funciona"
- Verse 2: como a comunicação funciona — o kubelet fala com o runtime via CRI;
  o runtime puxa a imagem do registry, cria o container com os recursos
  definidos e gerencia o ciclo de vida; o Kubernetes abstrai tudo atrás da CRI
- Bridge: a história do Docker — por muito tempo foi o runtime padrão, mas
  o Kubernetes removeu o suporte direto ao Docker (dockershim) em favor da CRI;
  containerd (o core do Docker) continua sendo muito usado
- Use analogies (ex: container runtime é como a cozinha de um restaurante —
  o Kubernetes é o garçom que anota o pedido, mas é a cozinha que prepara)
- Keep container runtime, CRI, containerd, CRI-O, kubelet, registry, Docker,
  dockershim, image em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Conceitos cobertos

- O que é o container runtime e por que o Kubernetes delega a execução a ele
- Container Runtime Interface (CRI) como camada de abstração
- Exemplos de runtimes: containerd e CRI-O
- História do Docker: remoção do dockershim e continuidade via containerd
