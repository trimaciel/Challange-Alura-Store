# Challange-Alura-Store

Primeiro desafio da Especialização de Data Science para realizar a análise de vendas e desempenho de lojas

# Análise de Dados de Vendas para Decisão Estratégica de Negócios

## 🚀 Visão Geral do Projeto

Este projeto teve como objetivo realizar uma análise exploratória dos dados de vendas de quatro lojas distintas, pertencentes ao Senhor João. O principal objetivo foi identificar qual das lojas seria a mais adequada para venda, visando a obtenção de capital para um novo investimento 💰. A análise abrangeu diversas métricas de desempenho das lojas, incluindo faturamento total, categorias de produtos com maior e menor demanda, média de avaliação dos clientes, produtos de maior e menor sucesso de vendas e o custo médio de frete.

## ⚙️ Metodologia

O projeto foi desenvolvido seguindo as seguintes etapas:

1.  **Carregamento e Consolidação dos Dados:** Os dados de vendas de cada uma das quatro lojas, disponibilizados em arquivos CSV, foram carregados utilizando a biblioteca `pandas` no ambiente Google Colab. Posteriormente, os dados foram consolidados em um único DataFrame para facilitar a análise comparativa.

2.  **Análise das Métricas de Desempenho:** Para cada loja, foram calculadas e analisadas as seguintes métricas:
    * Faturamento Total:** Soma do valor de todas as vendas realizadas por cada loja.
    * Categorias Mais Populares:** Identificação da categoria de produto com maior número de vendas em cada loja.
    * Média de Avaliação dos Clientes:** Cálculo da média das avaliações de compra fornecidas pelos clientes de cada loja.
    * Produtos Mais e Menos Vendidos:** Identificação dos produtos com maior e menor frequência de venda em cada loja.
    * Custo Médio do Frete:** Cálculo da média do custo de frete para as vendas de cada loja.

3.  **Visualização dos Dados:** Para facilitar a interpretação e a apresentação dos resultados, foram gerados diversos tipos de gráficos utilizando as bibliotecas `matplotlib` e `seaborn`:
    * Gráfico de barras para o faturamento total por loja.
    * Gráfico de linhas para a média de avaliação dos clientes por loja.
    * Gráfico de barras lado a lado para comparar os produtos mais e menos vendidos em cada loja.
    * Gráfico de barras para o custo médio do frete por loja.

4. **Análise Geográfica das Vendas**
Para explorar a distribuição geográfica das vendas de cada loja, foram gerados mapas de calor utilizando a biblioteca `seaborn`. Esses mapas visam identificar as áreas de maior densidade de vendas para cada uma das quatro lojas, utilizando as coordenadas de latitude e longitude dos dados de venda. As áreas mais claras ou com cores mais intensas nos mapas representam uma maior concentração de vendas.

**Observações Preliminares dos Mapas de Calor:**

* **Loja 1:** Apresenta uma maior densidade de vendas concentrada principalmente na região Sudeste, com um foco notável nas áreas próximas ao litoral, possivelmente nos estados de São Paulo e Rio de Janeiro. Há também indicações de menor concentração em outras áreas mais ao sul e ao norte.
* **Loja 2:** A maior densidade de vendas também se concentra na região Sudeste, com um padrão de distribuição bastante similar ao da Loja 1, sugerindo uma forte presença nessa mesma área geográfica. Observam-se também algumas áreas de menor densidade distribuídas de forma semelhante às da Loja 1 em outras regiões.
* **Loja 3:** O mapa de calor também indica uma concentração significativa de vendas na região Sudeste, seguindo um padrão de alta densidade similar ao observado nas Lojas 1 e 2. Adicionalmente, nota-se uma presença, embora com menor densidade, em algumas áreas mais ao norte e ao sul, replicando a tendência das outras lojas.
* **Loja 4:** Também apresenta a maior densidade de vendas concentrada na região Sudeste, seguindo um padrão semelhante ao das outras lojas. No entanto, observa-se uma dispersão um pouco maior das vendas em outras regiões, com uma presença notável, embora com menor intensidade, nas regiões Nordeste e Sul, além de alguns pontos isolados no Centro-Oeste e Norte.

**Comparação Geral:**

A análise dos mapas de calor revela um padrão dominante, com a região Sudeste do Brasil apresentando a maior concentração de densidade de vendas para todas as lojas analisadas. As Lojas 1, 2 e 3 mostram uma concentração muito similar no Sudeste, enquanto a Loja 4 demonstra uma distribuição um pouco mais abrangente, com maior presença relativa em outras regiões.

5.  **Recomendação Estratégica:** Com base na análise das métricas e nas visualizações geradas, foi elaborado um relatório final com uma recomendação clara sobre qual loja seria a mais indicada para venda, juntamente com a justificativa detalhada da decisão.

## 🛠️ Ferramentas e Plataformas Utilizadas

* ** Plataforma de Desenvolvimento:** [Google Colaboratory (Colab)](https://colab.research.google.com/) - Um ambiente Python gratuito baseado na nuvem que permite executar notebooks Jupyter no navegador.
* ** Bibliotecas Python:**
    * `pandas`: Para manipulação e análise de dados tabulares.
    * `matplotlib`: Para criação de gráficos e visualizações 📈.
    * `seaborn`: Para aprimorar a estética dos gráficos matplotlib 🎨.
* ** Fonte de Pesquisa e Assistência:** [Gemini](https://gemini.google.com/) - Modelo de linguagem grande utilizado como assistente para auxiliar na elaboração do código, na compreensão de conceitos e na estruturação do relatório.
* ** Plataforma de Aprendizado:** [Alura](https://www.alura.com.br/) - A plataforma Alura foi utilizada como fonte de aprendizado e referência para conceitos de análise de dados e programação em Python, auxiliando na construção de um projeto robusto e bem fundamentado.

## 💻 Estrutura do Código

O código do projeto está organizado em um notebook Jupyter (`.ipynb`) e segue as etapas descritas na metodologia. As seções principais incluem:

* Carregamento e visualização inicial dos dados.
* Cálculo das métricas de desempenho para cada loja.
* Geração dos gráficos para cada métrica.
* Elaboração do relatório final com a recomendação 📝.

## 📉 Resultados e Conclusão

A análise dos dados revelou que a **Loja 4** apresenta o menor faturamento total e uma média de avaliação de clientes que não se destaca positivamente em comparação com as demais. Embora o custo médio do frete seja o menor nessa loja, esse fator isoladamente não compensa o desempenho inferior nas outras métricas principais.

Com base nesses achados, o relatório final recomendou a **venda da Loja 4** como a opção mais estratégica para o Senhor João, visando a obtenção de capital para seu novo investimento. A decisão foi fundamentada na análise comparativa das lojas em relação ao faturamento, à satisfação dos clientes e aos custos de frete, considerando o cenário geral de desempenho de cada unidade.

## ⏭️ Próximos Passos (Opcional)

*  Realizar uma análise mais aprofundada da lucratividade e dos custos operacionais de cada loja.
*  Avaliar o valor de mercado dos ativos de cada loja para auxiliar na decisão de venda.
*  Analisar as tendências de crescimento de cada loja ao longo do tempo.

🍀 **Tri Maciel**  
📫 [trimaciel@hotmail.com](mailto:trimaciel@hotmail.com) / [trimaciel.souza@gmail.com](mailto:trimaciel.souza@gmail.com)  
✨ *Em frente!*

