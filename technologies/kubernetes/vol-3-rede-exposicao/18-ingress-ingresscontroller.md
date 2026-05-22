# 🎵 Ingress & IngressController

> **Volume:** Vol. 3 — Rede & Exposição
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/services-networking/ingress/
> **Música gerada:** 🔗 em breve

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: organized, calm, smart, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: Ingress & IngressController

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of Ingress & IngressController in Kubernetes.
The lyrics must:
- Verse 1: explique o problema que o Ingress resolve — sem ele, cada Service
  precisaria de um LoadBalancer externo próprio; o Ingress define regras de
  roteamento HTTP/HTTPS (por host ou path) para múltiplos Services, usando
  um único ponto de entrada
- Chorus: algo memorável como "um IP só, várias rotas — Ingress distribui
  pelo host e pelo path / api.site.com vai pro backend, site.com vai pro front"
- Verse 2: o IngressController — o Ingress sozinho não faz nada; precisa de
  um IngressController rodando no cluster para implementar as regras; os mais
  comuns são nginx-ingress, Traefik e AWS ALB Ingress Controller
- Bridge: TLS no Ingress — dá pra configurar terminação TLS direto no Ingress
  usando Secrets com certificados; combinado com cert-manager, os certificados
  se renovam automaticamente
- Use analogies (ex: Ingress é como um porteiro de shopping — um único portão
  de entrada, e ele direciona cada visitante para a loja certa pelo nome ou corredor)
- Keep Ingress, IngressController, Service, LoadBalancer, HTTP, HTTPS, TLS,
  nginx-ingress, Traefik, cert-manager, Secret em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
