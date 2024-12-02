# Previsão de Próxima Palavra com Word2Vec e RNN
## Este repositório contém uma implementação completa de um pipeline para:

1.  Pré-processamento de texto.
2.  Treinamento de embeddings de palavras utilizando Word2Vec com a biblioteca Gensim.
3.  Construção e treinamento de um modelo de RNN com TensorFlow/Keras para prever a próxima palavra em uma sequência de texto.

## Recursos
### Linguagem: Python 3.x.
### Bibliotecas Principais:
* Gensim: Para geração de embeddings com Word2Vec.
* TensorFlow/Keras: Para criação e treinamento do modelo RNN.
* NLTK: Para tokenização e manipulação de texto.
* NumPy: Para manipulações numéricas.
* Pandas: Para manipulação de datasets.

  
## Pipeline do Projeto
## Pré-Processamento de Texto:
Tokenização e limpeza do texto (remoção de pontuações, stopwords, etc.).
Conversão do texto em listas de palavras.
## Treinamento de Embeddings:
Treinamento de um modelo Word2Vec utilizando Gensim para transformar palavras em vetores contínuos no espaço semântico.
## Preparação de Dados para RNN:
Construção de sequências de treinamento com janelas deslizantes (input de sequência e saída como próxima palavra).
Transformação de palavras em vetores usando os embeddings treinados.
## Modelo de Previsão de Próxima Palavra:
Implementação de uma RNN usando TensorFlow/Keras.
Arquitetura flexível com camadas como LSTM/GRU para capturar dependências sequenciais.
Treinamento e avaliação do modelo.


