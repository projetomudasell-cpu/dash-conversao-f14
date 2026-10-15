# Conversão F14 por página

Dashboard estático que compara a conversão em F14 dos compradores de ingresso (lote agosto/26) vindos da página **Tradicional** (campanhas PG1) e da página de **IA** (campanhas PG2), com o perfil de cada grupo a partir do formulário de matrícula.

- `index.html`: página completa, com os dados já embutidos (sem nomes, e-mails ou telefones).
- `vercel.json`: configuração da Vercel (pede para buscadores não indexarem a página).

## Deploy na Vercel

Importe este repositório em [vercel.com/new](https://vercel.com/new). Framework: **Other**. Não há comando de build nem diretório de saída. Cada push na `main` publica de novo.

## Atualizar os números

Os dados ficam fixos no `index.html`. Para atualizar, gere o arquivo de novo a partir das planilhas mais recentes e faça o commit aqui.

## Debriefing Pablo — Setembro/26

`debriefing-pablo-set26/index.html`: debriefing do lançamento pago de setembro/26 (investimento, métricas pré e pós-abertura de carrinho, públicos, campanhas, páginas e criativos), com os dados agregados já embutidos (sem nomes, e-mails ou telefones). Na Vercel fica em `/debriefing-pablo-set26`.
