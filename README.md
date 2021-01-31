# Classificação de texto com avaliaçôes de filmes

Este *notebook* classifica avaliações de filmes como **positiva** ou **negativa** usando o texto da avaliação. Isto é um exemplo de classificação *binária* — ou 
duas-classes—, um importante e bastante aplicado tipo de problema de aprendizado de máquina.

Usaremos a base de dados [IMDB](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/imdb) que contém avaliaçòes de mais de $50\,000$ filmes do banco 
de dados [Internet Movie Database](https://www.imdb.com/). A base é dividida em $25\,000$ avaliações para **treinamento** e $25\,000$ para **teste**. 
Os conjuntos de treinamentos e testes são *balanceados*, ou seja, eles possuem a mesma quantidade de avaliações positivas e negativas.

O notebook utiliza [tf.keras](https://www.tensorflow.org/guide/keras), uma API alto-nível para construir e treinar modelos com **TensorFlow**. Para mais tutoriais 
avançados de classificação de textos usando `tf.keras`, veja em 
[MLCC Text Classification Guide](https://developers.google.com/machine-learning/guides/text-classification/).






Thanks God!
