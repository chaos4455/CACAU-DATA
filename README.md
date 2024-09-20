# 📊 Análise e Predição de Vendas - Rede de Franquias Cacau Show 🍫

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Faker](https://img.shields.io/badge/Faker-DF3434?logo=faker&logoColor=white)](https://faker.readthedocs.io/)
[![Plotly](https://img.shields.io/badge/Plotly-FF6600?logo=plotly&logoColor=white)](https://plotly.com/)
[![Data Analysis](https://img.shields.io/badge/Data_Analysis-FF6347?style=flat&logo=data&logoColor=white)](https://en.wikipedia.org/wiki/Data_analysis)
[![Machine Learning](https://img.shields.io/badge/Machine_Learning-32CD32?style=flat&logo=machinelearning&logoColor=white)](https://en.wikipedia.org/wiki/Machine_learning)
[![License MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/seuusuario/seurepositorio?style=social)](https://github.com/seuusuario/seurepositorio/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/seuusuario/seurepositorio?style=social)](https://github.com/seuusuario/seurepositorio/network/members)

---

## 🌟 Sobre o Projeto

Bem-vindo ao repositório **Análise e Predição de Vendas** para a rede de franquias **Cacau Show**! Este projeto é uma prova de conceito (**POC**) que demonstra como a análise de dados e técnicas de predição podem gerar insights valiosos para o negócio, utilizando ferramentas poderosas como **Pandas**, **Faker** e **Plotly**.

> 🎯 **Objetivo**: Fornecer uma visão detalhada das vendas, identificar padrões e prever tendências futuras para auxiliar na tomada de decisões estratégicas.

---

## 📚 Índice

- [🌐 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [📈 Análise de Dados](#-análise-de-dados)
  - [🔹 Comparação de Vendas Dumbbell](#-comparação-de-vendas-dumbbell)
  - [📅 Cronograma de Vendas Gantt](#-cronograma-de-vendas-gantt)
  - [🎯 Meta de Receita Anual Bullet](#-meta-de-receita-anual-bullet)
  - [📉 Crescimento de Receita Waterfall](#-crescimento-de-receita-waterfall)
  - [🔥 Correlação de Métricas Heatmap](#-correlação-de-métricas-heatmap)
  - [🗺️ Receita por Cidade Treemap](#-receita-por-cidade-treemap)
  - [🔍 Matriz de Dispersão de Métricas](#-matriz-de-dispersão-de-métricas)
  - [⚖️ Pareto de Receita por Cidade](#-pareto-de-receita-por-cidade)
  - [📈 Receita Acumulada por Cidade](#-receita-acumulada-por-cidade)
  - [🍕 Percentual de Clientes por Cidade](#-percentual-de-clientes-por-cidade)
  - [🌍 Densidade de População vs Receita](#-densidade-de-população-vs-receita)
  - [📊 Vendas per Capita por Cidade](#-vendas-per-capita-por-cidade)
  - [🔺 Ticket Médio por Cidade](#-ticket-médio-por-cidade)
  - [📉 KDE do IDH vs Receita Total](#-kde-do-idh-vs-receita-total)
  - [📦 Receita por Funcionário Boxplot](#-receita-por-funcionário-boxplot)
  - [📈 Crescimento de Vendas por Cidade](#-crescimento-de-vendas-por-cidade)
  - [📉 Dispersão de Receita por Cliente](#-dispersão-de-receita-por-cliente)
  - [📊 Receita Crescimento Empilhada](#-receita-crescimento-empilhada)
- [🔮 Predição de Vendas](#-predição-de-vendas)
- [💡 Valor para o Negócio](#-valor-para-o-negócio)
- [📂 Estrutura do Repositório](#-estrutura-do-repositório)
- [🚀 Como Usar](#-como-usar)
- [🤝 Contribuições](#-contribuições)
- [📜 Licença](#-licença)
- [📞 Contato](#-contato)

---

## 🌐 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Faker](https://img.shields.io/badge/Faker-DF3434?logo=faker&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-FF6600?logo=plotly&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-FFDB00?logo=jupyter&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)

Este projeto utiliza as seguintes tecnologias e bibliotecas:

- **Python**: Linguagem de programação principal.
- **Pandas**: Manipulação e análise de dados.
- **Faker**: Geração de dados falsos para simulação.
- **Plotly**: Criação de gráficos interativos.
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo.
- 
![barras_empilhadas_receita_crescimento (1)](https://github.com/user-attachments/assets/008a77ba-a2bd-45e1-9481-111a50a2aac3)
![dispersao_receita_clientes (1)](https://github.com/user-attachments/assets/230f2e98-86ff-4077-a932-e34bdface77f)
![linhas_crescimento_vendas_cidade (1)](https://github.com/user-attachments/assets/3df282b8-3f03-4e7d-95fd-db3888036ae3)
![boxplot_receita_por_funcionario_cidade (1)](https://github.com/user-attachments/assets/63acebc6-f4b0-47a0-94fd-b5bf60817845)
![kde_idh_receita_total (1)](https://github.com/user-attachments/assets/cd440410-446a-4484-b420-0123c6e41972)
![barras_ticket_medio_cidade (1)](https://github.com/user-attachments/assets/26757f44-b5d7-4af2-b3e7-37bf3db845b1)
![linhas_vendas_per_capita_cidade (1)](https://github.com/user-attachments/assets/97d909b4-76f0-4a5c-bb0c-35110be9e4ff)
![densidade_distribuicao_populacao_receita (1)](https://github.com/user-attachments/assets/8b95871a-3e9e-48ff-9901-556ac58b68cd)
![barras_empilhadas_receita_crescimento](https://github.com/user-attachments/assets/0a33a942-41ac-4b95-aebe-d26e4c3bfcc0)
![dispersao_receita_clientes](https://github.com/user-attachments/assets/4002db85-d757-4013-8ded-7cd7836a923b)
![linhas_crescimento_vendas_cidade](https://github.com/user-attachments/assets/2d0f636b-81cb-4efe-afb6-0bf7f5973662)
![boxplot_receita_por_funcionario_cidade](https://github.com/user-attachments/assets/78a0c9b2-85f0-4ed5-9589-9469c900cb16)
![kde_idh_receita_total](https://github.com/user-attachments/assets/8686a2d6-524a-4e53-aa56-c29740799b7f)
![barras_ticket_medio_cidade](https://github.com/user-attachments/assets/6060e023-c338-428d-a9a9-6b8a26e36f3e)
![linhas_vendas_per_capita_cidade](https://github.com/user-attachments/assets/8c3f73cb-230f-48df-b0cc-ad24944d861e)
![densidade_distribuicao_populacao_receita](https://github.com/user-attachments/assets/31ac41c7-a00b-420b-b0d9-60ecd4641662)
![pizza_percentual_clientes_cidade](https://github.com/user-attachments/assets/b24ca2c3-bee2-4bd8-af40-775663ad8f09)
![area_receita_total_acumulada_cidade](https://github.com/user-attachments/assets/71ef0b4c-0903-4b0f-a5e6-414b0bb26140)
![pareto_receita_por_cidade](https://github.com/user-attachments/assets/331a8044-3499-4a21-98f8-fd566639447b)
![scatter_matrix_metricas_vendas](https://github.com/user-attachments/assets/384cba7d-5189-4633-b5b1-1f763fe95d0d)
![treemap_receita_cidade_crescimento](https://github.com/user-attachments/assets/0a1f83a4-f994-4922-a16d-70e9a96c128c)
![heatmap_correlacao_metricas](https://github.com/user-attachments/assets/7d47d810-0cad-41e3-b6b3-9ad14fab079e)
![waterfall_crescimento_receita](https://github.com/user-attachments/assets/d4e0061a-4730-4a8d-b6cc-66fff0cb3a68)
![bullet_meta_receita_anual](https://github.com/user-attachments/assets/38705365-cd9b-4412-a27a-05209328e157)
![gantt_cronograma_vendas](https://github.com/user-attachments/assets/ee710836-3a9d-467a-b820-6af0108fb4a0)
![dumbbell_comparacao_vendas](https://github.com/user-attachments/assets/9e56dc38-82ee-4f95-95a6-588ccdfb9f56)

---

## 📈 Análise de Dados

Nesta seção, apresentamos uma série de gráficos que ilustram diferentes aspectos das vendas da rede de franquias **Cacau Show**. Cada gráfico foi criado utilizando **Plotly** para fornecer visualizações interativas e informativas.



### 🔹 Comparação de Vendas Dumbbell

![Comparação de Vendas Dumbbell](./images/dumbbell_comparacao_vendas.png)

> **Descrição**: Este gráfico dumbbell compara as vendas de diferentes franquias ao longo de dois períodos distintos.
>
> **Valor para o Negócio**: Permite identificar quais franquias estão melhorando ou deteriorando seu desempenho, facilitando a tomada de decisões estratégicas.

### 📅 Cronograma de Vendas Gantt

![Cronograma de Vendas Gantt](./images/gantt_cronograma_vendas.png)

> **Descrição**: O gráfico de Gantt apresenta o cronograma de vendas projetadas versus realizadas.
>
> **Valor para o Negócio**: Auxilia no planejamento e no acompanhamento das metas de vendas, garantindo que as franquias estejam alinhadas com os objetivos estabelecidos.

### 🎯 Meta de Receita Anual Bullet

![Meta de Receita Anual Bullet](./images/bullet_meta_receita_anual.png)

> **Descrição**: Este gráfico bullet mostra o progresso em relação à meta de receita anual.
>
> **Valor para o Negócio**: Facilita o monitoramento do desempenho financeiro, permitindo ajustes rápidos para alcançar as metas estabelecidas.

### 📉 Crescimento de Receita Waterfall

![Crescimento de Receita Waterfall](./images/waterfall_crescimento_receita.png)

> **Descrição**: O gráfico waterfall detalha as contribuições positivas e negativas para o crescimento da receita.
>
> **Valor para o Negócio**: Ajuda a identificar os principais fatores que impactam a receita, permitindo ações direcionadas para maximizar o crescimento.

### 🔥 Correlação de Métricas Heatmap

![Correlação de Métricas Heatmap](./images/heatmap_correlacao_metricas.png)

> **Descrição**: Heatmap de correlação entre diferentes métricas de vendas.
>
> **Valor para o Negócio**: Identifica relações entre variáveis, auxiliando na compreensão dos fatores que influenciam as vendas.

### 🗺️ Receita por Cidade Treemap

![Receita por Cidade Treemap](./images/treemap_receita_cidade_crescimento.png)

> **Descrição**: Treemap que representa a receita gerada por cada cidade, destacando o crescimento relativo.
>
> **Valor para o Negócio**: Visualiza a distribuição geográfica das vendas, facilitando a identificação de áreas de alto desempenho.

### 🔍 Matriz de Dispersão de Métricas

![Matriz de Dispersão de Métricas](./images/scatter_matrix_metricas_vendas.png)

> **Descrição**: Matriz de dispersão que explora a relação entre diferentes métricas de vendas.
>
> **Valor para o Negócio**: Permite uma análise multifacetada das métricas, revelando padrões e tendências ocultas.

### ⚖️ Pareto de Receita por Cidade

![Pareto de Receita por Cidade](./images/pareto_receita_por_cidade.png)

> **Descrição**: Gráfico de Pareto que destaca as cidades que mais contribuem para a receita total.
>
> **Valor para o Negócio**: Ajuda a focar nos mercados mais lucrativos, otimizando esforços de marketing e vendas.

### 📈 Receita Acumulada por Cidade

![Receita Acumulada por Cidade](./images/area_receita_total_acumulada_cidade.png)

> **Descrição**: Gráfico de área que mostra a receita total acumulada por cidade ao longo do tempo.
>
> **Valor para o Negócio**: Fornece uma visão clara do crescimento ao longo do tempo, facilitando a análise de tendências.

### 🍕 Percentual de Clientes por Cidade

![Percentual de Clientes por Cidade](./images/pizza_percentual_clientes_cidade.png)

> **Descrição**: Gráfico de pizza que ilustra a distribuição percentual de clientes por cidade.
>
> **Valor para o Negócio**: Identifica onde a base de clientes está mais concentrada, auxiliando na segmentação de mercado.

### 🌍 Densidade de População vs Receita

![Densidade de População vs Receita](./images/densidade_distribuicao_populacao_receita.png)

> **Descrição**: Gráfico de densidade que correlaciona a população de uma cidade com a receita gerada.
>
> **Valor para o Negócio**: Avalia a eficácia das vendas em relação à população, otimizando a alocação de recursos.

### 📊 Vendas per Capita por Cidade

![Vendas per Capita por Cidade](./images/linhas_vendas_per_capita_cidade.png)

> **Descrição**: Gráfico de linhas que mostra as vendas per capita em cada cidade.
>
> **Valor para o Negócio**: Mede a eficiência das vendas em relação ao tamanho da população, identificando oportunidades de crescimento.

### 🔺 Ticket Médio por Cidade

![Ticket Médio por Cidade](./images/barras_ticket_medio_cidade.png)

> **Descrição**: Gráfico de barras que compara o ticket médio das vendas por cidade.
>
> **Valor para o Negócio**: Ajuda a entender o comportamento de compra dos clientes, ajustando estratégias de precificação.

### 📉 KDE do IDH vs Receita Total

![KDE do IDH vs Receita Total](./images/kde_idh_receita_total.png)

> **Descrição**: Gráfico KDE (Kernel Density Estimate) que correlaciona o IDH das cidades com a receita total.
>
> **Valor para o Negócio**: Analisa como o desenvolvimento socioeconômico impacta as vendas, direcionando ações para diferentes segmentos.

### 📦 Receita por Funcionário Boxplot

![Receita por Funcionário Boxplot](./images/boxplot_receita_por_funcionario_cidade.png)

> **Descrição**: Boxplot que mostra a distribuição da receita por funcionário em cada cidade.
>
> **Valor para o Negócio**: Avalia a produtividade dos funcionários, identificando necessidades de treinamento ou reestruturação.

### 📈 Crescimento de Vendas por Cidade

![Crescimento de Vendas por Cidade](./images/linhas_crescimento_vendas_cidade.png)

> **Descrição**: Gráfico de linhas que acompanha o crescimento das vendas em diferentes cidades.
>
> **Valor para o Negócio**: Monitora o desempenho ao longo do tempo, facilitando ajustes nas estratégias de vendas.

### 📉 Dispersão de Receita por Cliente

![Dispersão de Receita por Cliente](./images/dispersao_receita_clientes.png)

> **Descrição**: Gráfico de dispersão que correlaciona a receita gerada por cliente.
>
> **Valor para o Negócio**: Identifica os clientes mais valiosos, permitindo ações de fidelização direcionadas.

### 📊 Receita Crescimento Empilhada

![Receita Crescimento Empilhada](./images/barras_empilhadas_receita_crescimento.png)

> **Descrição**: Gráfico de barras empilhadas que detalha o crescimento da receita por diferentes categorias.
>
> **Valor para o Negócio**: Fornece uma visão segmentada do crescimento, facilitando a identificação de áreas promissoras.

---

## 🔮 Predição de Vendas

Utilizando técnicas de **Machine Learning**, este projeto realiza a predição de vendas futuras com base nos dados históricos disponíveis. O modelo desenvolvido permite prever tendências e ajustar estratégias para maximizar os resultados.

> **Ferramentas Utilizadas**:
> - **Scikit-learn**: Para construção e treinamento de modelos de predição.
> - **NumPy**: Manipulação eficiente de arrays numéricos.
> - **Matplotlib**: Visualização de resultados de predição.

---

## 💡 Valor para o Negócio

Através desta análise detalhada e predições precisas, a rede de franquias **Cacau Show** pode:

- **Identificar Tendências**: Compreender padrões de vendas e antecipar demandas futuras.
- **Otimizar Recursos**: Alocar de forma eficiente os recursos humanos e financeiros.
- **Melhorar Estratégias de Marketing**: Direcionar campanhas para as áreas mais lucrativas.
- **Aumentar a Satisfação do Cliente**: Ajustar ofertas e serviços com base no comportamento de compra.
- **Maximizar Lucros**: Implementar ações baseadas em dados para aumentar a receita total.

---

