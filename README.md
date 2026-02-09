# Projecto-Goodreads

---

# Análisis de Datos de Libros en Goodreads 📚📊

En este proyecto, realizamos un flujo completo de análisis de datos: desde la EDA y limpieza, a través de visualizaciones utilizando Matplotlib y Seaborn hasta el análisis estadístico. El paso final es la visualización complementaria - hasta la creación de un dashboard interactivo en Power BI. El objetivo es explorar los factores que puedan influir en la popularidad de los libros y entender la distribución de la literatura en la plataforma Goodreads

🎯 **Nuestro objetivo:** Proporcionar una visión detallada de la biblioteca de Goodreads, analizando la relación entre el idioma en el que libro está escrito, la cantidad de valoraciones y el éxito de los títulos, apoyando así la comprensión de las tendencias actuales en el sector editorial.

📂 **Estructura del Proyecto:**

* ├── **EDA_Limpieza_y_Analisis_Estadistico_Goodreads.ipynb**: Nuestro notebook con el procesamiento de datos, pruebas estadísticas y visualizaciones.
* ├── **goodreads.csv**: Dataset inicial.
* ├── **goodreads_limpio.csv**: Dataset final tras la EDA, limpieza, gestión de duplicados, y gestión de nulos, preparado para visualizaciones en PowerBi. 
* ├── **Proyecto_Goodreads.pbix**: Dashboard interactivo de Power BI que consiste de una página de muestra protagonizada por seis visualizaciones distintas.
* └── **README.md**: Documentación del proyecto que desglosa los detalles de nuestro análisis.

⚙️ **Herramientas Utilizadas:**

* **Python** (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
* **Power BI**
* **Visual Studio Code / Jupyter Notebook**

🚀 **Exploración del Análisis:**

El proyecto se divide en tres fases fundamentales:

1.**EDA, limpieza y visualización (Python):**:

* Entre otros cambios, se han eliminado la columnas `isbn` y `isbn13`, puesto que no aportaron nada a nuestro análisis o visualización. 
* Se han redondeado valores a dos decimales en la columna `average rating`.
* Se han hecho cambios relevantes en cuanto a la distribución de idiomas en la columna `language_code`.
* Se gestionaron valores duplicados (comprobando si habia diferentes ediciones del mismo libro), y los valores nulos. 

* Durante la fase de la visualización, utilizando las bibliotecas de matplotlib y seaborn,y varios gráficos como barplot, lineplot, boxplot, scatterplot, etc, se ha respondido a varias preguntas importantes relacionadas con nuestro dataset.

1. **Distribución de calificaciones:** ¿Cómo se distribuyen las puntuaciones promedio? (Usando histogramas y KDE).
2. **Relación Páginas/Calificación:** ¿Influye la longitud del libro en su nota media?
3. **Proporción de Idiomas:** ¿Cuál es el peso de los idiomas principales tras la limpieza?
4. **Top 5 Autores:** ¿Cómo varía la calificación promedio entre los autores con más libros?
5. **Evolución de Reseñas:** ¿Cómo ha cambiado el número promedio de reseñas a lo largo de los años?
6. **Correlación Votos/Reseñas:** ¿Existe una relación directa entre el número total de votos y las reseñas escritas?

2. **Análisis Estadístico (Python):** 

* Se realizó un **Test de Mann-Whitney U** para comparar las calificaciones entre libros en inglés y otros idiomas, para ver si el idioma influyía en la calificación. Hemos obtenido el resultado que nos ha indicado que no hay diferencias significativas en la calidad percibida, a pesar de la diferencia en volumen.


3. **Visualización (Power BI):**

* **Distribución por Idioma:** Un gráfico de donut que muestra el dominio del inglés (94.74%) frente a otros idiomas.
* **Evolución Temporal:** Gráfico de áreas que muestra el crecimiento exponencial de publicaciones hacia el año 2000.
* **Top Rankings:** Listados de los autores más prolíficos (liderados por Stephen King) y los títulos con mayor impacto social.



🔍 **Principales Conclusiones:**

* **Conclusión 1: Dominio del Mercado:** Aunque el inglés acapara casi el 95% de los datos, la calidad de los libros (rating medio) se mantiene constante independientemente del idioma de publicación.
* **Conclusión 2: Autores Prolíficos:** Stephen King destaca no solo en volumen de obras, sino en mantener una base crítica masiva de lectores.
* **Conclusión 3: Tendencia de Lectura:** El análisis temporal revela que la digitalización y el acceso a plataformas como Goodreads han impulsado el registro de libros publicados en las últimas dos décadas.

🤝 **Autor:**

* **Evelina Saponjic Jovanovic**: Data Analyst

