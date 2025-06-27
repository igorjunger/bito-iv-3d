Visualização 3D da Volatilidade Implícita - Opções de BITO
Este notebook coleta e visualiza os dados das opções de compra (calls) do ETF BITO (Bitcoin Strategy ETF), criando um gráfico 3D da volatilidade implícita com base no strike e no tempo até o vencimento.

🧠 Objetivo
Coletar os dados de volatilidade implícita das opções para os próximos 3 vencimentos
Calcular o tempo até vencimento em anos (TTM)
Gerar um gráfico 3D com:
Eixo X = Strike
Eixo Y = Tempo até vencimento
Eixo Z = Volatilidade Implícita (IV)
📦 Requisitos
pip install yfinance pandas matplotlib
