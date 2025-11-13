🌟 Alura Store — Data Analysis Project

📊 Análisis completo de ventas para ayudar al Sr. Juan a decidir qué tienda debe vender.

🛍️ Descripción del Proyecto

Este proyecto forma parte del desafío Alura Store, donde se analizan los datos de ventas de 4 tiendas distintas para identificar cuál presenta peor rendimiento y debería ser vendida por el Sr. Juan.

El análisis integra:

📈 Ingresos totales por tienda

🏷️ Categorías más populares

⭐ Promedio de calificaciones de los clientes

🛒 Productos más y menos vendidos

🚚 Costo promedio del envío

🌍 Distribución geográfica de ventas

🎯 Objetivo Principal

Ayudar al Sr. Juan a tomar una decisión inteligente basada en datos, identificando la tienda con desempeño más débil.

🧰 Tecnologías Utilizadas
Tecnología	Uso
🐍 Python	Análisis de datos
🧮 Pandas	Manipulación de datos
📊 Matplotlib	Visualizaciones
🌈 Seaborn	Gráficos avanzados
🗺️ Folium / Scatter Maps	Mapas geográficos
🌐 Streamlit	Interfaz web (opcional)
📁 Estructura del Proyecto
alura-store-analisis/
│── analysis.ipynb       # Notebook principal con el análisis
│── app.py               # Aplicación web (opcional)
│── store1.csv
│── store2.csv
│── store3.csv
│── store4.csv
│── README.md            # Este documento
│── requirements.txt

🚀 Cómo instalar y ejecutar el proyecto
1️⃣ Clonar el repositorio:
git clone https://github.com/tu_usuario/alura-store-analisis.git

2️⃣ Instalar dependencias:
pip install -r requirements.txt

3️⃣ Ejecutar análisis:
jupyter notebook analysis.ipynb

4️⃣ Ejecutar app web (opcional):
streamlit run app.py

📊 Análisis Realizado
💰 1. Ingresos Totales

Se suma la columna Price de cada tienda para determinar cuál genera más y menos ingresos.

🏷️ 2. Categorías Más Populares

Se cuentan ventas por categoría:
→ Permite identificar las categorías que impulsan las ventas.

⭐ 3. Calificaciones Promedio

Se calcula la satisfacción del cliente por tienda:
→ Tiendas con menor calificación indican problemas en servicio o calidad.

🛒 4. Productos Más y Menos Vendidos

Ranking basado en frecuencia:
→ Refleja tendencias y debilidades comerciales.

🚚 5. Costo Promedio de Envío

Promedio de la columna Shipping:
→ Costos altos pueden afectar ventas.

🌍 6. Análisis Geográfico

Con lat y lon se visualizan patrones de compra:
→ Ayuda a identificar regiones estratégicas o débiles.

📈 Visualizaciones Incluidas

✔ Gráfico de barras: Ingresos por tienda
✔ Pie chart: Distribución por categorías
✔ Histograma: Calificaciones de clientes
✔ Scatter map: Distribución geográfica de ventas
✔ Ranking horizontal: Productos más vendidos

🧠 Conclusión Final

Incluye:

La tienda con menor ingreso

La tienda con peores calificaciones

La tienda con mayores costos de envío

Categorías que no generan ventas significativas

Regiones con menor movimiento comercial

📌 La recomendación final está basada en datos cuantitativos + visualizaciones.

🔮 Posibles Mejoras Futuras

Implementar modelos de predicción de ventas.

Dashboard completamente interactivo con Streamlit.

Clusterización de clientes mediante K-Means.

Automatización para generar reportes PDF.

👨‍💻 Autor

Edwin Lemus
📚 Profesor — 👨‍💻 Desarrollador — 🌱 Ambientalista
Apasionado por el análisis de datos, la tecnología y las ciencias naturales.

⭐ ¿Te gustó este proyecto?

Dale una estrella en GitHub ✨
¡Tu apoyo ayuda a seguir creando proyectos increíbles!