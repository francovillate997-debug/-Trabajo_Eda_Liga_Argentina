
# ⚽ Master_EDA_Futbol_Argentino

Este repositorio contiene el **Análisis Exploratorio de Datos (EDA)** sobre un dataset histórico de resultados de fútbol argentino. El objetivo principal es limpiar, transformar y visualizar los datos para descubrir patrones y tendencias en los resultados de los partidos.

## 📁 Estructura del Repositorio

| Carpeta/Archivo | Descripción |
| :--- | :--- |
| **`data/`** | Dataset original (`results.csv`). |
| **`notebooks/`** | Notebook principal (`eda.ipynb`) con código de limpieza, transformación y visualización. |
| **`README.md`** | Documentación del proyecto, estructura y conclusiones. |
| **`requirements.txt`** | Dependencias de Python necesarias. |

## 🛠️ Entorno de Análisis

Python 3.x con las siguientes librerías:

* **`pandas`**: Manipulación y limpieza de datos.
* **`numpy`**: Operaciones numéricas.
* **`seaborn` / `matplotlib`**: Visualización de datos.

## 🔍 Conclusiones Clave

### 1. Limpieza y Calidad de Datos
* **Renombramiento:** Columnas clave renombradas al español para coherencia.
* **Duplicados:** Eliminadas 2,809 filas duplicadas.
* **Incoherencias:** Valor anómalo `'A'` imputado a 0 goles para análisis numérico.

### 2. Tendencias de Goles
* **Distribución:** La mayoría de los partidos se concentran en un total de **2 o 3 goles** por encuentro.
* **Estabilidad Histórica:** El promedio de goles por partido se ha mantenido notablemente **estable a lo largo de las décadas**, oscilando consistentemente entre 2.5 y 3 goles por partido.

---

### **Instrucciones para Replicar el Análisis**

1.  Clonar el repositorio.
2.  Instalar las dependencias usando `pip install -r requirements.txt`.
3.  Abrir el archivo `notebooks/eda.ipynb` en un entorno Jupyter (VS Code) y ejecutar todas las celdas.