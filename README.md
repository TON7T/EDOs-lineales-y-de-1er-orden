# EDOs Lineales y de 1er Orden

Este repositorio contiene un **programa para trabajar con sistemas de ecuaciones diferenciales ordinarias (EDOs)** de 1er orden que pueden ser representados como una **matriz 2x2**.

## Descripción

El programa resuelve sistemas de ecuaciones diferenciales ordinarias de la forma:

$$
x' = a \cdot x + b \cdot y
$$

$$
y' = c \cdot x + d \cdot y
$$

Donde **a**, **b**, **c**, y **d** son **constantes**.

Este programa permite:
- Calcular las soluciones \(x(t)\) y \(y(t)\).
- Generar el **diagrama de fase**.
- Graficar las **trayectorias** en función de las condiciones iniciales.

### ¿Cómo funciona?

El programa utiliza los **valores y vectores propios** de la matriz asociada al sistema de ecuaciones. Dependiendo de los valores propios:
- **Reales y distintos**,
- **Reales y repetidos**, o
- **Complejos**

Las soluciones se calculan de diferentes maneras.

## Referencias

Para profundizar más sobre cómo se resuelven estos sistemas de EDOs, puedes consultar las siguientes fuentes:

- Hoffman, K., & Kunze, R. (1971). Linear Algebra. Prentice-Hall.
- Robinson, J. (2004). An Introduction to Ordinary Differential Equations. Cambridge University Press.

---

¡Esperamos que este programa te sea útil para resolver sistemas de ecuaciones diferenciales ordinarias de 1er orden! 🚀
