# 📊 Análise e Predição de Vendas - Rede de Franquias Cacau Show 🍫

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Faker](https://img.shields.io/badge/Faker-DF3434?logo=faker&logoColor=white)](https://faker.readthedocs.io/)
[![Plotly](https://img.shields.io/badge/Plotly-FF6600?logo=plotly&logoColor=white)](https://plotly.com/)
[![Data Analysis](https://img.shields.io/badge/Data_Analysis-FF6347?style=flat&logo=data&logoColor=white)](https://en.wikipedia.org/wiki/Data_analysis)
[![Machine Learning](https://img.shields.io/badge/Machine_Learning-32CD32?style=flat&logo=machinelearning&logoColor=white)](https://en.wikipedia.org/wiki/Machine_learning)
[![License MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

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

# 🛠️ **Data Analysis & Prediction Showcase - Extended Heatmaps Series** 🔍

![](https://img.shields.io/badge/Data_Science-Extended_Analysis-green?style=for-the-badge&logo=pandas&logoColor=white) 
![](https://img.shields.io/badge/Visualizations-Heatmaps_&_Comparisons-purple?style=for-the-badge&logo=plotly&logoColor=white)

Este segmento do repositório foca em novas análises visuais para a rede de franquias da Cacau Show, expandindo o showcase de gráficos para incluir **heatmaps** que analisam a relação entre diferentes variáveis, como receita, ticket médio, IDH e produtividade.

> **Heatmaps são ferramentas poderosas** para visualizar a **correlação** e a **distribuição** de métricas em larga escala, especialmente úteis para identificar padrões em dados de vendas complexos e determinar onde estão as melhores oportunidades de crescimento.

---

## 🌐 **Heatmap Comparisons - Detailed Analysis**

📊 **1. Heatmap - IDH vs. Ticket Médio Ponderado**
- **Arquivo**: `heatmap_idh_ticket_medio_ponderado_334af40bfaf6332be964a2a3f1e162b7.png`
- **Descrição**: Este gráfico visualiza a correlação entre o Índice de Desenvolvimento Humano (IDH) das cidades e o ticket médio ponderado. 
    - 🟢 **Valor para o negócio**: Identifica **cidades com alto IDH** e baixo ticket médio, sugerindo oportunidades de **up-sell** e campanhas promocionais específicas.

📊 **2. Heatmap - Ticket Médio Ponderado vs. Produtividade**
- **Arquivo**: `heatmap_ticket_medio_ponderado_produtividade_409c1fd2852385ca7d199200297d0396.png`
- **Descrição**: Relação entre o ticket médio ponderado e a produtividade por funcionário.
    - 🟢 **Valor para o negócio**: Ajuda a identificar **filiais mais produtivas**, permitindo insights sobre **melhorias de treinamento** e **iniciativas de performance**.

📊 **3. Heatmap - Crescimento de Vendas vs. População**
- **Arquivo**: `heatmap_crescimento_vendas_populacao_ee4dca36cf109699269c1555c3729c58.png`
- **Descrição**: Correlação entre o crescimento de vendas e a população das cidades.
    - 🟢 **Valor para o negócio**: Identifica regiões **subaproveitadas** com alta densidade populacional e **baixas vendas**, sugerindo **estratégias locais** de expansão de mercado.

📊 **4. Heatmap - Receita Total vs. Receita per Capita**
- **Arquivo**: `heatmap_receita_total_per_capita_8f905599aea42f791eeafb5194581f0d.png`
- **Descrição**: Receita total de cada cidade em relação à receita per capita.
    - 🟢 **Valor para o negócio**: Permite identificar cidades que possuem uma **alta concentração de receita** em poucos clientes, sinalizando uma possível necessidade de **diversificar a base de consumidores**.

---

## 🔍 **Additional Heatmaps with Tailored Palettes**

🎨 Para esta série de heatmaps, utilizamos uma **nova paleta de cores** que destaca as diferenças com ainda mais clareza e impacto visual.

📊 **5. Heatmap - Receita per Capita vs. Funcionários**
- **Arquivo**: `heatmap_receita_per_capita_funcionarios_87424907d6e81c01f321b4c563ee1808.png`
- **Descrição**: Relação entre receita per capita e o número de funcionários por cidade.
    - 🟢 **Valor para o negócio**: Avalia a **eficiência operacional** e as necessidades de **otimização de equipe**.

📊 **6. Heatmap - Ticket Médio vs. Receita Total**
- **Arquivo**: `heatmap_ticket_receita_funcionarios_dd8f440ffc4cf6e0da6ff5691feb1b78.png`
- **Descrição**: Comparação entre o ticket médio de vendas e a receita total gerada por funcionários.
    - 🟢 **Valor para o negócio**: Revela **quais unidades** possuem **funcionários mais rentáveis**, ajudando no planejamento de **bônus e incentivos**.

📊 **7. Heatmap - Produtividade dos Funcionários vs. Crescimento de Vendas**
- **Arquivo**: `heatmap_produtividade_funcionarios_crescimento_636cbdca7fc3237200c4ca535c041db1.png`
- **Descrição**: A comparação entre a produtividade e o crescimento de vendas.
    - 🟢 **Valor para o negócio**: Fornece dados para ajustar as **estratégias de vendas** e **alocar melhor os recursos**.

📊 **8. Heatmap - Receita vs. IDH**
- **Arquivo**: `heatmap_receita_idh_ad75b622eb435f062e98440c49c942c5.png`
- **Descrição**: A receita gerada comparada ao IDH das cidades.
    - 🟢 **Valor para o negócio**: Dá insights sobre como o **nível de desenvolvimento** afeta o **comportamento de compra**.

---

## 🎨 **Gráficos Adicionais com Novas Abordagens Visuais**

Com o intuito de aprimorar a análise, gráficos adicionais com um **novo design e paleta** foram incluídos:

📈 **9. Receita por Funcionário vs. Crescimento das Vendas**
- **Arquivo**: `grafico_receita_vs_funcionarios_455bee1bad62d6bebf048e522155fe14.png`
- **Descrição**: Este gráfico mostra a relação entre a receita gerada por funcionário e o crescimento das vendas ao longo do tempo.
    - 🟢 **Valor para o negócio**: **Mede a eficiência de cada funcionário** em gerar receita em ambientes com diferentes ritmos de crescimento.

📈 **10. Receita Total por Cidade**
- **Arquivo**: `grafico_receita_total_cidade_3617552818fa6dac8bca536c45fc3929.png`
- **Descrição**: Compara a receita total das principais cidades.
    - 🟢 **Valor para o negócio**: Permite **focar em cidades-chave** para aumentar a receita total, ajustando as estratégias locais.

---

### 🚀 **Por que Heatmaps e Gráficos Adicionais São Importantes?**

![](https://img.shields.io/badge/Business_Value-Strategic_Insights-blue?style=for-the-badge&logo=chart-line&logoColor=white)
![](https://img.shields.io/badge/Visualization-Advanced_Analytics-red?style=for-the-badge&logo=insights&logoColor=white)

- **Heatmaps** fornecem uma **visualização instantânea** das correlações e distribuições de métricas, permitindo que **gestores de negócios identifiquem rapidamente tendências** e **pontos críticos** de crescimento.
- **Gráficos detalhados** ajudam a entender a **eficiência operacional**, **produtividade de funcionários** e o **impacto das estratégias regionais** no desempenho geral da rede.

Estes dados visualizados fornecem a base para **decisões estratégicas** mais precisas, levando a **melhorias nas operações**, **aumento de receita** e **expansão das oportunidades de crescimento**.
![histograma_ticket_medio_7fc8f65cc290111a5230bc2993d077b4](https://github.com/user-attachments/assets/a84b776d-46e0-4b21-b4c6-d1143001a033)
![boxplot_receita_total_9f2fe0cef0d4f64b579bd97168e19993](https://github.com/user-attachments/assets/f9ec3816-0726-4d8a-87a3-fe73752255d1)
![treemap_receita_cidade_a25180bea0d166b2d9664ebb7a8ba62b](https://github.com/user-attachments/assets/26b00dba-0cec-4aa6-aac4-2a86ab9cadbb)
![heatmap_receita_ticket_medio_0680776da3801ad006bccab66c58d4c5](https://github.com/user-attachments/assets/4c1f007b-015e-4779-aa4e-8c982cf5cd9c)
![heatmap_ticket_clientes_69d0a02fb0d29049711e6c03af342874](https://github.com/user-attachments/assets/2045368f-021e-462d-b187-1b8c8ef66100)
![heatmap_receita_funcionarios_80d4b20613fa6a5934c4d8dab60df870](https://github.com/user-attachments/assets/7d3f4699-90d6-4794-94ea-1d68f916ee28)
![heatmap_receita_crescimento_7fc264c67b0b5f122abe43f15d4cc0d9](https://github.com/user-attachments/assets/62da48d5-1109-4594-9723-56d517b4a826)
![heatmap_produtividade_idh_1547d297d1cb6a4b31d231cb780810b5](https://github.com/user-attachments/assets/8fea3ece-c498-4488-ac69-988aae4618b7)
![heatmap_receita_per_capita_populacao_fac91369c2296a60efdf0a89583098d3](https://github.com/user-attachments/assets/84d789f4-65ce-40e0-a829-a830bc864ff0)
![heatmap_ticket_medio_ponderado_idh_456842a1e9cd746d9a72471b75bf10f1](https://github.com/user-attachments/assets/3504600b-d8fe-4c4f-98b9-9e1b1652afe3)
![heatmap_receita_produtividade_3f8cfca9ed058b4bfe17d2874e22aece](https://github.com/user-attachments/assets/1f34620a-ab4c-4251-9510-38444f17c5a6)
![heatmap_crescimento_vendas_ticket_medio_908663d60ff80fe468f11fbb57f8aa6f](https://github.com/user-attachments/assets/1f043358-92eb-40ef-856f-6115478f0ce7)
![heatmap_receita_crescimento_vendas_d0dab7740cbbf4b61bfb7d170a1ec117](https://github.com/user-attachments/assets/8291c753-ac2e-4381-9559-31cc7601732f)
![heatmap_receita_idh_ad75b622eb435f062e98440c49c942c5](https://github.com/user-attachments/assets/0727b277-97a8-4bef-a283-3ffec3cb63f1)
![heatmap_receita_funcionarios_populacao_b6b242ecd691e3c7ddc7106abebab65d](https://github.com/user-attachments/assets/065f29e2-2ace-4ce8-92f4-527d39f8fcc2)
![heatmap_receita_per_capita_ticket_3d8a42eaee20e82c5cebf521c8b6f931](https://github.com/user-attachments/assets/41c02e81-d805-4bb0-8d91-cc25f8bd2642)
![heatmap_produtividade_funcionarios_crescimento_636cbdca7fc3237200c4ca535c041db1](https://github.com/user-attachments/assets/4589a1b0-4fc9-401b-a3f4-70b2299ac8c2)
![heatmap_clientes_crescimento_612d15fa3e4aadf96ed3ba8f5ff5352c](https://github.com/user-attachments/assets/725b9d18-5b76-4d5e-b53e-4e1faeab47a9)
![heatmap_ticket_receita_funcionarios_dd8f440ffc4cf6e0da6ff5691feb1b78](https://github.com/user-attachments/assets/bdf4b3f5-c614-4872-ac43-ec3019f868cf)
![heatmap_receita_per_capita_funcionarios_87424907d6e81c01f321b4c563ee1808](https://github.com/user-attachments/assets/af6e0abd-7d22-46e8-8676-b2af099bf779)
![heatmap_idh_clientes_ef5fefce18fec24491326b7895b9e397](https://github.com/user-attachments/assets/13dbec9a-a2c8-4325-a2a8-ac584b102b1e)
![heatmap_receita_total_per_capita_8f905599aea42f791eeafb5194581f0d](https://github.com/user-attachments/assets/d7d4239e-e118-4487-bb3b-403665bacec9)
![heatmap_crescimento_vendas_populacao_ee4dca36cf109699269c1555c3729c58](https://github.com/user-attachments/assets/65cf938e-286d-42de-a863-d98567925114)
![heatmap_ticket_medio_ponderado_produtividade_409c1fd2852385ca7d199200297d0396](https://github.com/user-attachments/assets/56bd8ee7-e970-47cf-b7fa-a8dd885ad98e)
![heatmap_idh_ticket_medio_ponderado_334af40bfaf6332be964a2a3f1e162b7](https://github.com/user-attachments/assets/6193d83f-72f5-4818-97e2-a2a8e5ea161d)

---

Fique à vontade para explorar os gráficos e conferir a **extensão das análises** que foram desenvolvidas para otimizar as vendas e a performance da rede de franquias da **Cacau Show** 🍫.



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

