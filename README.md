Análise de Sentimentos em Textos Twitter 
 
Descrição

Este projeto consiste em uma análise de sentimentos em textos usando aprendizado de máquina. O objetivo é classificar sentenças em sentimentos positivos ou negativos. O modelo é treinado com base em um conjunto de dados rotulado contendo exemplos de sentenças e seus respectivos rótulos de sentimento.

Conjunto de Dados

O conjunto de dados usado neste projeto contém sentenças em português com rótulos de sentimento (1 para positivo e 0 para negativo). O arquivo CSV de exemplo (test_data.csv) está incluído neste repositório.

Pré-processamento

As sentenças são pré-processadas para remover stopwords, pontuações e transformar o texto em minúsculas. A tokenização é realizada para dividir as sentenças em palavras individuais.

Treinamento do Modelo

O modelo de classificação utilizado é o Support Vector Machine (SVM) com kernel linear. Os textos são vetorizados usando o método TF-IDF para representá-los em formato numérico. O modelo é treinado usando um conjunto de treinamento e, em seguida, avaliado com um conjunto de teste.

Métricas de Avaliação

O desempenho do modelo é avaliado usando várias métricas, incluindo acurácia, precisão, recall e F1-score. Além disso, uma matriz de confusão é apresentada para analisar o desempenho do modelo para cada classe de sentimento.

Resultados

Os resultados obtidos mostram que o modelo possui uma acurácia de aproximadamente 79%. As métricas de precisão, recall e F1-score fornecem uma visão detalhada do desempenho para cada classe de sentimento.

Como Executar o Código

Clone este repositório em seu ambiente local.
Certifique-se de ter as bibliotecas necessárias instaladas (pandas, numpy, matplotlib, scikit-learn, nltk).
Execute o arquivo sentiment_analysis.ipynb em seu ambiente Jupyter Notebook ou Jupyter Lab.
Observações

O conjunto de dados usado aqui é um exemplo de teste. Para um projeto real, é recomendado usar um conjunto de dados mais abrangente e diversificado.
O pré-processamento e treinamento podem ser adaptados para diferentes idiomas e domínios, dependendo do contexto do projeto.
Referências

Scikit-learn Documentation
NLTK Documentation
