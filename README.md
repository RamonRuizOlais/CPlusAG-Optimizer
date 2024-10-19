# CPlusAG-Optimizer
“Nonlinear Conjugate Gradient for Smooth Convex Functions” de Sahar Karimi y Stephen Vavasis propone un método llamado C+AG (conjugate plus accelerated gradient) que intenta cerrar la brecha entre el método de gradiente conjugado no lineal (NCG), óptimo para funciones cuadráticas, y el método de gradiente acelerado (AG), óptimo para funciones convexas suaves.

El método de Gradiente Conjugados no lineales (NCG) es ampliamente utilizado para problemas de optimización sin restricciones, sin embargo, en los casos en que es aplicado a funciones convexas suaves sólo satisface límites de complejidad débiles.

Por otro lado, el método del Gradiente Acelerado de Nesterov (AG) es un método óptimo para esta clase de funciones (convexas suaves), pero no es tan eficiente como NCG para funciones cuadráticas:

* Para el caso de las funciones cuadráticas, la decisión más apropiada sería utilizar un método de Gradiente Conjugado, por tanto es claro que existe una brecha en las opciones de los algoritmos de optimización disponibles.

* NCG es la solución óptima para funciones cuadráticas y de hecho demuestra un desempeño bastante apropiado para funciones generales, sin embargo tiene límites de complejidad bastante pobres comparados con AG.

# Referencias

[1]  Nonlinear conjugate gradient for smooth convex
functions. Sahar Karimi, Stephen Vavasis.

https://arxiv.org/pdf/2111.11613
