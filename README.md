# talleR

Curso introductorio en R para presentarlo en un día.

Ocasiones en las que ha sido empleado:

- *Introducción exprés a R - Curso en EDAN*, 15/07/2025, `2025EDAN07`.

## Instalación

1. Descarga este proyecto (como ZIP o usando Git/GitHub Desktop)
2. Abre el archivo `taller.Rproj`, que debería abrirse automáticamente con RStudio
3. Lanza la orden `renv::install()`
4. Abre el archivo `programando_en_R/01-Programacion_R.Rmd` y pulsa en el botón de `Knit`, arriba a la izquierda, o bien pulsa `Ctrl + Shift + K`. 

Si obtienes una presentación como salida, entonces la instalación ha sido correcta. Si no es el caso, vuelve al paso 3 y asegúrate de que todos los paquetes están correctamente instalados.

## Contenido

Se encuentra separado por carpetas, todas dentro de la carpeta `contenido/`.

### `programando_en_R/`

- `01-Programacion_R`
  - Comparativa con Matlab y con Python
  - Ejemplos de uso de:
  	- Vectores
  	- Vectores
  	- Operaciones básicas
  	- Funciones
  		- Alcance (*scope*) de una función
  	- Matrices/Tablas
  	- Procesamiento de texto (Cadenas de caracteres)
  	- Condicionales (if, ifelse, ifelseif)
  	- Bucles (for, while)
- `02-R_especifico`
  > **2025EDAN07** - 1 clase o media, pensando en combinarla con lo visto en Estadística/Matemáticas)
	- Instalación de paquetes
	- Funciones summary, glimpse y/o skim
	- Pruebas estadísticas
	- R Markdown

### `tidyverse/`

- Pensado para 4 horas de clase únicamente, empleando un CSV con datos reales
- Objetivos: Repetir y extender lo visto en Calc/Excel
- Clase 1 (2h):
	- [ ] Instalación de paquetes
	- [ ] El operador tubería (`%>%`, o `|>`)
	- [ ] Lectura con `readr`
		- [ ] Lectura avanzada para una variable
	- [ ] Limpieza con `dplyr` y comentar que existe `tidyr`
- Clase 2 (2h):
	- [ ] Manipulación de datos con `dplyr`
	- [ ] Visualización con `ggplot2`
	- [ ] Siguientes pasos en `tidyverse`: `forcats`, `stringr`, `lubridate`

### `modelos_matematicos/`

Este añadido está pensado específicamente para el curso impartido el 15/07/2025 en el Departamento de Ecuaciones Diferenciales y Análisis Numérico (EDAN) de la Universidad de Sevilla, codificado como `2025EDAN07`.

- [ ] Modelos discretos
	- [ ] Puntos de equilibrio
	- [ ] Estabilidad
	- [ ] Visualización
		- [ ] Una condición inicial
		- [ ] Varias condiciones iniciales
- [ ] Modelos continuos
	- [ ] Puntos de equilibrio
	- [ ] Estabilidad
	- [ ] Visualización
		- [ ] Una condición inicial
		- [ ] Varias condiciones iniciales
- [ ] Modelo Lotka-Volterra
	- [ ] Puntos de equilibrio
	- [ ] Estabilidad
	- [ ] Visualización
		- [ ] Una condición inicial
		- [ ] Varias condiciones iniciales
