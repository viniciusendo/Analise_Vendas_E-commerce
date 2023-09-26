<h1 align="center">DNC - Desafio Preparação de Dataset para Modelagem de Dados</h1>

<p align="center">
 <a href="#entendimento-do-negócio">Entendimento do negócio</a> •
 <a href="#tratamento-dos-dados">Tratamento dos dados</a> • 
 <a href="#entendimento-dos-dados">Entendimento dos dados</a> • 
 <a href="#perguntas-de-negócio">Perguntas de negócios</a> •  
 <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a
</p>

## Entendimento do negócio
<p align="justify">
Esta é uma proposta de resolução para um desafio da Formação em Dados da Escola DNC. Trata-se da análise das vendas e do levantamento de indicadores de recência, frequência e ticket médio (RFM) de uma empresa de e-commerce, através da aplicação dos conceitos e técnicas de data cleaning e data wrangling para estruturação de uma base de dados para modelagem. 

<p align="justify">
A empresa possuía uma base de dados contendo informações sobre os códigos de identificação do cliente, fatura e estoque do produto, descrição, quantidade e preço unitário do produto e data do faturamento. 

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
A análise gráfica de vendas mostrou os 10 países com maior valor em vendas, os 10 produtos mais vendidos e a evolução anual das vendas. Dela, observa-se que o Reino Unido é o maior responsável pelo total vendido e que existe um aumento considerável no volume de vendas na segunda metade do ano, começando a partir de setembro. 

<p align="justify">
A criação dos indicadores de RFM foi acompanhada da análise univariada de cada um dos indicadores, além da utilização de um boxplot para verificar a distribuição dos dados, que se mostraram dispersos, gerando um conjunto de dados pouco homegêneo. 

## Tecnologias utilizadas
- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
