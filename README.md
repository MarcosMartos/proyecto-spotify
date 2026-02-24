# 🎧 Spotify Data Analysis Project

Este proyecto personal utiliza la librería **Pandas** para procesar y analizar el historial de reproducción extendido de Spotify. El objetivo es transformar datos crudos en formato JSON en visualizaciones comprensibles sobre hábitos musicales.

---

## 🚀 Funcionalidades
El script realiza un proceso completo de análisis de datos:
1.  **Extracción**: Carga de archivos JSON nativos de Spotify.
2.  **Limpieza**: Filtrado de columnas innecesarias y eliminación de registros nulos (anuncios o tracks sin nombre).
3.  **Transformación**: 
    * Renombrado de campos técnicos a nombres amigables.
    * Conversión de *timestamps* a objetos `datetime`.
    * Creación de nuevas dimensiones: Año, Mes, Día de la Semana y Hora.
4.  **Visualización**: Generación de gráficos estadísticos con **Seaborn** y **Matplotlib**.

---

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.x
* **Librerías principales:**
    * `pandas`: Para la manipulación de DataFrames.
    * `matplotlib.pyplot`: Para la estructura de los gráficos.
    * `seaborn`: Para el diseño y estilo visual de los datos.

---

## 📊 Visualizaciones Incluidas
El proyecto genera automáticamente tres métricas visuales:
* **Top 10 Artistas:** Gráfico de barras horizontales con paleta *mako*.
* **Distribución Horaria:** Histograma con curva KDE para identificar picos de escucha durante el día.
* **Actividad Mensual:** Comparativa de consumo musical a lo largo de los meses del año.

---

## 📁 Estructura de Archivos
Para que el script funcione correctamente, la estructura debe ser la siguiente:
```text
.
├── data/
│   └── Streaming_History_Audio_2022-2026_0.json  # Datos de entrada
├── spotify_analysis.py                            # Script de Python
└── README.md                                      # Documentación
```

## ⚙️ Instalación y Uso
Clona este repositorio o descarga el script.

Instala las dependencias necesarias:

```text
Bash
pip install pandas matplotlib seaborn
```
Ejecuta el análisis:


```text
bash
python prueba.ipynb
```

## 📝 Notas de Implementación
Se utiliza un bloque try-except para capturar errores de carga de archivos o de formato.

Se aplica el método de Method Chaining para optimizar la selección y renombrado de columnas.

El análisis de meses está ordenado cronológicamente para evitar desorden alfabético en el eje X.

Autor: Marcos

Estudiante de Ingeniería en Sistemas
