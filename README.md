# proyecto_integrado_2
Modelo de Examen Final Tipo 2 - Este proyecto Integra conocimientos de Procesador de Texto, Planillas de calculo,, Github, Colab, Publicacion.

# Propuesta de examen
**Objetivo:**
* Crear archivos y aplicar formatos necesarios con aplicaciones google.
* Generar nuevos datos con analisis estadístico en colab
* Guardar en Github
* Publicar en netlify

---

# Análisis de la Educación Argentina - Estudios de Prueba

Este proyecto analiza la educación argentina y contrasta con la cantidad de faltas a horas aulicas.

# Estructura del Proyecto

- `Educacion_Argentina.ipynb`: Notebook de Jupyter con el análisis

- ## 1. Utilizando Write for me en ChatGPT

Puedes ver el Informe escrito en: [[Informe Estadístico sobre la Educación en Argentina](https://chatgpt.com/share/6733b30c-47ec-8002-8835-f98cbf4965ad)]

## 4. Instrucciones para implementación
### En Gitub, crea un repositorio llamado proyecto_integrado_2
   a. Con descripción: Modelo de Examen Final Tipo 2 - Este proyecto Integra conocimientos de Procesador de Texto, Planillas de calculo,, Github, Colab, Publicacion. 
   b. Tenga README.md y licencia MIT
### Pasos iniciales con Google:
1. Tener abierto su usuario de google
2. Abre colab y crea un cuaderno siguiendo las instrucciones solicitadas:
   a. Solicita a prompt Gemeni que armae un dataframe de al menos 100 filas con datos random con  apellido y nombre, nro_dni, materias de educacion nivel secundario de la argentina que contenga las siguientes columnas: materia escolar, nota 1er Trimestre, nota 2do Trimestre, nota 3er Trimestre, Faltas a clases.
   b. Solicita a prompt Gemini: Armar grafico de barras con Promedio general de cada materia, ordenados de mayor a menor, agregar las faltas como valor constrastable en dos ejes. Agregar las leyendas que ayuden a la interpretación.
   c. Descargar la tabla creada a tu pc local, con extension csv `df.to_csv("datos_alumnos.csv", index=False)`
4. Guarda la notebook con el nombre Educacion_Argentina.ipynb en tu repositorio
### Con "Write for me" incluido en ChatGPT
1. Levantar el archivo "datos_alumnos.csv" y solicitar: `Utiliza estos datos de prueba para generar un informe sobre Educación de Argentina que no supere las 5 paginas, armando una tabla estadistica descriptiva, incluye referencias.`
2. Dentro del Repositorio de Github, en el README agregar:
  a. ## 1. Utilizando Write for me en ChatGPT
            Puedes ver el Informe escrito en: `[[Informe Estadístico sobre la Educación en Argentina](AQUI AGREGA LA DIRECCION COMPARTIDA DE WRITE FOR ME)]`
