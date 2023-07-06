# Tarea 2: Procesamiento de Datos Masivos (IIC2440)

## Estudiantes

- [Matías Fuentes](https://github.com/matifuentes2)
- [Larry Uribe](https://github.com/larryuc)

## Introducción
Este repositorio documenta el trabajo realizado para la Tarea 2 en el marco del curso Procesamiento de Datos Masivos IIC2440 el primer semestre del 2023. El objetivo es proponer una estrategia general para implementar algoritmos de grafos en un entorno distribuido, ejemplificándola mediante una implementación de [PageRank](https://en.wikipedia.org/wiki/PageRank#:~:text=PageRank%20(PR)%20is%20an%20algorithm,the%20importance%20of%20website%20pages.) y [Single Source Shortest Path (SSSP)](https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/) realizada con las estructuras más simples de [PySpark](https://www.databricks.com/glossary/pyspark).

Puedes encontrar una [explicación de la estrategia general propuesta aquí](https://youtu.be/063bT478T0o).

## Estructura del repositorio

El proyecto tiene la siguiente estructura


- `problema1.ipynb` - Contiene una descripción paso a paso de cómo se implementó PageRank y se ejemplifica su uso con el pequeño grafo entregado en el enunciado. Adicionalmente hacia el final se dejan comentadas las celdas que permiten probar el algoritmo con el grafo [cora](https://paperswithcode.com/dataset/cora). Esa parte se deja comentada ya que tarda mucho en correr sin contar con un cluster.

- `problema2.ipynb` - Contiene una descripción paso a paso de cómo se implementó SSSP y se ejemplifica su uso con un pequeño grafo de juguete inventado por los autores. Adicionalmente hacia el final se dejan comentadas las celdas que permiten probar el algoritmo con el grafo [cora](https://paperswithcode.com/dataset/cora). Esa parte se deja comentada ya que tarda mucho en correr sin contar con un cluster.