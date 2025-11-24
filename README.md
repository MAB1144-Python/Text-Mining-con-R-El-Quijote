# 📊 Minería para Big Data — Tarea 3  
**Modelado para grandes volúmenes de datos**

Este repositorio contiene los materiales necesarios para desarrollar la **Tarea 3** del curso **Minería para Big Data (203238426)**.  
El objetivo principal es implementar técnicas de minería de datos para analizar grandes volúmenes de información, aplicando procesos ETL, minería de texto y modelado predictivo.

---

## 📁 Contenido del repositorio

### 📂 Datasets incluidos
| Archivo | Descripción |
|--------|-----------|
| **ACT3_Dataset.xlsx** | Dataset principal para procesos ETL, exploración e integración. |
| **ACT3_diabetes.csv** | Dataset tabular para análisis predictivo (clasificación / regresión). |
| **ACT3_pricerunner_aggregate.csv** | Dataset agregado para análisis exploratorio y correlaciones. |

---

### 📚 Documentos para minería de texto
| Archivo | Uso |
|--------|-----|
| **DONQUIJOTE_PARTE1.pdf** | Texto fuente para minería de texto. |
| **DONQUIJOTE_PARTE2.pdf** | Texto fuente complementaria para minería de texto. |
| **Junta de Castilla y León_ EL QUIJOTE EN PDF.pdf** | Versión adicional del texto para pruebas o comparaciones. |

> Estos documentos pueden utilizarse para extraer tokens, generar bigramas, analizar correlaciones semánticas y realizar análisis de sentimiento.

---

### 💻 Scripts incluidos
| Archivo | Función |
|--------|--------|
| **Text Mining – Don Quijote.R** | Script en R para minería de texto: limpieza, n-gramas, frecuencias, correlaciones y visualizaciones. |

---

## ✨ Objetivos del trabajo según la guía

### 1. 🚀 Proceso ETL (Google Colab)
- Importación del dataset.
- Identificación de tipos de atributos.
- Traducción de encabezados.
- Conversión de variables (ej. `CustomerID` → string).
- Limpieza de valores nulos.
- Documentación detallada y justificación de cada transformación.

### 2. 🧠 Minería de texto (RStudio o Python)
- Generación de bigramas.
- Extracción de términos más frecuentes.
- Análisis de correlaciones entre tokens.
- Visualizaciones y patrones semánticos.
- Interpretación de resultados.

### 3. 🤖 Modelado con Weka
- **Clustering K-Means** con 3, 4 y 8 clusters.
- Eliminación de variable `class` para aprendizaje no supervisado.
- Comparativa usando SSE (Sum of Squared Errors).
- Diagramas de dispersión y análisis final.

### 4. 📈 Regresión con Weka
- Comparación entre regresión lineal y logística.
- Uso de datasets integrados de Weka (`iris`, `cpu`).
- Creación de 2 datasets propios con ≥ 7 instancias cada uno.
- Predicción sobre atributo objetivo `class`.

---

## 🚀 Cómo usar este repositorio

### 🔍 Minería de texto
1. Abrir el script:
Text Mining – Don Quijote.R

markdown
Copiar código
2. Cargar uno de los PDFs incluidos.
3. Ejecutar secciones del script:
   - Limpieza del texto.
   - Tokenización.
   - Bigramas y correlaciones.
   - Visualizaciones.

> Se recomienda instalar librerías: `tidytext`, `tidyverse`, `stringr`, `ggplot2`, `SnowballC`.

### 📊 Análisis de datasets
Los archivos CSV/XLS pueden usarse para:
- ETL en Google Colab.
- Modelado predictivo en R o Python.
- Actividades de clustering y regresión en Weka.

---

## 📦 Requisitos técnicos
- **Google Colab**
- **Weka**
- **RStudio o Python**
- Librerías recomendadas:
  - `tidytext`
  - `tidyverse`
  - `stringr`
  - `ggplot2`
  - `scikit-learn` (Python)
  - `SnowballC`
  - `wordcloud`

---

## 📝 Evidencias sugeridas para el informe final (PDF)
- Capturas del proceso ETL en Colab.
- Resultados y gráficas de minería de texto.
- Tabla comparativa de clustering (3, 4 y 8 clusters).
- Diagramas de dispersión de Weka.
- Resultados de regresión y predicciones.
- Conclusiones de cada fase.
- Referencias en **normas APA**.

---

## ⚠️ Notas importantes
- No compartir contenido con plagio.
- Comentar el código y explicar decisiones.
- Usar datasets propios solo para la sección de regresión.
- Nombrar el archivo final según el formato solicitado por la guía.

--- 

🧠 *Para soporte adicional, puedes extender este repositorio con notebooks, scripts o tableros de visualización.*  
