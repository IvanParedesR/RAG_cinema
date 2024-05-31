# RAG Proyecto de recomendador de peliculas
En este RAG, se busca hacer un recomendador de peliculas que Ivan recomienda (Yo soy Ivan). La estructura del RAG es relativamente simple:

-* Instalacción de bibliotecas e importación de las bibliotecas instaladas
-* Carga de API-keys de OpenAI. Por seguridad no estoy incluyendo la APIKEY de OPENAI. Para correrlo, se necesitaría generar una APIKEY e insertarla.
-* Cargar base de datos con texto sin embeddings, la base de datos en csv incluye: Año de la cinta o TV show, nombre de la cinta, reseña y mi opinión.
-* Generar embeddings con el texto. Los embeddings son representaciones numéricas que captan las similitudes y relaciones entre conceptos
-* Definir funciones especificas para realizar la busqueda, definir el mensaje de respuesta, responder.
-* Realizar la busqueda.
