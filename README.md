# Insiders Customers



## Customer Clustering

![Customer](/customer_image.jpg)

## 1. Business Problem

<p> A empresa All in One Place é uma empresa Outlet Multimarcas, ou seja, ela comercializa produtos de segunda linha de várias marcas a um preço menor, através de um e-commerce.</p>

<p> Em pouco mais de 1 anos de operação, o time de marketing percebeu que alguns clientes da sua base, compram produtos mais caros, com alta frequência e acabam contribuindo com uma parcela significativa do faturamento da empresa. </p>

<p> Baseado nessa percepção, o time de marketing vai lançar um programa de fidelidade para os melhores clientes da base, chamado Insiders. </p>

## 2. Business Assumptions.

**Com base na análise dos dados tomamos as seguintes suposições de negócio:**

- Remoção de compra de itens com valores menores do que $ 0.04.
- Códigos de estoque como 'POST', 'D', 'DOT', 'M', 'S', 'AMAZONFEE', 'm', 'DCGSSBOY', 'DCGSSGIRL', 'PADS', 'B', 'CRUK' foram removidos pois não foi possível identificar sua finalidade.


## 3. Estratégia de Solução

***Minha estratégia para resolver esse desafio foi:***

**Step 01. Data Description:**  O objetivo é utilizar métricas estatísticas para identificar outliers no escopo do negócio.

**Step 02. Data Filtering:** Filtrar as linhas e selecionar as colunas que não contenham informações para modelagem ou não correspondam ao escopo do negócio.

**Step 03. Feature Engineering:** Derivar novos atributos com base nas variáveis originais para descrever melhor o fenômeno a ser modelado.

**Step 04. Exploratory Data Analysis:** Explorar os dados para encontrar insights e entender melhor o impacto das variáveis no aprendizado do modelo.

**Step 05. Feature Selection:** Seleção dos atributos mais significativos para treinar o modelo.

**Step 06. Data Preparation:** Preparar os dados para que os modelos de aprendizado de máquina possam aprender um comportamento específico.

**Step 07. Machine Learning Modelling:** Treinamento do modelo de aprendizado de máquina.

**Step 08. Cluster Analysis:** Análise de comportamento dos clusters formados

**Step 09. Exploratory Data Analysis:** Análise Exploratória dos clusters encontrados.

**Step 10. Deploy:** Deploy do modelo na AWS

## 5. Machine Learning Model Applied:

Os testes foram realizados usando os seguintes algoritmos:

-> KMeans

-> GMM

-> HC

## 6. Machine Learning Modelo Performance

**A métrica utilizada para avaliar a qualidade dos clusters foi a Silhouette Score**

| Modelo  |  2  | 3  |  4  |  5  | 6  |  7  |  8  | 9  |  10  |
| ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- |------------------- | ------------------- |
|  KMeans |  0.443215	 |  0.468555 |  	0.529569 | 0.541902	 |  0.584678 |  	0.634752 | 0.651534	 |  0.672910 |  	0.678708 | 0.669074	 |
|  GMM    |  0.393473	 |  0.462310 |  	0.532297 | 0.552666	 |  0.568974 |  	0.548120 | 0.642017	 |  0.661465 |  	0.667338 | 0.646291	 |
|  HC     |  0.443215	 |  0.469561 |  	0.529953 | 0.551710	 |  0.582836 |  	0.629056 | 0.645837	 |  0.667599 |  	0.671997 | 0.685611	 |


![Clusters](/clusters.jpg)

## 7. Business Results

## 8. Conclusions


## 9. Lessons Learned


## 10. Next Steps to Improve


