# 🎵 HorizontalPodAutoscaler

> **Volume:** Vol. 6 — Observabilidade & Operação
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/workloads/autoscaling/
> **Música gerada:** [Versão A](https://suno.com/s/5aCEHDQQaEtAF9NC) · [Versão B](https://suno.com/s/TOmjP36S9EdmIo9x)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: dynamic, responsive, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: HorizontalPodAutoscaler

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of HorizontalPodAutoscaler in Kubernetes.
The lyrics must:
- Verse 1: explique o que é o HPA — monitora métricas como uso de CPU e memória
  de um Deployment e automaticamente aumenta ou diminui o número de réplicas
  para manter a métrica dentro do target definido; escala horizontalmente sem
  intervenção manual
- Chorus: algo memorável como "CPU subiu, HPA age — mais réplicas entram
  pra aguentar a demanda / caiu o tráfego, ele escala pra baixo —
  HPA equilibra, o cluster não sobrecarrega"
- Verse 2: como funciona na prática — o HPA consulta o metrics-server a cada
  15 segundos; compara a métrica com o target; calcula o número ideal de
  réplicas; só funciona se resources.requests estiver definido nos containers
- Bridge: o erro clássico — criar HPA sem definir resources.requests; sem
  referência o HPA não consegue calcular o percentual de uso e não age;
  minReplicas muito baixo pode deixar o sistema sem capacidade para um pico
- Use analogies (ex: HPA é como um gerente de caixa de supermercado —
  quando a fila aumenta, abre mais caixas; quando esvazia, fecha os desnecessários)
- Keep HorizontalPodAutoscaler, HPA, Deployment, metrics-server, CPU,
  memory, replicas, requests, minReplicas, maxReplicas em inglês;
  rest in Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Conceitos cobertos

- HPA como mecanismo de escala horizontal automática baseada em métricas
- Integração com metrics-server: consulta a cada 15 segundos para calcular réplicas ideais
- Dependência obrigatória de resources.requests para o HPA funcionar
- Configuração de minReplicas e maxReplicas para evitar subprovisão e desperdício
