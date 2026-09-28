# Prueba de Concepto (PoC) - Machine Learning Predictivo

## 📌 Datos del Proyecto
* **Autor:** Danny Yordano Dulcey Escobedo
* **Programa:** Análisis y Desarrollo de Software (ADSO) - SENA
* **Ficha:** 3235887
* **Sistema de Información:** Ferré Control

## 🚀 Descripción de la Prueba de Concepto
Esta prueba de concepto (PoC) implementa un modelo de Machine Learning basado en **Regresión Lineal** utilizando Python. El objetivo actual del algoritmo es predecir los tiempos de llegada de corredores en una maratón a partir de datos históricos de entrenamiento. 

**Justificación y vinculación al proyecto:**
La viabilidad de esta tecnología está orientada a integrarse a futuro en el sistema **Ferré Control**. El propósito es adaptar esta misma lógica predictiva (Regresión Lineal) para analizar el historial de ventas y estimar cuándo se agotará el stock de un producto específico, optimizando así los tiempos de reabastecimiento de la ferretería.

## 🛠️ Tecnologías y Librerías Utilizadas
- **Lenguaje:** Python
- **Librerías:** 
  - `pandas` (Manipulación y limpieza de datos)
  - `scikit-learn` (Entrenamiento del modelo predictivo)
  - `matplotlib` (Visualización de datos)
  - `numpy` (Operaciones numéricas)
- **Entorno de ejecución:** Google Colab / Jupyter Notebook

## ⚙️ Instrucciones de Ejecución
1. Clonar este repositorio o descargar los archivos directamente.
2. Abrir el entorno de **Google Colab** (https://colab.research.google.com/).
3. Subir el archivo `.ipynb` al entorno.
4. En el panel lateral izquierdo de Colab, subir el archivo `DatosMaratonenCSV.csv`.
5. Ejecutar las celdas en orden (Shift + Enter) para ver el proceso de limpieza, la gráfica de dispersión y la predicción final.

## 🔒 Consideraciones Éticas y de Seguridad
Para la futura implementación en Ferré Control, se garantizará la privacidad de los usuarios y clientes. Los datos financieros y personales serán anonimizados antes de ser procesados por cualquier modelo predictivo, cumpliendo con las normativas de protección de datos.
