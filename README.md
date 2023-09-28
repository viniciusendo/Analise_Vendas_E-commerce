<h1 align="center">Análise de Vendas de E-Commerce</h1>

<p align="center">
 <a href="#entendimento-do-negócio">Entendimento do negócio</a> •
 <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a> •
 <a href="#tratamento-dos-dados">Tratamento dos dados</a> • 
 <a href="#entendimento-dos-dados">Entendimento dos dados</a> • 
 <a href="#perguntas-de-negócio">Perguntas de negócios</a
</p>

## Entendimento do negócio
<p align="justify">
Esta é uma proposta de resolução para um desafio da Formação em Dados da Escola DNC. Trata-se da análise das vendas e do levantamento de indicadores de recência, frequência e ticket médio (RFM) de uma empresa de e-commerce, através da aplicação dos conceitos e técnicas de data cleaning e data wrangling para estruturação de uma base de dados para modelagem. 

<p align="justify">
A empresa possuía uma base de dados contendo informações sobre os códigos de identificação do cliente, fatura e estoque do produto, descrição, quantidade e preço unitário do produto e data do faturamento. 

## Tecnologias utilizadas
- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Tratamento dos dados
<p align="justify">
Para utilizarmos as informações de maneira ideal, foi necessário fazer a manipulação da base de dados. Destaca-se:
  
- Remoção das linhas com valores nulos
- Remoção das linhas duplicadas, mantendo a primeira linha
- Remoção das linhas com valores incorretos de quantidade ou preço unitário do produto
- Correção dos tipos de dados
- Remoção de outliers extremos
- Criação de colunas e variáveis com dados de interesse

## Entendimento dos dados
<p align="justify">
Foi feita a análise univariada para observar a distribuição de variáveis numéricas (média, mínimo, máximo, desvio padrão) afim de procurar por padrões ou tendências relevantes para o negócio.
  
## Perguntas de negócio
<p align="justify">
A análise dos 10 países com maior valor em vendas mostra que o Reino Unido é o maior responsável pelo total vendido com uma larga vantagem para o segundo colocado, a Holanda. Essa informação nos permite localizar onde está a maior parte dos consumidores, ajudando a definir estratégias de marketing para focar neste público-alvo.

<p align="center">
    <img width="700" height="400" src="https://github.com/viniciusendo/Analise_Vendas_E-commerce/assets/134152277/a4b71e7b-86d8-4b1e-b9de-d1c0de8d4d35">
</p>

<p align="justify">
A análise dos 10 produtos mais vendidos nos permite identificar os produtos mais populares do catálogo, ajudando a definir estratégias de venda, como o uso de recomendações conjuntas com estes produtos.

<p align="center">
    <img width="700" height="400" src="https://github.com/viniciusendo/Analise_Vendas_E-commerce/assets/134152277/214cac86-8b50-4755-8780-e31f953af072">
</p>

A análise da evolução anual das vendas mostra que existe um aumento considerável no volume de vendas na segunda metade do ano, começando a partir de setembro. Essa informações nos ajuda a entender a sazonalidade das vendas, permitindo focar em ações de marketing em determinados períodos e auxiliando a fazer previsões de vendas. 

<p align="center">
    <img width="700" height="400" src="https://github.com/viniciusendo/Analise_Vendas_E-commerce/assets/134152277/2d7a00b6-f9c2-43cc-ab38-4a627a535d54">
</p>

<p align="justify">
A criação dos indicadores de RFM foi acompanhada da análise univariada de cada um dos indicadores, além da utilização de um boxplot para verificar a distribuição dos dados, que se mostraram dispersos, gerando um conjunto de dados pouco homegêneo. A informação do RFM nos ajuda a entender o perfil de cada cliente, possibilitando, por exemplo, classificá-los de acordo com seu padrão de compra e direcionando campanhas específicas para cada um deles.

<div align="center">
 
|  | Média | Desvio Padrão | Mínimo | Máximo |
| ----------- | :-----------: | :-----------: | :-----------: | :-----------: |
| **Recência** | 91.52 | 99.96 | 0.00 | 373.00 |
| **Frequência**| 4.27 | 7.69 | 1.00 | 209.00 |
| **Ticket Médio** | 380.49 | 497.43| 2.90 | 1484.77 |

</div>




