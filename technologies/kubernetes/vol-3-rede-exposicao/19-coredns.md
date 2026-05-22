# 🎵 CoreDNS

> **Volume:** Vol. 3 — Rede & Exposição
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/
> **Música gerada:** [Versão A](https://suno.com/s/hTpzhiG0MJAUaNRL) · [Versão B](https://suno.com/s/KW7KMaD34uZOWKy1)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: quiet, smooth, invisible, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: CoreDNS

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of CoreDNS in Kubernetes.
The lyrics must:
- Verse 1: explique o papel do CoreDNS — é o servidor DNS que roda dentro do
  cluster; todo Service criado ganha automaticamente um registro DNS no formato
  service.namespace.svc.cluster.local; Pods se comunicam por nome, não por IP
- Chorus: algo memorável como "não precisa de IP pra chamar o Service /
  CoreDNS resolve o nome — dentro do cluster tudo tem endereço"
- Verse 2: como funciona na prática — quando um Pod faz uma requisição para
  um service, o CoreDNS resolve para o ClusterIP; a resolução é automática
  dentro do mesmo namespace; entre namespaces precisa do FQDN completo
- Bridge: debugging de DNS — falha de resolução DNS é um dos problemas mais
  comuns em Kubernetes; kubectl exec em um Pod e usar nslookup ou dig para
  testar a resolução é o primeiro passo do diagnóstico
- Use analogies (ex: CoreDNS é como a lista telefônica interna de uma empresa —
  você disca pelo nome do ramal, não pelo número, e ela resolve pra você)
- Keep CoreDNS, DNS, Service, ClusterIP, namespace, FQDN, nslookup, dig,
  cluster.local em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```

---

## Conceitos cobertos

- CoreDNS como servidor DNS interno do cluster
- Registro DNS automático para Services no formato service.namespace.svc.cluster.local
- Resolução dentro do mesmo namespace vs entre namespaces (FQDN completo)
- Debug de DNS: nslookup e dig via kubectl exec como primeiro passo do diagnóstico
