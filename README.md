![image](https://github.com/hernancontigiani/ceia_memorias_especializacion/raw/master/Figures/logoFIUBA.jpg)

#  PNL - Entrega final de desafios 

A lo largo de la cursada de la materia, pudimos explorar distintos métodos y librerías de procesamiento de texto especializados en machine learning para resolver distintos problemas y requerimientos del mercado actual tales como bots conversacionales, traductores, y summarizers.

A continuacion destilamos un poco más los desafíos junto a una breve descripcion de cada uno y sus links de referencia:

### Desafío 1
Se exploró el uso de vectorizadores de texto como TfidfVectorizer y CountVectorizer, aplicamos Naïve Bayes con MultinomialNB y ComplementNB con el dataset de '20 newsgroups'. 
    
Link del desafio: https://github.com/christophcharaf/procesamiento_lenguaje_natural/blob/main/clase_1/ejercicios/Desafio_1.ipynb

### Desafío 2
Utilizamos embeddings de Gensim para generar los textos en base al famoso libro de Moby Dick, ejercicio en el cual identificamos una forma muy precaria de 'prediccion' de palabras proximas asi como tambien visualizamos los terminos vecinos dentro de nuestro corpus generado.

Link del desafio: https://github.com/christophcharaf/procesamiento_lenguaje_natural/blob/main/clase_2/jupyter_notebooks/Desafio%202.ipynb

### Desafío 3
Exploramos el uso de una arquitectura de redes neuronales con capas LSTM, lo cual nos permite generar predicciones de secuencias en base a contexto.

Para este fin utilizamos como corpus un album de musica rock de Avenged Sevenfold, en el cual evaluamos la prediccion del modelo utilizando tecnicas como beam search determinisco y estocástico, asi como tambien greedy search.

Link del desafío: https://github.com/christophcharaf/procesamiento_lenguaje_natural/blob/main/clase_3/ejercicios/desafio_3/desafio_3.ipynb


### Desafío 4
Se desarrolló un BOT para responder preguntas de los usuarios. Se utilizaron embeddings de GloVe y se implementaron dos capas LSTM para el encoder y el decoder, además de una capa densa en la salida.

Si bien el desempeño del modelo no fue muy bueno, se intentó demostrar la funcionalidad basica y modularidad en cuanto a estructura que puede llegar a tener un modelo como este.

Link al desafio:
https://github.com/christophcharaf/procesamiento_lenguaje_natural/blob/06319bc92458da7d6ed45fff37734eb9afd12a6d/clase_6/ejercicios/6_bot_qa.ipynb
