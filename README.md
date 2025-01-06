## Projeto soybean compra venda mantem

### Problem:
Grouping credit card holders is an essential practice for credit card companies. This strategy allows them to check which group, or cluster, the cardholder belongs to, and they may receive additional benefits when using the card, or be subject to certain restrictions depending on the group to which they belong.

A decisão de comprar, vender ou manter títulos de soja é uma questão complexa que envolve uma série de fatores econômicos e de mercado. Para tomar decisões informadas, é essencial realizar uma análise de mercado, que inclui:
Tendências históricas: Estudar o comportamento passado dos preços pode ajudar a prever movimentos futuros.
Relatórios de oferta e demanda: Informações sobre estoques, colheitas e consumo são cruciais.
Indicadores econômicos: Taxas de juros, inflação e câmbio podem influenciar a rentabilidade dos investimentos.

### Motivation:
Credit Management
A well-structured grouping system helps to optimize the credit available to the holder, allowing them to extend their credit and buy more, while at the same time having their credit restricted according to the group they may belong to.

O aprendizado por reforço (AR) é uma abordagem poderosa de inteligência artificial que tem ganhado destaque na tomada de decisões financeiras, especialmente na negociação de commodities como a soja. 

O mercado de soja é caracterizado por:
Alta volatilidade: Os preços mudam rapidamente devido a fatores como clima, demanda global e políticas comerciais.
Incerteza: A natureza estocástica das variáveis envolvidas torna a previsão de preços um desafio.
O AR é adequado para esse cenário, pois permite que um agente aprenda a partir da interação com o ambiente, ajustando suas decisões com base em recompensas e penalidades.

### Solution:
Using credit card usage data, machine learning algorithms will be used to define credit card holder classification clusters, grouping those that are similar into groups that reflect the dynamics of card usage that will reveal the level of commitment both in consumption and in the coverage of this consumption, revealing their responsibility regarding the most appropriate use in the balance between credit and debit.

A adoção de aprendizado por reforço (AR) para solucionar o problema de decisão de compra, venda ou manutenção de títulos de soja futuros apresenta uma série de vantagens que se alinham com as complexidades e dinâmicas do mercado agrícola. O Aprendizado por reforço permite:

Aprendizado Contínuo
    Adapta-se a novas informações: O agente pode aprender continuamente com novas situações e ajustar suas estratégias em tempo real.
    Melhora ao longo do tempo: Com a experiência acumulada, o desempenho do agente tende a se aprimorar, levando a decisões mais informadas.

### Objective:
- This project aims to create clusters defined according to the characteristics of credit card holders, grouping these holders and characterizing the clusters based on the occurrence of the variables used.

- Esse projeto tem como objetivo treinar um modelo, utilizando aprendizado por reforço, que nos orientará se no momento atual devemos comprar, vender ou manter os títulos (contratos) de soja futuros.

### Data Origin:
- Dataset: https://www.kaggle.com/datasets/choweric/cbot-soybeans/data

- The sample dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

- O Dataset de cotação do preço da soja apresenta cotações diárias com data do dia de cotação dos valores de títulos futuros da soja na bolsa de valores, com valores percorridos durante todo o dia.

- A seguir está o Dicionário de Dados para o conjunto de dados cotação de título de soja:

    Date: data da ocorrência da cotação
    Open: valor cotado na abertura dos trabalhos de negociação
    High: valor máximo atingido no período de negociação
    Low:  valor mínimo atingido no período de negociação
    Volume: nro de contratos negociados no período de negociação
    Open interest: fluxo de dinheiro para dentro ou para fora de um mercado de futuros