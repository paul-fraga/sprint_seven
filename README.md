# 🚗 Análisis Interactivo de Venta de Vehículos

Este proyecto es un panel de control web interactivo diseñado para realizar un Análisis Exploratorio de Datos (EDA) sobre un conjunto de datos de anuncios de venta de coches (`vehicles_us.csv`). 

**🔴 <a href="https://sprint-seven.onrender.com/" target="_blank">Ver la Aplicación en Vivo</a>**

### 🛠️ Herramientas y Tecnologías
* **Lenguaje:** Python
* **Framework Web:** Streamlit
* **Manipulación de Datos:** Pandas
* **Visualización Dinámica:** Plotly (Graph Objects)
* **Despliegue Cloud:** Render

### 💡 Características Principales
La aplicación permite al usuario interactuar directamente con los datos a través de una interfaz gráfica limpia, ofreciendo:
* **Histogramas interactivos:** Para analizar la distribución del kilometraje (odómetro) de los vehículos.
* **Gráficos de dispersión (Scatter plots):** Para visualizar y explorar la relación directa entre el kilometraje y el precio de venta.
* **Controles dinámicos:** Interfaz controlada tanto por botones de acción como por casillas de verificación (checkboxes) para personalizar la visualización al instante.

### 🚀 Cómo ejecutar este proyecto localmente

Si deseas probar la aplicación en tu propio entorno, sigue estos pasos:

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener instaladas las dependencias requeridas. Puedes instalarlas ejecutando:
   ```bash
   pip install pandas plotly streamlit
   ```
3. Ejecuta la aplicación desde la línea de comandos en la carpeta raíz del proyecto:
  ```bash
  streamlit run app.py
   ```
4. Tu navegador abrirá automáticamente la aplicación local.
