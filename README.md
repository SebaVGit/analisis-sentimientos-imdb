# Análisis de Sentimientos IMDB
* Ejercicio de análisis de sentimientos con dataset de IMDB y tensorflow.
* Esta basado en una pregunta de un ejercicio del curso `Modelos Computacionales de la Física y Astronomía` de la UNAB (Universidad Andrés Bello. Chile).

Se considera la base de datos del sitio IMDB para clasificar sentimientos en positivos(1) o negativos(0). Esta base de datos consiste en 50000 reviews de películas, donde cada review es transformado en una secuencia de índices de palabras en forma de números. Las palabras dentro de los reviews son indexadas por su frecuencia promedio dentro del set de datos. Por ejemplo el entero "2" corresponde a la segunda palabra
más frecuente de los datos. Este set de datos fue creado por investigadores de la Universidad de Stanford,
y publicado en [este paper](https://ai.stanford.edu/~amaas/papers/wvSent_acl2011.pdf) el año 2011.
