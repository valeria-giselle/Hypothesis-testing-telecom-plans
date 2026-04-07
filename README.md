🌐 **Lenguaje:**  
[English version](README_EN.md)

# 📊 Análisis de hipótesis: Planes de Telefonía Megaline

## 📌 Descripción del proyecto
El objetivo de este proyecto es analizar el comportamiento de los usuarios de la empresa de telefonía Megaline y evaluar, mediante pruebas de hipótesis estadísticas, si existen diferencias significativas en el uso y los ingresos generados por los distintos planes de telefonía.

El análisis se enfoca en el impacto del tipo de plan (*Surf* y *Ultimate*) sobre el consumo de llamadas, datos de internet y los ingresos mensuales, con el fin de apoyar la toma de decisiones de negocio.

## 🎯 Objetivos
- Analizar patrones de uso de llamadas e internet por tipo de plan.
- Evaluar diferencias en los ingresos promedio entre planes.
- Identificar efectos estacionales en el comportamiento de los usuarios.
- Aplicar pruebas de hipótesis para respaldar decisiones estratégicas.

## 📁 Datos utilizados
El proyecto utiliza múltiples conjuntos de datos proporcionados por Megaline, que incluyen:
- Información de usuarios
- Registros de llamadas
- Mensajes de texto
- Uso de internet
- Detalles de los planes tarifarios

## 📂 Estructura del repositorio
- `datasets/` → Datasets usados en el análisis
- `notebooks/` → Análisis en Jupyter Notebook
- `README.md` → Descripción del proyecto en español
- `README_EN.md` → Descripción del proyecto en inglés
- `requirements.txt` → Dependencias del proyecto

## 🧪 Metodología
- Limpieza y preparación de datos.
- Agregación de métricas mensuales por usuario.
- Análisis exploratorio de datos (EDA).
- Formulación de hipótesis nula y alternativa.
- Aplicación de pruebas t de Student.
- Interpretación de resultados desde una perspectiva de negocio.

## 🛠️ Tecnologías utilizadas
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn

## 📊 Visualizaciones clave
<img width="844" height="544" alt="image" src="https://github.com/user-attachments/assets/40437e4f-ba53-4efd-b7cd-765e1b52dc6c" />

<img width="579" height="499" alt="image" src="https://github.com/user-attachments/assets/3164ab49-9b54-48c2-bd20-9f6668eedb52" />

<img width="586" height="502" alt="image" src="https://github.com/user-attachments/assets/0aa2c705-0e66-48d9-8d48-c2986ee351e9" />

## 📈 Resultados clave
- Se identificaron diferencias claras en los patrones de uso entre los planes.
- El plan *Ultimate* mostró un consumo más intensivo y estable.
- El plan *Surf* presentó mayor variabilidad en ingresos y comportamiento.
- Se observaron efectos estacionales relevantes en llamadas y consumo de datos.

## 🧠 Conclusión
El análisis del comportamiento de los usuarios de los planes Surf y Ultimate permitió identificar diferencias claras en patrones de uso, consumo de datos e ingresos, así como efectos estacionales relevantes a lo largo del año.

En términos de llamadas, se observó un incremento progresivo en la duración promedio, con picos durante los meses de verano y a finales de año. El plan Surf se asocia principalmente con usuarios de menor duración de llamadas, mientras que Ultimate concentra a usuarios con un uso más intensivo, aunque con una base más reducida.

Respecto al consumo de datos, los usuarios del plan Ultimate presentan un consumo significativamente mayor y más variable, alcanzando volúmenes elevados en ciertos meses. En contraste, los usuarios del plan Surf muestran un consumo más moderado y concentrado en rangos medios.

El análisis de ingresos reveló que el plan Ultimate genera ingresos más estables y predecibles, mientras que Surf presenta una mayor dispersión, reflejando una base de usuarios más heterogénea en términos de gasto.

En conjunto, los resultados muestran que el tipo de plan y la estacionalidad influyen de manera significativa en el comportamiento de los usuarios. El plan Ultimate resulta más rentable y consistente, mientras que Surf ofrece volumen pero con mayor variabilidad.

**Recomendaciones**

- Ajustar las estrategias de marketing considerando los picos estacionales de uso.

- Evaluar el diseño de planes híbridos que combinen flexibilidad y alto consumo para maximizar ingresos y satisfacción del cliente.

- Utilizar pruebas estadísticas como base para decisiones de precios y segmentación de usuarios.

