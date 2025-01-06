## Projeto soybean compra venda mantem

### Problem:
The decision to buy, sell or hold soybean securities is a complex issue involving a number of economic and market factors. To make informed decisions, it is essential to conduct market analysis, which includes:
Historical trends: Studying past price behavior can help predict future movements.
Supply and demand reports: Information on stocks, harvests and consumption is crucial.
Economic indicators: Interest rates, inflation and exchange rates can influence the profitability of investments.

A decisão de comprar, vender ou manter títulos de soja é uma questão complexa que envolve uma série de fatores econômicos e de mercado. Para tomar decisões informadas, é essencial realizar uma análise de mercado, que inclui:
Tendências históricas: Estudar o comportamento passado dos preços pode ajudar a prever movimentos futuros.
Relatórios de oferta e demanda: Informações sobre estoques, colheitas e consumo são cruciais.
Indicadores econômicos: Taxas de juros, inflação e câmbio podem influenciar a rentabilidade dos investimentos.

### Motivation:
Reinforcement learning (AR) is a powerful artificial intelligence approach that has gained prominence in financial decision-making, especially in the trading of commodities such as soybeans. 

The soybean market is characterized by:
High volatility: Prices change rapidly due to factors such as weather, global demand, and trade policies.
Uncertainty: The stochastic nature of the variables involved makes price prediction challenging.
AR is well suited for this scenario because it allows an agent to learn from interacting with the environment, adjusting its decisions based on rewards and penalties.

O aprendizado por reforço (AR) é uma abordagem poderosa de inteligência artificial que tem ganhado destaque na tomada de decisões financeiras, especialmente na negociação de commodities como a soja. 

O mercado de soja é caracterizado por:
Alta volatilidade: Os preços mudam rapidamente devido a fatores como clima, demanda global e políticas comerciais.
Incerteza: A natureza estocástica das variáveis envolvidas torna a previsão de preços um desafio.
O AR é adequado para esse cenário, pois permite que um agente aprenda a partir da interação com o ambiente, ajustando suas decisões com base em recompensas e penalidades.

### Solution:
The adoption of reinforcement learning (AR) to solve the decision problem of buying, selling or holding soybean futures presents a series of advantages that align with the complexities and dynamics of the agricultural market. Reinforcement learning allows:

Continuous Learning
Adapts to new information: The agent can continuously learn from new situations and adjust its strategies in real time.
Improves over time: With accumulated experience, the agent's performance tends to improve, leading to more informed decisions.

A adoção de aprendizado por reforço (AR) para solucionar o problema de decisão de compra, venda ou manutenção de títulos de soja futuros apresenta uma série de vantagens que se alinham com as complexidades e dinâmicas do mercado agrícola. O Aprendizado por reforço permite:

Aprendizado Contínuo
    Adapta-se a novas informações: O agente pode aprender continuamente com novas situações e ajustar suas estratégias em tempo real.
    Melhora ao longo do tempo: Com a experiência acumulada, o desempenho do agente tende a se aprimorar, levando a decisões mais informadas.

### Objective:
- This project aims to create clusters defined according to the characteristics of credit card holders, grouping these holders and characterizing the clusters based on the occurrence of the variables used.

- Esse projeto tem como objetivo treinar um modelo, utilizando aprendizado por reforço, que nos orientará se no momento atual devemos comprar, vender ou manter os títulos (contratos) de soja futuros.

### Data Origin:
- Dataset: https://www.kaggle.com/datasets/choweric/cbot-soybeans/data

- This project aims to train a model, using reinforcement learning, that will guide us whether we should currently buy, sell or hold future soybean bonds (contracts).

- O Dataset de cotação do preço da soja apresenta cotações diárias com data do dia de cotação dos valores de títulos futuros da soja na bolsa de valores, com valores percorridos durante todo o dia.

- A seguir está o Dicionário de Dados para o conjunto de dados cotação de título de soja:

    Date: data da ocorrência da cotação
    Open: valor cotado na abertura dos trabalhos de negociação
    High: valor máximo atingido no período de negociação
    Low:  valor mínimo atingido no período de negociação
    Volume: nro de contratos negociados no período de negociação
    Open interest: fluxo de dinheiro para dentro ou para fora de um mercado de futuros