
# 🚀 Análisis de percepción ciudadana sobre apps de movilidad en Colombia

## 📌 Descripción general

Este proyecto combina análisis técnico y sensibilidad ciudadana para evaluar la **popularidad**, **funcionalidad** y **percepción emocional** de las principales aplicaciones de movilidad en Colombia: Uber, DiDi, Cabify, inDriver, Easy Taxi y Taxis Libres. Se estudian cinco ciudades clave: **Bogotá**, **Medellín**, **Cali**, **Barranquilla** y **Bucaramanga**, utilizando datos simulados y reales.

---

## 🎯 Objetivo del proyecto

> Analizar la popularidad, funcionalidad y percepción de las apps de movilidad en ciudades colombianas, usando datos simulados y reales, con un enfoque técnico-humanista.

---

## 🧠 ¿Qué incluye el análisis?

### 1. 📥 Reseñas ciudadanas
- Descarga y limpieza de reseñas por ciudad y app.
- Clasificación binaria de sentimientos (positivo/negativo).
- Cálculo de promedio de estrellas y distribución emocional.

### 2. 📊 Estimaciones operativas
- Estimación de usuarios activos (MAU) por ciudad y app.
- Estimación de conductores activos según tipo de app (taxi vs ride-hailing).
- Cálculo de ratios usuarios/conductores como indicador de funcionalidad.

### 3. 💳 Método de pago
- Simulación de proporción de pagos con tarjeta vs efectivo.
- Análisis de brechas digitales y su impacto en la percepción.

### 4. 🎨 Visualizaciones narrativas
- Gráficos comparativos por ciudad y app.
- Distribución de pagos digitales con `swarmplot` y `violinplot`.
- Mapas de calor para detectar patrones urbanos.

---
## 🧰 Tecnologías utilizadas

- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`
- Jupyter Notebook
- Markdown para documentación


---

## 🧪 Script destacado: `estimacion_apps_ciudad.py`

Este script genera estimaciones de usuarios activos (MAU) y conductores por ciudad para distintas apps de movilidad. Utiliza datos simulados de población urbana y flota de taxis como base para distribuir el uso de cada app.

### 🔧 ¿Qué hace?
- Reparte el MAU nacional de cada app proporcionalmente según la población urbana.
- Ajusta la participación en ciudades grandes (+20%) como proxy de mayor penetración.
- Estima el número de conductores activos por ciudad, diferenciando entre apps tipo taxi y ride-hailing.
- Exporta los resultados a `estimacion_apps_ciudad.csv`.
- Genera visualizaciones simples por app para mostrar el MAU estimado por ciudad.


### 📊 Ejemplos de visualizaciones

- ⭐ **Promedio de estrellas por app y ciudad**  
- 📊 **Distribución de calificaciones (1–5 estrellas)**  
- 💳 **Distribución de pagos con tarjeta por ciudad y app**  
- 🔥 **Mapas de calor de adopción digital**

---

### 📌 Conclusiones

- Las apps con mayor adopción de pagos digitales tienden a tener mejor percepción ciudadana.  
- Hay brechas funcionales entre ciudades que podrían reflejar desigualdad en acceso y experiencia.  
- El análisis técnico se complementa con una lectura emocional de las reseñas, revelando frustraciones, confianza y expectativas ciudadanas.
- En muchas ciudades no funcionan todos estas apps , lo que hace que la medicion sea un poco desajustada.
- En algunos graficos se visualiza como las app que se usan menos tienen casi la misma calificación.
- En las ciudades mas grandes como Bogotá , se evidencia el uso mas alto en ciertas App , lo que nos muestra un gran cantidad de comentarios y calificaciones
