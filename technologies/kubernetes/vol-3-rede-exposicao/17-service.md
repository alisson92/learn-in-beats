# 🎵 Service

> **Volume:** Vol. 3 — Rede & Exposição
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/services-networking/service/
> **Música gerada:** [Versão A](https://suno.com/s/m92CRxEaeWCujVhw) · [Versão B](https://suno.com/s/o4h1SCAEgjMKdjuy)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: smooth, reliable, calm, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Service

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Service in Kubernetes.
The lyrics must:
- Verse 1: explique o problema que o Service resolve — Pods têm IPs efêmeros,
  morrem e voltam com IPs diferentes; o Service fornece IP e DNS estáveis
  que apontam sempre para os Pods saudáveis via label selector
- Chorus: algo memorável como "Pod muda de IP, Service não muda não /
  selector encontra quem tá vivo — tráfego chega no destino certo então"
- Verse 2: os três tipos principais — ClusterIP (só acessível dentro do
  cluster, padrão), NodePort (expõe em uma porta de cada node), LoadBalancer
  (provisiona load balancer externo no cloud provider)
- Bridge: o erro clássico — expor tudo como LoadBalancer sem necessidade;
  cada LoadBalancer custa dinheiro no cloud; use ClusterIP internamente,
  Ingress para HTTP/HTTPS, e LoadBalancer só quando realmente necessário
- Use analogies (ex: Service é como uma recepção corporativa — não importa
  quantos funcionários entraram ou saíram, o número da recepção nunca muda)
- Keep Service, ClusterIP, NodePort, LoadBalancer, Pod, label selector,
  Ingress em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
