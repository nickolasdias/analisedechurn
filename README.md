# Análise de Churn de uma Instituição Bancária

# 1.0 Contexto

## O que é taxa de churn ?

Churn é uma métrica que aponta o número de clientes que deixaram de fazer negócios com a empresa em um determinado período de tempo.

Churn, em tradução livre, significa rotatividade, movimento, e por isso, a taxa de churn rate também é chamada de “taxa de rotatividade” ou “taxa de cancelamento”. 

Por representar um indicador relativo à interrupção de um negócio, o churn rate está relacionado principalmente a produtos contínuos, como assinaturas, planos telefônicos e planos bancários.

## Como calcular a taxa de churn ?

O cálculo da taxa de churn rate é feito a partir da divisão entre os clientes que interromperam o serviço no fim do período pré-determinado pelo número de clientes no início desse mesmo período, multiplicada por 100, a fim de obtermos a taxa em formato de porcentagem.

De forma prática, seria algo assim: suponhamos que uma empresa tenha 1000 clientes no início de um mês. Ao fim desse mesmo mês — ou outro período de análise pré-determinado — , o número de clientes cai para 950.

Utilizando esses dados, o cálculo do seu churn rate seria: 

50 (número de clientes que interromperam o serviço) / 1000 (clientes no início do processo) x 100 = 5%

Assim, nesse exemplo, a taxa de churn rate é de 5%.  Ou seja, 5% dos clientes daquele mês deixaram de manter parceria com essa empresa.

## Por que clientes deixam uma empresa, afinal? 

Existem diversas razões que levam os clientes a deixarem uma marca. De acordo com uma pesquisa divulgada pelo portal e-commerce Brasil, 87% dos consumidores deixam de fazer negócios com uma empresa em razão de um atendimento ruim. Além disso, outras razões podem contribuir para o aumento das taxas de churn rate, tais como: 

- Mudança na estratégia da empresa
- Crise financeira
- Superação pela concorrência
- Mudança de equipe/gestão
- Falta de confiança na equipe de agentes ou no fornecedor
- Qualidade do produto não atende as expectativas
- Produto com experiência do usuário ruim
- Falência do cliente
- Incompatibilidade entre as funções oferecidas pelo serviço e as demandas da empresa.

## Quais os impactos de uma taxa de churn alta ?

Alguns dos impactos negativos de uma taxa churn rate elevada são: 

- Dificuldade de firmar parcerias e contratos de expansão do negócio
- Baixa escalabilidade do produto ou do serviço
- Imagem externa da empresa desgastada
- Colaboradores desmotivados.

# 2.0 Desafio


- O gênero dos clientes influenciam na taxa de churn?
- O tipo de cartão de cartão de crédito influencia na taxa de churn ?
- Qual faixa etária dos clientes está propensa a ter churn ?
- Qual faixa de renda dos clientes está propensa a ter churn ?
- O estado civil dos clientes influência na taxa de churn ?
- Qual nível educacional dos clientes influência na taxa de churn ?
- 

# 3.0 Solução

**Observação:** A análise de dados foi realizada no software **POWER BI**.

Para responder as questões do desafio, analisei os dados filtrando o número de dependentes que cada cliente tem nos seguintes dashboards.

<h3> Análise geral </h3>

![01](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/01.png)

**Observação:**

- A instituição bancária têm 10.130 clientes com uma taxa de Churn de 16,07%
- Clientes do gênero feminino tem uma taxa de churn um pouco maior do que clientes do gênero masculino.
- Clientes com cartão do tipo blue tem a maior taxa de churn.
- As faixa etárias de clientes 
- Clientes com faixa de renda de menos de 40000 tem uma maior taxa de churn (6,04%) do que as demais faixa de renda.
-   

![02](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/02.png)

<h3> Análise considerando Clientes com nenhum Dependente </h3>

![03](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/03.png)

![04](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/04.png)

<h3> Análise considerando Clientes com um Dependente </h3>

![05](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/05.png)

![06](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/06.png)

<h3> Análise considerando Clientes dois um Dependentes </h3>

![07](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/07.png)

![08](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/08.png)

<h3> Análise considerando Clientes com três Dependentes </h3>

![09](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/09.png)

![10](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/10.png)

<h3> Análise considerando Clientes com quatro Dependentes </h3>

![11](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/11.png)

![12](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/12.png)

<h3> Análise considerando Clientes com cinco Dependentes </h3>

![13](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/13.png)

![14](https://github.com/nickolasdias/analisedechurn/blob/main/dashboards/14.png)
