# 📊 Proyecto Big Data - Grupo 4

Este proyecto implementa un **pipeline de preprocesamiento para detección de fraude** usando Python y librerías de ciencia de datos.  
Integrantes: Carolina Salas Moreno , Deykel Bernard Salazar, Esteban Ramírez Montero y Kristhel Porras Mata

## ⚙️ Características principales
- Muestreo estratificado opcional para datasets grandes.  
- Optimización de memoria convirtiendo `object` a `category`.  
- Limpieza y normalización de variables numéricas y target a formato binario (0/1).  
- Feature engineering:
  - Estadísticas por emisor (media, conteo, desviación).  
  - Z-score y coeficiente de variación de montos.  
  - Diversidad de dispositivos y flags de múltiples dispositivos.  
  - Rasgos temporales + codificación cíclica.  
- Procesamiento categórico:
  - One-Hot Encoding para baja cardinalidad.  
  - Frequency Encoding para alta cardinalidad.  
- Escalado con `RobustScaler` resistente a outliers.  
- Balanceo de clases con undersampling o class weights.  
- Artefactos guardados para reproducibilidad.

## 🛠️ Tecnologías
- Python (Pandas, NumPy, SciPy)  
- Scikit-learn  
- Imbalanced-learn  
- Databricks / Delta Lake (para integración big data)  
- Power BI (visualización de métricas)

## 🚀 Ejecución
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/KrisSo03/Proyecto_Big-Data_Grupo-4.git
   cd Proyecto_Big-Data_Grupo-4
