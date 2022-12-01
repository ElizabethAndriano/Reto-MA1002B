# Reto-MA1002B
Solución para las Ecuaciones Lotka-Volterra mediante métodos numéricos

## Fase 1: estudio cualitativo de las ecuaciones de Lotka-Volterra
Considerando las ecuaciones de Lotka-Volterra, donde p(t) representa las presas y d(t) los 
depredadores:

$p'(t)=\alpha_1p(t)-\alpha_2p(t)d(t)$

$d'(t)=-\beta_1d(t)+\beta_2p(t)d(t)$

Calcular el número promedio de depredadores y presas.

[Explicación de solución](https://youtu.be/XsF5nrLV-3c)

## Fase 2: aplicación a un caso real, modificaciones de las ecuaciones y solución numérica

Discretización para resolver el sistema con un método $O(h^2)$ de las ecuaciones de Lotka-Volterra con una 
aproximación de primer orden (método de Eulero), tomando en cuenta una limitación en el crecimiento 
de las presas.

[Explicación de solución](https://youtu.be/2v9JRVpImhU)

## Fase 3: Simulación estocástica de un proceso presa-depredador

El código se encuentra disponible en [Fase_3](Fase_3.ipynb)
