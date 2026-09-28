# Pipeline Avanzado de Procesamiento del Lenguaje Natural (PLN) y Minería de Texto
Stiven David Alvarez Olmos 
Dairo Enrique Contreras Quintana 

Este repositorio contiene la implementación práctica y documentada de un pipeline completo de **Procesamiento del Lenguaje Natural (PLN)** y **Minería de Texto** aplicado a un corpus de comentarios de YouTube sobre tecnología y educación. El proyecto abarca desde el preprocesamiento tradicional hasta tareas avanzadas utilizando modelos de **Transformers** y **LLMs** bajo buenas prácticas de MLOps.

---

##  Tecnologías y Librerías Utilizadas

* **Lenguaje:** Python 3.10+
* **Entorno de Ejecución:** Google Colab / Jupyter Notebooks
* **PLN & Procesamiento Léxico:** `spaCy` (`es_core_news_sm`), `NLTK`, `TextBlob`
* **Transformers & LLMs:** `Hugging Face Transformers`, `PyTorch`, `sentence-transformers`
* **Machine Learning & Vectorización:** `scikit-learn` (TF-IDF, LDA, Cosine Similarity, CountVectorizer)
* **Análisis y Manipulación de Datos:** `pandas`, `numpy`

---

##  Tareas y Procesos Implementados en el Pipeline

1. **Preprocesamiento y Normalización de Texto:** Limpieza con expresiones regulares (Regex), eliminación de Stopwords en español, Stemming (`SnowballStemmer`) y Lematización (`spaCy`).
2. **Representaciones Vectoriales y Desagregadas:** Matriz TF-IDF, Frecuencia de Término (TF) e Inverse Document Frequency (IDF) calculadas y presentadas por separado.
3. **Análisis Sintáctico y Semántico:** Etiquetado de Partes de la Oración (POS Tagging), Parsing Sintáctico de dependencias gramaticales (relaciones núcleo/cabecera) y Reconocimiento de Entidades Nombradas (`NER`).
4. **Machine Learning y Clasificación:** Modelado de Temas con Asignación Latente de Dirichlet (LDA) y Análisis de Sentimientos con puntuación de polaridad.
5. **Recuperación e Inserción Vectorial:** Búsqueda por Similitud del Coseno para Recuperación de Información (IR) y Word Embeddings densos (96 dimensiones).
6. **Tareas Avanzadas de PLN y Transformers:**
   * **Question Answering:** Extracción de respuestas contextuales sobre el corpus mediante modelos preentrenados.
   * **Summarization Real:** Resumen neuronal abstractivo utilizando `DistilBART`.
   * **Sentence Similarity:** Comparación semántica par a par entre oraciones con `sentence-transformers`.
   * **Traducción Automática (Translation):** Mapeo explícito de texto de Español a Inglés (`Helsinki-NLP`).
   * **Generación de Texto (LLM):** Generación causal de texto a partir de un *prompt* con `DistilGPT2`.
   * **Minería de Texto (Text Mining):** Extracción de patrones de co-ocurrencia y análisis de N-gramas (bigramas).

---

##  Instrucciones para Replicación

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/stivenalvarez/Proyecto-PLN.git](https://github.com/stivenalvarez/Proyecto-PLN.git)
   cd Proyecto-PLN 
