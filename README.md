## Análisis del dataset "Mating Crosses of chickens"

---

### 👥 Equipo 

| Nombre | Usuario GitHub |
|--------|:---------------:|
| Reyes Ramírez Mónica | [@mreyes](https://github.com/MonykRey) |
| Pineda Morán Natalie Berenice | [@npineda](https://github.com/nataliebpm) |

---

### 📋 Información del Curso

| Datos | Información |
|-------|:---------:|
| 📅 **Fecha** | 30 Junio 2026 |
| 📚 **Curso** | Code & Data Bootcamp: Git, Bash y R |
| 🏫 **Institución** | *ENESJ* |

---


## Introducción

Este proyecto buscar aplicar los conocimientos adquiridos durante el curso mediante el análisis del dataset Mating Crosses of Chickens disponible en R.

A través de cinco preguntas clave, se exploran las herramientas estadísticas y de manipulación de datos que ofrece el Software, con el objetivo de extraer conclusiones significativas a partir de los datos de cruzamiento entre individuos de distintas líneas genéticas de pollos.

- ***Enlace al reporte renderizado***: https://monykrey.github.io/Proyecto_final_bootcamp/

- ***Enlace a la presentacion del equipo***: 

---

## Pipeline

1. Descarga de datos

	a) Instalar el paquete `agridat`
	
	b) Buscar el Dataset de `becker.chicken`
	
2. Descripción de los datos

	a) Explorar el Dataset y relacionarlo con el objetivo del experimento 
	
	b) Obtener las dimensiones, estadísticas de resumen y tipo de datos
	
	c) Limpieza  y conversión de datos
	
	d) Guardar el dataset en un vector. 

3. Preguntas

	a) ¿Cuánto varía el peso dentro de una misma cruce?
	
	b) ¿Qué porcentaje de la variación total es ambiental vs genética?
	
	c) ¿Qué machos o hembras son mejores reproductores basándose en el peso de su progenie?
	
	d) ¿Se puede predecir el peso de nuevas cruzas a partir de los datos existentes?
	
	e) ¿El efecto de un macho es el mismo (consistente) sin importar con qué hembra se cruce, o depende de la combinación específica (macho x hembra)?

### 📁 Estructura del Repositorio en GitHub

- `scripts`: archivo de R con el código para el análisis

- `figures`: imagenes/gráficas generadas durante el análisis

- `README.md` 

- `Datos/Raw` : matrices de datos utilizadas para el análisis (datos crudos), en formato csv y xlsx

- `index.html`: reporte renderizado en formato html

- `Proyecto_final_bootcamp.Rproj`: código interno del Rproject

- `Final_Report_presentacion.qmd`: presentación en qmd

- `Final_Report_presentacion.html`: reporte renderizado de la presentación


## 📦 Requisitos y Dependencias

### Software

| Herramienta | Versión | Uso |
|:-------------:|:---------:|:-----:|
| R | 2026.01.1+403 | Análisis estadístico |

### Librerías

| Herramienta | Versión | Uso |
|:-------------:|:---------:|:-----:|
| agridat | - | Dataset |
| lattice | - | Gráficos multivariados |
| dplyr | - | Manipulación y transformación de datos |
| nlme | - |  Ajustar y comparar modelos de efectos mixtos |
| ggplot2 | - | Visualización de datos |

## 📚 Referencias

- Walter A. Becker (1984). Manual of Quantitative Genetics, 4th ed. Page 83.

- Kevin Wright (2025). agridat: Agricultural Datasets. R package version
  1.26. https://CRAN.R-project.org/package=agridat
  
