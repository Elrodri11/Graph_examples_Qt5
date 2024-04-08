# Graph Visualization Tool

Este es un programa que permite visualizar grafos dirigidos utilizando Qt y C++.

## Requisitos

- Qt 5 o superior
- C++11 o superior

## Cómo usar

1. Clona o descarga este repositorio.
2. Abre el proyecto en tu entorno de desarrollo preferido.
3. Ejecuta el programa.
4. Ingresa el grafo en el formato especificado en la sección "Formato de entrada".
5. Haz clic en el botón "Generate" para generar la visualización del grafo.

## Formato de entrada

El grafo se ingresa utilizando un formato de lista de adyacencia, donde cada línea representa una arista en el grafo. El formato es el siguiente:

A -- 2 --> B
B -- 3 --> C
C -- 4 --> A
A -- 5 --> D
A -- 5 --> A


Esto representa un grafo con cinco nodos (A, B, C, D) y cinco aristas con pesos (2, 3, 4, 5, 5) respectivamente. Las aristas están dirigidas desde el nodo origen hacia el nodo destino.

## Ejemplo

Un ejemplo de un grafo con seis estados podría ser:

A -- 1 --> B
B -- 2 --> C
C -- 3 --> D
D -- 4 --> E
E -- 5 --> F
F -- 6 --> A


Esto representa un grafo con seis nodos (A, B, C, D, E, F) y seis aristas con pesos (1, 2, 3, 4, 5, 6) respectivamente.

