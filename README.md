# Projecto-Goodreads

---

# Análisis de Datos de Libros en Goodreads 📚📊

En este proyecto, realizamos un flujo completo de Ciencia de Datos: desde la limpieza y el análisis estadístico en Python hasta la creación de un dashboard interactivo en Power BI. El objetivo es explorar los factores que influyen en la popularidad de los libros y entender la distribución de la literatura en la plataforma.

🎯 **Nuestro objetivo:** Proporcionar una visión detallada de la biblioteca de Goodreads, analizando la relación entre el idioma, la cantidad de valoraciones y el éxito de los títulos, apoyando así la comprensión de las tendencias actuales en el sector editorial.

📂 **Estructura del Proyecto:**

* ├── **EDA_Limpieza_y_Analisis_Estadistico_Goodreads.ipynb**: Notebook con el procesamiento de datos y pruebas estadísticas.
* ├── **goodreads_limpio.csv**: Dataset final tras la limpieza y gestión de nulos.
* ├── **Proyecto_Goodreads.pbix**: Dashboard interactivo de Power BI.
* └── **README.md**: Documentación del proyecto.

⚙️ **Herramientas Utilizadas:**

* **Python** (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
* **Power BI**
* **Visual Studio Code / Jupyter Notebook**

🚀 **Exploración del Análisis:**

El proyecto se divide en dos fases fundamentales:

1. **Análisis Estadístico (Python):** * Se gestionaron valores nulos en columnas críticas como `language` y `publisher`.
* Se realizó un **Test de Mann-Whitney U** para comparar las calificaciones entre libros en inglés y otros idiomas, obteniendo un valor , lo que indica que no hay diferencias significativas en la calidad percibida a pesar de la diferencia en volumen.
* Análisis de correlación donde destaca una fuerte relación (**0.87**) entre el número de valoraciones y el número de reseñas escritas.


2. **Visualización (Power BI):**
* **Distribución por Idioma:** Un gráfico de donut/treemap que muestra el dominio del inglés (94.74%) frente a otros idiomas.
* **Evolución Temporal:** Gráfico de áreas que muestra el crecimiento exponencial de publicaciones hacia el año 2000.
* **Top Rankings:** Listados de los autores más prolíficos (liderados por Stephen King) y los títulos con mayor impacto social.



🔍 **Principales Conclusiones:**

* **Conclusión 1: Dominio del Mercado:** Aunque el inglés acapara casi el 95% de los datos, la calidad de los libros (rating medio) se mantiene constante independientemente del idioma de publicación.
* **Conclusión 2: Autores Prolíficos:** Stephen King destaca no solo en volumen de obras, sino en mantener una base crítica masiva de lectores.
* **Conclusión 3: Tendencia de Lectura:** El análisis temporal revela que la digitalización y el acceso a plataformas como Goodreads han impulsado el registro de libros publicados en las últimas dos décadas.

🤝 **Autor:**

* **Evelina Saponjic Jovanovic**: Data Analyst

