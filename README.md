# Dashboard de Vendas Porsche

Dashboard interativo desenvolvido para o desafio do curso, a partir de uma base de 100 vendas de Porsche nos EUA.

🔗 **Acesse:** https://viniciusandrade91.github.io/dashboard-vendas-porsche-3.html/

## Perguntas respondidas
- Qual modelo tem a maior venda efetivada?
- Qual ano teve mais vendas?
- Qual a forma de pagamento mais recorrente?
- Como está a distribuição dos status de entrega?

## Filtros
Modelo, ano da venda, forma de pagamento e status de entrega.

## Tratamento dos dados
- Datas padronizadas e preço ausente (venda ID 20) preenchido com base na planilha bruta.
- 24 vendas com data inexistente (ex.: 30/02) ficam fora das análises por ano.
- Valores vazios ou zerados foram desconsiderados nos cálculos.
- **Venda efetivada** = status *Delivered*.

## Tecnologias
HTML, CSS e JavaScript puro (sem bibliotecas externas).

## Arquivos
- `index.html`: o dashboard
- `Desafio_Corrigido.xlsx`: base de dados tratada
