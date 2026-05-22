# 🎵 Probes

> **Volume:** Vol. 6 — Observabilidade & Operação
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/#container-probes
> **Música gerada:** [Versão A](https://suno.com/s/VV2i31eMo00er1J7) · [Versão B](https://suno.com/s/EyTuKqsMsWunG5BG)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: vigilant, calm, reliable, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Probes

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Probes in Kubernetes.
The lyrics must:
- Verse 1: explique o problema — o kubelet precisa saber se um container
  está vivo, se está pronto para receber tráfego, e se ainda está iniciando;
  sem probes o Kubernetes não distingue um container saudável de um que travou
  silenciosamente; probes são os olhos do kubelet
- Chorus: algo memorável como "liveness vê se tá vivo, readiness se tá pronto /
  startup dá o tempo de nascer — sem probe o cluster fica cego"
- Verse 2: os três tipos — liveness (se falhar, container é reiniciado),
  readiness (se falhar, Pod é removido do endpoint do Service),
  startup (desativa liveness e readiness até o container terminar de inicializar)
- Bridge: o erro clássico — configurar liveness com threshold muito agressivo;
  a app demora numa requisição pesada, a probe falha, o container reinicia,
  loop infinito de CrashLoopBackOff; calibre initialDelaySeconds e failureThreshold
- Use analogies (ex: liveness é o médico que checa se o paciente respira;
  readiness é o check de alta; startup é o tempo de recuperação pós-cirurgia)
- Keep liveness probe, readiness probe, startup probe, kubelet, Pod,
  Service, CrashLoopBackOff, initialDelaySeconds, failureThreshold
  em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Conceitos cobertos

- Os três tipos de probe: liveness (reinicia se falhar), readiness (remove do Service se falhar), startup (protege durante inicialização)
- Papel das probes como "olhos do kubelet" para distinguir container saudável de travado
- Parâmetros críticos de calibração: initialDelaySeconds e failureThreshold
- CrashLoopBackOff causado por liveness probe agressiva em requisições lentas
