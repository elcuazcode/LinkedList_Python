# LinkedList en Python

Este es un ejemplo de una lista enlazada en Python, que consta de la clase Node y la clase LinkedList. La clase Node se utiliza para crear los nodos individuales en la lista enlazada, mientras que la clase LinkedList se utiliza para crear la lista en sí y proporciona los métodos para agregar, eliminar y manipular los nodos.

## Clase Node

La clase Node tiene dos atributos:

- `data`: El valor almacenado en el nodo.
- `next`: El siguiente nodo en la lista.

El método `__init__` se utiliza para inicializar un objeto Node con un valor `data` y un puntero `next` nulo.

## Clase LinkedList

La clase LinkedList tiene un atributo:

- `head`: El primer nodo de la lista.

El método `__init__` se utiliza para inicializar una lista enlazada vacía con una `head` nula.

## Métodos

- `print_list`: Imprime todos los valores de la lista enlazada.
- `append`: Agrega un nuevo nodo al final de la lista enlazada.
- `prepend`: Agrega un nuevo nodo al principio de la lista enlazada.
- `delete_node`: Elimina un nodo específico de la lista enlazada.
- `remove_duplicates`: Elimina nodos duplicados de la lista enlazada.
- `is_palindrome_`: Verifica si la lista enlazada es un palíndromo.

Cada uno de estos métodos se explica en detalle en los comentarios del código.
