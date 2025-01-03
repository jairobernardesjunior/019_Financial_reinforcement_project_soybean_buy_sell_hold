## Projeto dólar compra venda hold

### Problem:
Grouping credit card holders is an essential practice for credit card companies. This strategy allows them to check which group, or cluster, the cardholder belongs to, and they may receive additional benefits when using the card, or be subject to certain restrictions depending on the group to which they belong.

O agrupamento de titulares de cartões de crédito é uma prática essencial para empresas administradoras de cartão de crédito. Essa estratégia traz a possibilidade de verificar em que grupo, cluster, o titular do cartão está inserido, podendo tanto receber algumas vantagens a mais no uso do cartão, como também sofrer alguma restrição conforme o grupo a que pertença.

### Motivation:
Credit Management
A well-structured grouping system helps to optimize the credit available to the holder, allowing them to extend their credit and buy more, while at the same time having their credit restricted according to the group they may belong to.

Gestão do Crédito
Um sistema de agrupamento bem estruturado ajuda a otimizar o crédito disponível para o titular, permitindo estender seu crédito, podendo comprar mais, ao mesmo tempo em que pode ter seu crédito restrito conforme o grupo que possa estar pertencente.

### Solution:
Using credit card usage data, machine learning algorithms will be used to define credit card holder classification clusters, grouping those that are similar into groups that reflect the dynamics of card usage that will reveal the level of commitment both in consumption and in the coverage of this consumption, revealing their responsibility regarding the most appropriate use in the balance between credit and debit.

Através de dados de utilização do cartão de crédito, será utilizado algoritmos de machine learning para definir clusters de classificação do titular do cartão de crédito, agrupando os que são semelhantes em grupos que refletem a dinâmica do uso do cartão que revelará o nível de compromisso tanto no consumo quanto na cobertura desse consumo, revelando sua responsabilidade frente ao uso mais adequado no equilíbrio entre crédito e débito.

### Objective:
- This project aims to create clusters defined according to the characteristics of credit card holders, grouping these holders and characterizing the clusters based on the occurrence of the variables used.

- Esse projeto tem como objetivo treinar um modelo, utilizando aprendizado por reforço, que nos orientará se no momento atual devemos comprar, vender ou manter o Dólar Americano.

### Data Origin:
- Dataset: https://www.kaggle.com/datasets/markfinn1/dolar-atualizado-dirio-bacen

- The sample dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

- O Dataset de amostra resume o comportamento de uso de cerca de 9000 titulares de cartão de crédito ativos durante os últimos 6 meses. O arquivo está em um nível de cliente com 18 variáveis ​​comportamentais.

- A seguir está o Dicionário de Dados para o conjunto de dados de Cartão de Crédito:-

    CUST_ID : Identificação do titular do cartão de crédito (categórico)

    BALANCE : Valor do saldo restante na conta para fazer compras

    BALANCE_FREQUENCY : Com que frequência o saldo é atualizado, pontuação entre 0 e 1 (1 = atualizado com frequência, 0 = não atualizado com frequência)

    PURCHASES : Quantidade de compras feitas na conta

    ONEOFF_PURCHASES : Valor máximo de compra feita de uma só vez

    INSTALLMENTS_PURCHASES : Valor da compra feita em parcelas

    CASH_ADVANCE : Dinheiro adiantado dado pelo usuário

    PURCHASES_FREQUENCY : Com que frequência as compras estão sendo feitas, pontuação entre 0 e 1 (1 = compradas com frequência, 0 = não compradas com frequência)

    ONEOFFPURCHASESFREQUENCY : Com que frequência as compras estão acontecendo de uma só vez (1 = compradas com frequência, 0 = não compradas com frequência)

    PURCHASESINSTALLMENTSFREQUENCY : Com que frequência as compras em parcelas estão sendo feitas (1 = feitas com frequência, 0 = não feito com frequência)

    CASHADVANCEFREQUENCY : Com que frequência o dinheiro adiantado é pago

    CASHADVANCETRX : Número de transações feitas com "Dinheiro adiantado"

    PURCHASES_TRX : Número de transações de compra feitas

    CREDIT_LIMIT : Limite do cartão de crédito para o usuário

    PAYMENTS : Valor do pagamento feito pelo usuário

    MINIMUM_PAYMENTS : Valor mínimo de pagamentos feitos pelo usuário

    PRCFULLPAYMENT : Porcentagem do pagamento integral pago pelo usuário

    TENURE : Prazo do serviço de cartão de crédito para o usuário