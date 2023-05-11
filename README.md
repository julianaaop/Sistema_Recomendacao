# Sistema de Recomendação de Filmes usando TF-IDF e CountVectorizer
Este projeto tem como objetivo construir um sistema de recomendação de filmes usando a linguagem de programação Python. O sistema de recomendação é baseado no algoritmo de similaridade de cosseno e utiliza o TfidfVectorizer e o CountVectorizer da biblioteca Scikit-Learn.

# Conjunto de dados
O conjunto de dados usado neste projeto consiste em informações sobre filmes, incluindo títulos, sinopses, elenco, diretores e palavras-chave. Os dados foram obtidos a partir da plataforma Kaggle, link abaixo:
https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv

# Implementação
O sistema de recomendação é implementado em Python e usa as seguintes bibliotecas:

pandas: para manipulação de dados
Scikit-Learn: para implementação do TfidfVectorizer, CountVectorizer e cálculo de similaridade de cosseno
NLTK: para processamento de linguagem natural
O sistema de recomendação é baseado em dois algoritmos principais: TF-IDF e CountVectorizer. Primeiro, é usado o TfidfVectorizer para criar uma matriz de termos-frequência inversa de documentos. Em seguida, é calculada a similaridade de cosseno entre os filmes com base na matriz TF-IDF.

Além disso, é feita a criação de uma "sopa" de palavras-chave, elenco e diretores para cada filme, que é usada como entrada para o CountVectorizer. Com base nessa matriz de frequência de palavras, é calculada a similaridade de cosseno entre os filmes.

# Como executar o código
Para executar o código, é necessário ter o Python e as bibliotecas pandas, Scikit-Learn e NLTK instaladas. É possível rodar o código em um ambiente de desenvolvimento como o Jupyter Notebook ou em um editor de texto como o VS Code.

O código está dividido em seções e pode ser executado passo a passo. É possível alterar o filme de referência para obter recomendações diferentes.
