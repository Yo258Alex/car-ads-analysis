# Aplicación de Análisis Exploratorio de Datos: Venta de Vehículos

Este proyecto consiste en una aplicación web interactiva desarrollada con **Streamlit** para explorar un conjunto de datos sobre anuncios
de venta de coches en los Estados Unidos (`vehicles_us.csv`).

La aplicación está diseñada para ayudar a identificar patrones y relaciones clave en los datos de los vehículos, como la distribución del
kilometraje y la relación entre el precio y el desgaste del motor.

## 🚀 Funcionalidades

La aplicación web proporciona las siguientes herramientas interactivas:

1. **Visualización de la Distribución del Kilometraje:**
   * Al hacer clic en el botón **"Construir histograma"**, la aplicación genera un gráfico interactivo utilizando *Plotly Express* que
      muestra la frecuencia de los vehículos según su lectura en el odómetro (`odometer`).
2. **Análisis de Relación Kilometraje vs. Precio:**
   * Al hacer clic en el botón **"Construir diagrama de dispersión"**, se despliega un gráfico de dispersión que mapea el precio (`price`)
      de los vehículos frente a su kilometraje, permitiendo visualizar cómo influye el uso en el valor de venta.

## 🛠️ Tecnologías Utilizadas

* **Python 3.10**
* **Streamlit** (para la interfaz web interactiva)
* **Pandas** (para la carga y manipulación de datos)
* **Plotly Express** (para la creación de gráficos dinámicos)

## 💻 Instrucciones para Ejecutar Localmente

Si deseas descargar este proyecto y ejecutarlo en tu propia computadora, sigue estos pasos:

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/Yo258Alex/car-ads-analysis.git