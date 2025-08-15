### Projeto 5: Análise de Avaliações de E-commerce de Roupas Femininas (EDA)

#### **Visão Geral**

Neste projeto de Análise Exploratória de Dados (EDA), investiguei e extraí insights de um conjunto de dados de avaliações de e-commerce de roupas femininas. O foco da análise foi entender as métricas de desempenho, identificar padrões nas avaliações e preparar o terreno para futuras análises de negócio.

#### **Objetivos do Projeto**

* Realizar a limpeza inicial dos dados, identificando tipos de dados, valores ausentes e estatísticas básicas.
* Calcular métricas de desempenho (KPIs) relevantes, como a quantidade de avaliações e a média de notas por faixa etária.
* Identificar a distribuição de avaliações por estrelas para entender a satisfação geral das clientes.
* Encontrar quais itens são os mais avaliados e a quantidade de feedback positivo que recebem.

#### **Metodologia**

A análise foi conduzida através dos seguintes passos:

1.  **Exploração de Dados:** Iniciei com uma visão geral do dataset para entender a estrutura, os tipos de dados e o volume de informações.
2.  **Limpeza e Tratamento:** Identifiquei e quantifiquei os valores ausentes por coluna.
3.  **Cálculo de Métricas:** Calculei a média, mediana, moda, mínimo e máximo das colunas numéricas, fornecendo uma base sólida de KPIs.
4.  **Análises Específicas:** Respondi a perguntas de negócio como a média de avaliação por faixas de idade e o ranking de itens mais comentados.

#### **Resultados da Análise e Principais Insights**

* **Métricas Gerais:**
    * **Linhas no Dataset:** 23.486
    * **Roupas Avaliadas:** 1.206 itens únicos.
* **Resumo Estatístico das Colunas Numéricas:**
    * **Idade (Age):** A idade média das clientes é de 43.20 anos.
    * **Avaliação (Rating):** A avaliação média é de 4.20, com a maioria das clientes dando 5 estrelas.
    * **Feedback Positivo (Positive Feedback Count):** A média de feedback positivo por avaliação é de 2.54.
* **Satisfação por Idade:**
    * Média de avaliação para mulheres de até 20 anos: **4.32**.
    * Média para mulheres de até 40 anos: **4.17**.
* **Distribuição de Avaliações:** O gráfico de barras mostra que a maioria das avaliações (13.131) deu 5 estrelas, indicando um alto nível de satisfação.
* **Item Mais Popular:** A roupa com o ID **1078** é a que possui o maior número de avaliações.


### **Arquivos**

* Womens_Clothing_Reviews_Cleaned.csv: A planilha com os dados processados.
* Resumo_Estatisticas_Numericas.csv: Uma tabela com as medidas de tendência central.
* Avaliacoes_por_Estrela.png: O gráfico de barras que mostra a distribuição das avaliações.
