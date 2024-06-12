# Propuestas Experimentales


## Pregunta experimental 1: ¿Existen características específicas de las películas que permiten tener mejor o peor  calificación?

Con esta pregunta se busca encontrar patrones en distintas combinaciones de las características, las cuales tengan una cierta tendencia a cómo son recibidas con el público. Siendo estas características las mismas que los antecedentes del cine.

## Pregunta experimental 2: ¿Cuáles son los antecedentes del cine que tienen un mayor impacto en las calificaciones?

Aquí es de interés encontrar antecedentes del cine que tengan mayor influencia que otros para así poder hacer una reducción de dimensionalidad y concentrarse en los atributos que afectan con mayor cantidad a la calificación de una película.

## Pregunta experimental 3: ¿Existen asociaciones entre películas que rompan el sesgo popular sobre el cine respecto a sus antecedentes?

Con estas preguntas se intenta romper sesgos preconcebidos, dado que, en el caso de las películas que son muy de cultura general, todas las personas tienden a tener opiniones, críticas y observaciones, creando inclinaciones que podrían llevar a no investigar o analizar correctamente los datos.

### Propuesta Experimental: 

- Para juzgar el sesgo popular en el cine, se ha decidido limitar el estudio según los atributos 'rating', 'country', 'minute', 'date' y 'genre'. En el dataset hay películas que no poseen información en estas columnas, por lo que se debe preprocesar los datos para limpiar estos registros.
- Además, se modificarán los géneros y los países usando la técnica One-Hot Encoding para convertir estos atributos en variables numéricas.
- Se aplicarán técnicas de clustering para buscar asociaciones entre las películas, utilizando tanto clustering jerárquico como espectral.
- El clustering se probará con distintos subconjuntos de atributos para ver cómo se comportan los datos.
- Para evaluar los clusters, se utilizará el enfoque visual, además de medidas como el coeficiente de Silhouette, cohesión y separación, cada una proporcionando información complementaria sobre la calidad y definición de los clusters.


