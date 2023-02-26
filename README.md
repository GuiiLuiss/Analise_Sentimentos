# Analise_de_Sentimentos

# Objetivo
Com base nas informações dispostas nesse conjunto de dados, irei trabalhar no tratamento, limpeza e transformação do texto com o objetivo de treinar um modelo de machine learning capaz de classificar cada amostra do dataset como uma das seguintes labels: positiva, negativa ou neutra.

# Sobre os Dados
O 'Financial Phrase Bank' é um conjunto de dados desenvolvido originalmente para o artigo [Good Debt or Bad Debt: Detecting Semantic Orientations in Economic Texts](https://www.researchgate.net/publication/251231107_Good_Debt_or_Bad_Debt_Detecting_Semantic_Orientations_in_Economic_Texts), disponibilizado por pesquisadores da Aalto University e do Indian Institute of Management. O conjunto de dados permite uma referência útil para ajustar modelos de linguagem em tarefas de análise de sentimento.

Esse estudo estará utilizando dados traduzidos pelo [Mateus Picanco](https://www.kaggle.com/mateuspicanco) - Cientista de Dados na Microsoft, na qual disponibilizou o dataset através da plataforma 'Kaggle' para trabalharmos.

O conjunto de dados originalmente contém notícias financeiras anotadas manualmente em inglês e consiste em três colunas:

- **y:** o rótulo anotado para o sentimento do texto da notícia (neutro, positivo, negativo)
- **text:** o texto original de cada registo
- **text_pt:** a versão traduzida manualmente do registro original
