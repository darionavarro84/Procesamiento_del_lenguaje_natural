   Hola! Este repositorio contiene las soluciones a 6 desafíos correspondientes a las temáticas vistas en el curso
de NLP del posgrado de la FIUBA en Inteligencia Artificial.

 A continuación, un resumen breve del contenido de este repositorio:

### **1-Vectorización**

__Objetivo:__ práctica de generación manual de funciones habituales en el preprocesamiento de textos:

__Contenido:__
-  Tokenización
-  Generación de corpus
-  Vectorización one-hot y TF-IDF
-  Comparación de oraciones en base a similitud coseno

### **2-ChatBot de recomendación**

 __Objetivo:__ diseño de un bot de consulta abierta y respuestas predeterminadas usando DNN+Spacy.

__Contenido:__
 - Generación de un dataset con potenciales preguntas y respuestas.
-  Preprocesamiento.
-  Definición de una arquitectura de red neuronal densa.
-  Ajuste de hiperparámetros y entrenamiento de la DNN. 
-  Testing y validación.


### **3-Custom embeddings**

__Objetivo:__ creación y entrenamiento de los embeddings correspondientes a un corpus elaborado en base al texto de Freud “The interpretation of the dreams”.

__Contenido:__
 - Generación de un dataset en base al texto.
-  Preprocesamiento del texto.
-  Generación de los vectores word2vec.
-  Entrenamiento de embeddings.
-  Ensayo de embeddings (‘get_most_similar’ y ‘get_less_similar’).
- Test de analogías sobre los embeddings entrenados.  


### **4-Predicción de la próxima palabra**

 __Objetivo:__ utilizar un texto para crear embeddings de palabras basado en ese contexto utizando la layer Embedding de Keras. Se utilizará esos embeddings junto con layers LSTM para intentar predecir la próxima palabra.

__Contenido:__
 - Generación de un dataset en base a la novela : “El retrato de Dorian Gray”.
-  Preprocesamiento del texto
-  Definición de una red neuronal recurrente usando embeddings y capas LSTM.
-  Entrenamiento de la RNN
-  Ensayo de predicciones

  
### **5-Sentiment analysis**

 __Objetivo:__ utilizar las críticas de compradores de ropa para que el sistema determine la evaluación del comprador y su crítica (cuantas estrellas le asigna al producto).

__Contenido:__
 - Generación de un dataset en base a críticas de usuarios de una tienda de ropa.
-  Preprocesamiento del texto
-  Definición de una red neuronal recurrente usando embeddings y capas LSTM.
-  Entrenamiento de la RNN
-  Testing y validación


### **6-Chatbot conversacional**
 __Objetivo:__ utilizar un dataset con preguntas y respuestas para construir un bot conversacional usando redes recurrentes con arquitectura encoder/decoder.

__Contenido:__
 - Generación de un dataset .
-  Preprocesamiento del dataset
-  Definición de una red neuronal con estructura encoder/decoder usando embeddings pre entrenados de Fasttext y capas LSTM.
-  Entrenamiento de la red y ajuste de hiperparámetros
-  Testing y validación


