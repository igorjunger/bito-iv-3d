# Visualização 3D da Volatilidade Implícita - Opções de BITO

Este projeto contém um notebook Jupyter que coleta e visualiza os dados das opções de compra (calls) do ETF **BITO** (Bitcoin Strategy ETF). Ele gera um gráfico 3D da volatilidade implícita com base no strike e no tempo até o vencimento.

---

## Objetivo

- Coletar os dados de volatilidade implícita das opções para os próximos 3 vencimentos.
- Calcular o tempo até vencimento em anos (TTM).
- Gerar um gráfico 3D com:
  - Eixo X = Strike
  - Eixo Y = Tempo até vencimento
  - Eixo Z = Volatilidade Implícita (IV).

---

## Requisitos

Para rodar o notebook, instale as bibliotecas abaixo:

```bash
pip install yfinance pandas matplotlib
