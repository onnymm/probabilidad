# Matemáticas para Data Science: Probabilidad
Proyecto y apuntes del curso en Platzi

En este proyecto se encuentran los apuntes, aportaciones personales y explicaciones del curso de Platzi, además de ejemplos llevados a código de Python para demostrar algorítmicamente el funcionamiento de los conceptos vistos.

Se recomienda estudiar el contenido de este repositorio en [VSCode](https://code.visualstudio.com/). Los pasos para descargar este repositorio e instalar las dependencias requeridas para su ejecución (En caso de querer reejecutar el código) se listan a continuación:

- Abre una terminal y ubícate en la carpeta en donde deseas instalar este repositorio.

**Nota:** Utiliza los comandos listados a continuación si requieres saber o recordar cómo navegar por medio de la terminal:

>   - `pwd` te ayuda a saber la ubicación en la que te encuentras.
>   - `ls` lista todas las carpetas que se encuentran en tu ubicación actual.
>   - `cd mi_carpeta` te posiciona dentro de la carpeta a la que quieras acceder.
>   - `cd ..` te lleva de regreso a la carpeta padre.

- Comienza actualizando pip:

```bash
python -m pip install --upgrade pip
```

- Instala este repositorio:

```bash
git clone git@github.com:onnymm/probabilidad.git
```

- Una vez instalado el repositorio puedes instalar las dependencias:

```bash
pip install -r .\requirements.txt
```

Y listo. Puedes proceder a revisar e interactuar con el repositorio.

Hecho con ❤ por [@onnymm](https://github.com/onnymm).

## Resumen de contenido

### 00 | [¿Qué es la probabilidad?](00_que_es_la_probabilidad.ipynb)
En esta lección se explica qué es la probabilidad y los axiomas de ésta. Se explican los conceptos más básicos y fundamentales que componen a una probabilidad y cuáles son las reglas que ésta debe seguir para su correcta representación.

### 01 | [Matemáticas en Machine Learning](01_matematicas_en_machine_learning.ipynb)
En esta lección se explica el uso de la probabilidad en modelos de Machine Learning usando un ejemplo de un modelo de clasificación de documentos de texto en categorías que describen el tema de éstos además de la inevitable imperfección que los modelos de Machine Learning tienen por el hecho de simplificar la realidad a sólo unas variables específicas para replicar un escenario del mundo real, la arquitectura de estos modelos y las herramientas de medición que por naturaleza siempre tendrán, por más pequeño o grande que sea, un margen de error.

### 02 | [Tipos de probabilidad](02_tipos_de_probabilidad.ipynb)
En esta lección se explican los tipos de probabilidad conjunta, condicional y marginal y la relación que tienen entre sí usando un DataFrame de Pandas y estilización mapeada por las condiciones utilizadas en los ejemplos para tener una explicación visual que ayude a entender qué está sucediendo. Siéntete en la libertad de explorar y manipular el código si te interesa saber cómo funciona la estilización con Pandas.

### 03 | [Ejemplos de cálculo de probabilidad](03_ejemplos_de_calculo_de_probabilidad.ipynb)
En esta lección se muestran ejemplos básicos de cálculo de probabilidad junto con ejemplos usando una clase sencilla con Python en donde se abstraen los conceptos de cálculo de probabilidad y se hacen las demostraciones de los ejemplos junto con las ejecuciones del código. Siéntete en la libertad de explorar y manipular el código si te interesa saber cómo funciona la clase de Python que desarrollé para la lección.