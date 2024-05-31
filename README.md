# RAG Proyecto de recomendador de peliculas
https://raw.githubusercontent.com/IvanParedesR/RAG_cinema/download (2).jpg
# Structure
In this RAG, the goal is to create a movie recommendation system that recommends movies I, Ivan, suggest. The structure of the RAG is relatively simple:

* Installation of libraries and import of installed libraries.
* Loading OpenAI API keys. For security reasons, I am not including the OpenAI API key. To run it, you will need to generate an API key and insert it.
* Load a database with text without embeddings; the CSV database includes: Year of the movie or TV show, name of the movie, review, and my opinion.
* Generate embeddings with the text. Embeddings are numerical representations that capture the similarities and relationships between concepts.
* Define specific functions to perform the search, define the response message, and respond.
* Perform the search.

# Background
This script is the fourth iteration of the RAG. Each of the previous RAGs had unacceptable errors. T-1 (a clear reference to Terminator), based on what Professor Rodrigo Rivera Castro gave us, was very complex and did not reflect my level of knowledge. T-2, redone from scratch, did not run at all; its problem was mainly that the embedding model was different from the model that performed the search. T-3 ran, but almost 90% of its responses were exclusively from CHATGPT.

# Future Adjustments
There are three main improvements I need to make:

* Generate a graphical interface, probably using Flask.
* Expand the database. One way would be to query the IMDB or Wikipedia API.
* Modify the model to respond using other AIs.

# Usage Instructions
* Load the database included here and then run the attached script. IT IS IMPORTANT TO INCLUDE YOUR OPENAI API KEY; OTHERWISE, IT WILL NOT WORK.

## Estructura
En este RAG, se busca hacer un recomendador de peliculas que Ivan recomienda (Yo soy Ivan). La estructura del RAG es relativamente simple:

* Instalacción de bibliotecas e importación de las bibliotecas instaladas
* Carga de API-keys de OpenAI. Por seguridad no estoy incluyendo la APIKEY de OPENAI. Para correrlo, se necesitaría generar una APIKEY e insertarla.
* Cargar base de datos con texto sin embeddings, la base de datos en csv incluye: Año de la cinta o TV show, nombre de la cinta, reseña y mi opinión.
* Generar embeddings con el texto. Los embeddings son representaciones numéricas que captan las similitudes y relaciones entre conceptos
* Definir funciones especificas para realizar la busqueda, definir el mensaje de respuesta, responder.
* Realizar la busqueda.

## Antecedentes
Este script es la cuarta iteración del RAG. Cada uno de los RAGs previos tuvo errores inaceptables. El T-1 (Clara referencia a Terminator), basado en lo que nos dió el profesor Rodrigo Rivera Castro era muy complejo y me parece que no reflejaba mi nivel de conocimiento. El T-2, rehecho desde cero, no corría nada, su problema radicaba principalmente en que el modelo de embedding era diferente al modelo que realizaba la busqueda. El T-3 corría pero casi el 90% de sus respuestas eran exclusivamente de CHATGPT.

## Adecuaciones futuras
Hay 3 principales mejoras que necesito hacer:
* Generar una interfaz gráfica. Probablmente usando Flask.
* Ampliar la base de datos. Una forma sería hacer una consulta a la API de IMDB o de Wikipedia.
* Modificar el modelo para responder usando otras AIs.

## Instrucciones de uso.

Cargar la base de datos que se incluye aquí y posteriormente correr el script anexo. ES IMPORTANTE INCLUIR TU APIKEY DE OPENAI, DE OTRO MODO NO FUNCIONARÁ.

## Be nice to robots

