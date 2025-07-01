---
layout: page
title: " "
---

# Escuela de Invierno: Simulación del Transporte de Contaminantes en Medios Porosos

## Programa

### Día 1: Fundamento Físicos del Transporte en Medios Porosos

* Objetivos
  * Introducir los conceptos físicos que rigen el flujo y transporte en medios porosos.
  * Comprender las ecuaciones que describen flujo subterráneo y transporte de contaminantes.
* Contenidos
  * Presentación general del curso y de los participantes.
  * Conceptos básicos sobre medios porosos.
  * Ley de Darcy.
  * Ecuación de continuidad para flujo subterráneo.
  * Ley de Fick.
  * Ecuación de advección-difusión

## Día 2: Discretización con Diferencias Finitas

* Objetivos
  * Entender el método de diferencias finitas en 1D.
  * Resolver problemas de flujo y transporte en estado estacionario y transitorio en MATLAB/OCTAVE.
* Contenidos
  * Introducción al método de diferencias finitas.
  * Discretización de la ecuación de flujo en 1D.
  * Discretización de la ecuación de advección-difusión en 1D. Upwinding.

## Día 3: Transporte Reactivo en 1D

* Objetivos
  * Introducir el concepto de reacción en el transporte de contaminantes.
  * Modelar y simular transporte con reacción lineal o de primer orden.
* Contenidos
  * Ecuación de advección-reacción-difusión
  * Discretización con diferencias finitas.
  * Implementación en MATLAB/OCTAVE.

## Día 4: Introducción a MOLE y diferencias miméticas

* Objetivos
  * Comprender la idea detrás de diferencias miméticas.
  * Usar la librería MOLE para simular problemas de 1D.
* Contenidos
  * Introducción a operadores miméticos de Castillo-Grone. Malla escalonada.
  * Introducción e instalación de MOLE.
  * Implementación de flujo subterráneo (1D) en MOLE.
  * Implementación de advección-difusión (1D) en MOLE.
  * Implementación de advección-reacción-difusión (1D) en MOLE.

## Dia 5: Tópicos avanzados y extensiones

* Objetivos
  * Simular problemas más realistas con condiciones de frontera variadas y heterogeneidad.
  * Explorar problemas en 2D y plantear extensiones/proyectos.
* Contenidos
  * Condiciones de frontera de tipo Dirichlet, Neumann, mixtas.
  * Inclusión de heterogeneidad espacial: campo de permeabilidad variable.
  * Resolución de problema 2D en MOLE.
  * Brainstorming en grupos: ideas de proyectos que podrían continuar la escuela.

## Recursos

### Bibliografía básica
* Pinder, G. F., & Celia, M. A. (2006). Subsurface hydrology. John Wiley & Sons.
* Bear, J., & Cheng, A. H. D. (2010). Modeling groundwater flow and contaminant transport (Vol. 23, p. 834). Dordrecht: Springer.
* Charbeneau, R. J. (2006). Groundwater hydraulics and pollutant transport. Waveland Press.

### MOLE y diferencias miméticas
* Repositorio de GitHub: https://github.com/csrc-sdsu/mole
* Artículos
  * Corbino et al., (2024). MOLE: Mimetic Operators Library Enhanced. Journal of Open Source Software, 9(99), 6288, https://doi.org/10.21105/joss.06288
  * Castillo, José E., & Miranda, G. F. (2013). Mimetic discretization methods. CRC Press. https://doi.org/10.1201/b14575
  * Corbino, J., & Castillo, J. E. (2020). High-order mimetic finite-difference operators satisfying the extended Gauss divergence theorem. Computational and Applied Mathematics, 364. https://doi.org/10.1016/j.cam.2019.06.042
  * Dumett, M., & Castillo, J. E. (2023b). Mimetic analogs of vector calculus identities (CSRC2023- 01, submitted for publication). San Diego State University Computational Science Research Center. https://doi.org/10.13140/RG.2.2.26630.14400

### Scripts (A ser añadidos conforme la escuela avanza)

