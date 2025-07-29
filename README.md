# Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes

## 🧾 Descripción General

Este proyecto se enfoca en estudiar las razones detrás de la cancelación de servicios por parte de los clientes de una empresa de telecomunicaciones (conocido como **churn**).  
Utilizando un conjunto de datos real, se analiza el comportamiento de los usuarios para identificar patrones y factores clave que influyen en su decisión de abandonar el servicio.
El objetivo es generar insights que apoyen el diseño de estrategias efectivas para mejorar la retención de clientes.

## 🧱 Estructura del Análisis
Todo el trabajo se encuentra en un notebook interactivo (Google Colab o Jupyter Notebook) con la siguiente estructura:
1. **📌 Introducción:** Presentación del problema y objetivos del análisis.
2. **🧹 Limpieza de Datos:** Carga del dataset, procesamiento y normalización.
3. **🔍 Análisis Exploratorio (EDA):** Visualización y análisis estadístico de las variables.
4. **🧠 Conclusiones:** Principales hallazgos derivados del análisis.
5. **🧭 Recomendaciones:** Estrategias sugeridas basadas en los datos.

## 📂 Dataset Utilizado
El dataset utilizado es `TelecomX_Data.json` y se encuentra disponible en el siguiente enlace:
📎 https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json
Contiene información sobre:
- Servicios contratados por el cliente  
- Tipo de contrato  
- Datos de facturación  
- Indicador de cancelación (`Churn`)


## ⚙️ Requisitos
Este proyecto está diseñado para ser ejecutado en un entorno de cuaderno interactivo como **Google Colab** o **Jupyter Notebook**.Necesitarás tener instalado las siguientes librerías:
*   `pandas`: Para manipulación y análisis de datos.
*   `requests`: Para descargar el archivo JSON desde la URL.
*   `matplotlib`: Para crear visualizaciones estáticas.
*   `seaborn`: Para crear visualizaciones estadísticas más atractivas.
*   `IPython`: Específicamente para la función `display` si utilizas un entorno interactivo como Colab o Jupyter Notebooks.
