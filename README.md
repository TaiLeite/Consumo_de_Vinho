# Consumo_de_Vinho

# Análise de Dados: Fatores de Influência no Mercado de Vinhos 🍷

Este projeto realiza uma análise exploratória de dados (EDA) sobre o dataset *Wine Reviews* (Kaggle), buscando entender como variáveis como origem, pontuação e prestígio influenciam o preço e a decisão de compra dos consumidores.

##  Objetivos do Projeto
* Identificar a correlação entre a qualidade técnica (pontuação) e o preço de mercado.
* Analisar o desempenho de diferentes países produtores.
* Isolar "outliers" de mercado (vinhos com preços desproporcionais à qualidade).
* Identificar oportunidades de melhor custo-benefício para o consumidor.

##  Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** * `Pandas` para manipulação e limpeza de dados.
  * `Matplotlib` e `Seaborn` para visualização de dados.
* **Inteligência Artificial:** Utilização do `Google Gemini` como assistente de *pair programming* para refinamento de lógica visual e estilização de gráficos.

##  Principais Insights

### 1. O Paradoxo do Luxo
Durante a análise, identificamos casos onde o preço é guiado pelo status da marca e não apenas pela nota técnica. 
* *Exemplo:* Vinhos com 88 pontos custando mais de \$1.500,00, enquanto vinhos de 100 pontos custam significativamente menos.

### 2. A Eficiência Austríaca vs. Prestígio Francês
Ao aplicar um filtro de relevância (países com mais de 100 avaliações), descobriu-se que:
* A **Áustria** apresenta a maior média de pontuação com preços competitivos.
* A **França** mantém preços médios elevados devido ao prestígio histórico, mesmo com uma média de pontos variada devido ao grande volume de produção.

##  Tratamento de Dados (Data Cleaning)
Para garantir a integridade da análise, foram realizados os seguintes passos:
1. Remoção de registros com valores nulos na coluna de preço.
2. Tratamento de outliers manuais (remoção de erros de entrada de dados).
3. Criação de filtros de volume para evitar o viés de amostras pequenas (ex: Inglaterra).

##  Visualizações
O gráfico acima demonstra como a Áustria e a Alemanha lideram em pontuação média quando filtramos países com volume relevante, superando potências tradicionais no rácio qualidade/preço.

![Ranking de Países](<img width="1980" height="1499" alt="meu_grafico_top10" src="https://github.com/user-attachments/assets/1992ad69-f465-4bfe-b441-0dd5e8ceba07" />)


---
**Autora:** Taiane Leite  
**Formação:** Enfermeira Assistencial e Graduanda em Ciência da Computação.
