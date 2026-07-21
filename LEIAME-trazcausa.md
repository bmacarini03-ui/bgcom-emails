# TrazCausa: e-mail de classificacao por area

Dois arquivos, mesmo texto, links diferentes. O objetivo dos dois e o mesmo:
fazer o advogado se declarar previdenciario ou trabalhista com um clique.

## A (enviado em 21/07/2026, 14:11, para 24.463)
`trazcausa-classificacao-a-enviado-21-07.html`
Links vao direto para o WhatsApp com a mensagem ja escrita.
Clique custa mais, mas quem clica ja vira conversa.

## B (reserva, para reaquecimento / teste)
`trazcausa-classificacao-b.html`
Espelho publicado tambem em `trazcausa-classificacao.html` (URL que o Bruno guardou).
Links vao para `ok-previdenciario.html` e `ok-trabalhista.html`, que registram
o clique, agradecem e oferecem o WhatsApp como opcao. Clique mais barato,
classificacao em maior volume.

## Onde os cliques caem
As duas versoes alimentam AS MESMAS segmentacoes no RD:
- `[trazcausa] AREA previdenciario`
- `[trazcausa] AREA trabalhista reclamante`

Ao disparar o B, adicionar em cada segmentacao uma condicao com operador OU:
"Clicou no link do email" > (o e-mail do disparo B) > (a URL ok-previdenciario
ou ok-trabalhista). O balde continua unico.
