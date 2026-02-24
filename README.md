# proyecto-spotify

🎧 Spotify Data Analysis with Pandas
Este proyecto consiste en un pipeline de análisis de datos para procesar el historial de reproducción extendido de Spotify. Utiliza Python para limpiar, transformar y visualizar hábitos musicales a través de diversas métricas temporales y de popularidad.

🚀 Características
ETL (Extract, Transform, Load): Carga de datos directamente desde archivos JSON de Spotify.

Limpieza de Datos: Eliminación de registros incompletos y renombrado de columnas para mejorar la legibilidad.

Feature Engineering: Extracción de componentes temporales (Año, Mes, Día de la semana, Hora) a partir de Timestamps ISO 8601.

Visualización Estadística: \* Top 10 de artistas más escuchados.

Distribución horaria de consumo musical.

Tendencias de actividad por mes.

🛠️ Tecnologías utilizadas
Python 3.x

Pandas: Manipulación y limpieza de estructuras de datos.

Matplotlib: Creación de la base de las figuras.

Seaborn: Visualizaciones estadísticas de alta densidad estética.

📋 Requisitos previos
Para ejecutar este script, asegúrate de tener instaladas las siguientes librerías:

Bash
pip install pandas matplotlib seaborn
📁 Estructura del Proyecto
Plaintext
├── data/
│ └── Streaming_History_Audio_2022-2026_0.json # Tu historial de Spotify
├── main.py # Script principal de análisis
└── README.md # Documentación del proyecto
📊 Visualizaciones Generadas
El script genera automáticamente tres visualizaciones clave:

Top 10 Artistas: Un gráfico de barras que identifica a los artistas con mayor frecuencia de reproducción.

Distribución Horaria: Un histograma con estimación de densidad (KDE) que muestra en qué momentos del día eres más activo.

Actividad Mensual: Un análisis de barras que revela la evolución de tu consumo a lo largo del año calendario.

Desarrollado por Marcos - Estudiante de Ingeniería en Sistemas
