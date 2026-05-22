# 🎵 NetworkPolicy

> **Volume:** Vol. 3 — Rede & Exposição
> **Tecnologia:** Kubernetes
> **Documentação oficial:** https://kubernetes.io/docs/concepts/services-networking/network-policies/
> **Música gerada:** [Versão A](https://suno.com/s/4E5O3YOGdAbRtgnb) · [Versão B](https://suno.com/s/SY9v28nvOnUvAiFy)

---

## Prompt

```
[STYLE]: lo-fi hip hop
[MOOD]: serious, focused, security-minded, educational
[LANGUAGE]: Brazilian Portuguese (technical terms in English)
[STRUCTURE]: verse, chorus, verse, chorus, bridge, chorus

[TOPIC]: NetworkPolicy

[INSTRUCTIONS]:
Write a song that teaches and reinforces the concept of NetworkPolicy in Kubernetes.
The lyrics must:
- Verse 1: explique o problema — por padrão, todo Pod pode falar com todo Pod
  no cluster sem restrição; isso é perigoso em produção; NetworkPolicy é o
  objeto que define quais Pods podem receber ou enviar tráfego, funcionando
  como um firewall declarativo no nível do Pod
- Chorus: algo memorável como "por padrão tudo aberto, NetworkPolicy fecha /
  ingress e egress controlados — só fala quem tem permissão, segurança de verdade"
- Verse 2: como funciona — regras de ingress controlam quem pode mandar
  tráfego para o Pod; regras de egress controlam para onde o Pod pode mandar;
  precisa de um CNI que suporte NetworkPolicy (Calico, Cilium, Weave)
- Bridge: o erro clássico — aplicar uma NetworkPolicy de deny-all sem antes
  mapear as dependências da aplicação; o Pod fica isolado, para de funcionar,
  e o debug vira pesadelo; sempre mapeie o tráfego antes de restringir
- Use analogies (ex: NetworkPolicy é como um firewall de data center, mas
  declarado em YAML — você define as regras, o CNI executa no kernel)
- Keep NetworkPolicy, Pod, ingress, egress, label, namespace, CIDR, CNI,
  Calico, Cilium em inglês; rest in Portuguese
- Be educational but feel like a real song, not a lecture
```
