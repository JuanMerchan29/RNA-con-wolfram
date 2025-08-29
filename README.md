# Redes Neuronales 

## Introducción

Este proyecto muestra cómo implementar las compuertas lógicas **AND**, **OR** y **XOR** mediante **redes neuronales artificiales (RNA)** en Wolfram Language. Se busca entender cómo una red puede aprender reglas lógicas simples y por qué algunas requieren mayor complejidad.


## Conceptos básicos

* **Red neuronal artificial (RNA):** modelo inspirado en el cerebro que recibe entradas, aplica pesos y genera una salida.
* **Linealmente separable:** problemas como AND y OR se pueden resolver con una sola neurona.
* **No linealmente separable:** problemas como XOR requieren una capa oculta para ser resueltos.


## Implementación

* **AND:** una sola neurona basta, ya que la salida solo es 1 cuando ambas entradas son 1.
* **OR:** también se resuelve con una sola neurona, la salida es 1 cuando al menos una entrada lo es.
* **XOR:** requiere al menos una capa oculta, ya que no puede resolverse con una frontera lineal.

En el repositorio se incluyen los notebooks con las implementaciones para cada compuerta.


## Conclusión

* AND y OR son fáciles de aprender para la red porque son problemas lineales.
* XOR necesita mayor complejidad (capa oculta).
* Con este ejercicio se demuestra cómo las RNA pueden modelar tanto problemas simples como no lineales en Wolfram Language.
