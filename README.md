

<!-- README.md is generated from README.Rmd. Please edit that file -->

## Taller de Inferencia Causal en R

### Diapositivas

- [00
  Introducción](https://causal-inference-r-workshop.netlify.app/00-intro.html)
- [01 Modelo Causal: Whole
  Game](https://causal-inference-r-workshop.netlify.app/01-causal_modeling_whole_game.html)
- [02 Cuando los métodos estándar
  funcionan](https://causal-inference-r-workshop.netlify.app/02-when-standard-methods-succeed.html)
- [03 Inferencia Causal con `group_by` y
  `summarise`](https://causal-inference-r-workshop.netlify.app/03-causal-inference-with-group-by-and-summarise.html)
- [04 Diagramas
  Causales](https://causal-inference-r-workshop.netlify.app/04-dags.html)
- [05 La Inferencia Causal no es solo un Problema de
  Estadística](https://causal-inference-r-workshop.netlify.app/05-quartets.html)
- [06 Introducción a las Puntuaciones de
  Propensión](https://causal-inference-r-workshop.netlify.app/06-pscores.html)
- [07 Usando las Puntuaciones de
  Propensión](https://causal-inference-r-workshop.netlify.app/07-using-pscores.html)
- [08 Verificando las Puntuaciones de
  Propensión](https://causal-inference-r-workshop.netlify.app/08-pscore-diagnostics.html)
- [09 Ajustando el Modelo de
  Resultado](https://causal-inference-r-workshop.netlify.app/09-outcome-model.html)
- [10 Exposiciones Continuas y
  G-Computación](https://causal-inference-r-workshop.netlify.app/10-continuous-g-comp.html)
- [11 Análisis de Sensibilidad de Puntos de
  Inflexión](https://causal-inference-r-workshop.netlify.app/11-tipr.html)
- [12 Whole Game (Tu
  turno)](https://causal-inference-r-workshop.netlify.app/12-whole_game-2.html)
- [13 Bonus: Sesgo de
  Selección](https://causal-inference-r-workshop.netlify.app/13-bonus-selection-bias.html)
- [14 Bonus: Exposiciones Continuas con Puntuaciones de
  Propensión](https://causal-inference-r-workshop.netlify.app/14-bonus-continuous-pscores.html)

### Instalación de materiales localmente

Proporcionaremos un enlace a un espacio de Posit Cloud para el taller.
Sin embargo, recomendamos instalar los materiales localmente para tener
dos opciones.

Para instalar los paquetes requeridos y los materiales del curso,
tenemos un paquete R llamado
{[causalworkshop](https://github.com/malcolmbarrett/causalworkshop)}
para ayudarte a hacerlo. Puedes instalar
{[causalworkshop](https://github.com/malcolmbarrett/causalworkshop)}
desde GitHub con:

``` r
install.packages("remotes")
remotes::install_github("malcolmbarrett/causalworkshop")
```

Una vez que hayas instalado el paquete, instala el taller con

``` r
causalworkshop::install_workshop()
```

Por defecto, este paquete descarga los materiales a un lugar conspicuo
como tu Escritorio. También puedes decirle a `install_workshop()`
exactamente dónde poner los materiales:

``` r
causalworkshop::install_workshop("un/ruta/en/tu/computadora")
```

------------------------------------------------------------------------

## Créditos

Este taller fue originalmente desarrollado por **Malcolm Barrett**,
**Lucy D’Agostino McGowan**, y **Travis Gerke**.

Esta versión en español fue adaptada por **Miguel Angel Luque
Fernandez**, Departamento de Estadística e Investigación Operativa,
Universidad de Granada (UGR).

Créditos al autor original: Malcolm Barrett et al.
