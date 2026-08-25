# Régua Prado — protótipo do quiz de qualificação

Protótipo navegável do quiz de lead qualificado da weareprado. Página única, sem dependência externa
além da fonte do Google Fonts. Abra `index.html` no navegador ou publique via GitHub Pages.

## O que este protótipo é

Uma **simulação da régua de qualificação**, não a versão de produção. Ele existe para o time comercial
responder como se fosse um dono de farmácia e verificar se o corte separa lead bom de lead ruim.

O painel à direita mostra a pontuação sendo calculada ao vivo, dimensão por dimensão.

## A régua — v1

| Dimensão | Peso |
|---|---|
| Investimento atual em marketing | 30 |
| Problema que quer resolver | 25 |
| Papel na farmácia (decisor) | 20 |
| Tamanho da operação | 15 |
| O que já tentou | 10 |

**Critério eliminatório:** não sustentar o investimento mínimo zera o lead, independente da pontuação.

**Cortes:** 70+ qualificado · 40–69 morno · abaixo de 40 não qualificado.

## O que ainda não está aqui

- Backend de cálculo (hoje o score roda no navegador — em produção roda no servidor)
- Disparo de evento de conversão e integração com CAPI
- Integração com CRM e agenda
- Páginas de destino definitivas
- Identidade visual da Prado

## Como validar

Rode os perfis reais de clientes que fecharam e de leads descartados. Se os dois grupos pontuarem
parecido, a régua está errada e os pesos precisam mudar — é exatamente para isso que este protótipo serve.

---

Etapa 0 do projeto de funil de lead qualificado · agosto de 2026
