# 📊 Análisis de Abandono Escolar en Media Superior (México)

Este repositorio contiene un análisis exploratorio de datos sobre el abandono escolar en la educación media superior en México. El proyecto fue desarrollado como parte de un reto de ciencia de datos, con el objetivo de identificar patrones por estado, género, tipo de escuela y localidad, utilizando Python, Jupyter Notebook y visualización de datos.

---

## 🎯 Objetivo

Responder a las siguientes preguntas clave:

- ¿En qué estados hay más abandono escolar?
- ¿Cuál es la diferencia entre hombres y mujeres?
- ¿Influye el tipo de escuela o la localidad?

---

## 🧠 Lo que aprendí

- Limpieza de datos reales con inconsistencias y outliers
- Cálculo e interpretación de tasas de abandono
- Agrupación y análisis por variables categóricas (estado, género, tipo de escuela)
- Visualización con `seaborn` y `matplotlib`
- Extracción de conclusiones accionables a partir de datos educativos

---

## 🛠️ Tecnologías utilizadas

- Python 3.10
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 📝 Descripción General del Reto

El reto consistió en analizar datos del sistema educativo nacional para detectar los factores que inciden en el abandono escolar. Durante el proceso se limpiaron más de 20,000 registros, se identificaron inconsistencias en tasas fuera de rango, y se calculó la tasa de abandono por entidad federativa, sexo y tipo de plantel.

Las decisiones tomadas incluyeron:

- Eliminar filas con egresados mayores a alumnos
- Calcular la tasa de abandono como: `1 - (egresados / alumnos)`
- Mapear entidades con nombres legibles
- Generar visualizaciones comparativas y top rankings

---

## 📌 Principales hallazgos

- **Estados con mayor abandono**: Tlaxcala (78.8%), Baja California Sur (77.7%), Baja California (77.0%)
- **Diferencia de género**: Las mujeres presentan una tasa promedio de abandono ligeramente superior a los hombres
- **Tipo de plantel**: Planteles con ciertos tipos de gestión muestran mayor tasa de abandono

---

## 🚀 Cómo ejecutar el análisis

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/abandono-escolar-media-superior.git

2. Abre el archivo notebook.ipynb en Google Colab y carga el dataset

3. Ejecuta las celdas para reproducir los resultados.

---

## 📊 Visualización interactiva en Tableau

¡Explora este proyecto de visualización de datos en Tableau Public! 🚀

Haz clic aquí para verlo en acción 👉 [**Abrir Dashboard en Tableau**](https://public.tableau.com/views/AbandonoEscolar/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
