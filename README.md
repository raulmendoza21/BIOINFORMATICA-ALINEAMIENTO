# Practica de Bioinformatica - Sesion 03

Autores: Raul Mendoza, Adrian Ojeda\
Asignatura: Bioinformatica (ULPGC)

## Descripcion General

Esta practica se centra en el estudio y aplicacion de alineamientos de
secuencias, tanto de ADN como de proteinas, utilizando Python y la
libreria Biopython. El objetivo principal es comprender los fundamentos
de los algoritmos clasicos de alineamiento, implementarlos manualmente y
compararlos con las herramientas proporcionadas por Biopython.

## Estructura de la Practica

La practica se divide en tres ejercicios principales:

### Ejercicio 1: Alineamiento Global

-   Implementacion desde cero del algoritmo Needleman--Wunsch.
-   Implementacion de un segundo algoritmo propio basado en
    desplazamientos.
-   Comparacion entre ambos utilizando secuencias cortas y aleatorias.

### Ejercicio 2: PairwiseAligner con ADN

-   Uso del modulo PairwiseAligner de Biopython.
-   Alineamientos globales y locales con secuencias aleatorias.
-   Alineamientos utilizando secuencias procedentes de ficheros FASTA
    simulados.
-   Variaciones de parametros: penalizaciones de huecos y modos de
    alineamiento.

### Ejercicio 3: PairwiseAligner con Proteinas

-   Alineamientos de secuencias proteicas usando matrices de
    sustitucion.
-   Comparacion entre BLOSUM62, PAM250 y una matriz personalizada.
-   Discusion sobre como afectan estas matrices a la puntuacion del
    alineamiento.

## Archivos Incluidos

-   Bioinformatica_Sesion03_alineamientos_FIJO2.ipynb: Notebook
    principal con la practica completa.
-   README.md: Este archivo, explicando el contenido y como ejecutar la
    practica.

## Requisitos

-   Python 3.8 o superior
-   Libreria Biopython
-   Libreria pypandoc (solo necesaria para la generacion del README)

## Como Ejecutar la Practica

1.  Descargar el archivo `.ipynb`.

2.  Abrirlo con Jupyter Notebook o JupyterLab.

3.  Ejecutar las celdas en orden para reproducir todos los resultados.

4.  Asegurarse de que Biopython esta instalado. En caso contrario,
    ejecutar:

        pip install biopython

## Objetivo Educativo

Esta practica ayuda a: - Comprender los algoritmos clasicos de
alineamiento. - Ver la diferencia entre implementaciones manuales y
herramientas bioinformaticas reales. - Entender como las penalizaciones
y matrices de sustitucion afectan a los alineamientos.
