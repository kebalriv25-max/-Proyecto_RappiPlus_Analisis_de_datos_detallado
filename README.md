# Proyecto RappiPlus: de datos a decisiones de negocio
El objetivo de este proyecto es evaluar el desempeño del servicio RappiPlus para apoyar decisiones de negocio basadas en datos

## Se trabajara con el siguiente dataset: 
- **rappiplus_orders_raw.csv** → Cada fila representa un pedido realizado en la plataforma.
- **rappiplus_catalog.csv** → Cada fila representa un producto disponible en la plataforma..
- **rappiplus_marketing_spend.csv** → Cada fila representa una inversión en marketing realizada en un país y canal específico.
- **events / users / user_activity (SQL)** → Comportamiento del usuario dentro de la plataforma.
- **datasets/experiment_checkout_ui.csv** → Cada fila representa la participación de un usuario en un experimento (A/B testing).

## 📂 Contenido del repositorio

- `Proyecto_Datos_RappiPlus.ipynb`
  → Notebook principal con la comparación de gastos promedio, tasas de conversión, análisis de tráfico, visualizaciones y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `Proyecto_Datos_RappiPlus.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (Todos se encuentran disponibles)

## 🧠 Objetivo del análisis
se realizara lo siguiente:
- 🔍 Evaluar si podemos confiar en los datos (calidad de datos en Python)
- 💰 Analizar si el negocio es rentable (revenue, costos y profit)
- 🛒 Entender dónde se pierden los usuarios (funnel de conversión)
- 🔁 Evaluar si los usuarios regresan (retención por cohortes)
- 🧪 Validar si los cambios generan impacto (test estadístico)
- 📊 Comunicar los resultados (dashboard en BI)

## 📊 Visualizaciones de Power BI

- **Resumen ejecutivo**
  
<img width="1636" height="946" alt="image" src="https://github.com/user-attachments/assets/92d496fe-b9df-4497-a6df-932b3ed022ad" />

- **Análisis de detalle por producto**
  
<img width="1624" height="936" alt="image" src="https://github.com/user-attachments/assets/1b684cd2-87cd-4222-b6f0-8eb00b32fa9e" />

