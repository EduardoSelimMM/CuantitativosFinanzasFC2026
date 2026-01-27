# Métodos Cuantitativos en Finanzas
## Semestre: 2026-2
### Del 2 de febrero al 10 de junio de 2026
### Licenciatura en Actuaría

<img src="imagenes/image.gif" align="right" height="250" width="250" hspace="10">

## ⏰ Horario ⏰

+ Lunes a viernes 8:00 a 9:00 hrs.

# 🫰🏻👋🏼 Presentación 🫰🏻👋🏼

**Profesor:** Eduardo Selim Martínez Mayorga (eduardo.selim@ciencias.unam.mx)

**Adjunto:** Luis Enrique Villalón Pineda (lenriquev13@ciencias.unam.mx)

Este es el tercer curso del área de finanzas. Tiene objetivos más claros y ambiciosos que el curso de Mercados Financieros. En este curso se estudian conceptos introductorios de productos financieros derivados: modelos de valuación discretos y continuos de éstos así como una breve introducción a cálculo estocástico. Otro de los ejes temáticos del curso consiste en extender la Teoría de Portafolios que se estudio en el curso de Mercados Financieros; se profundizará en el modelo APT y en los modelos factoriales. También se estudiará una herramienta fundamental para la administración de riesgos financieros: las medidas de riesgos. Se centrará la atención en el Valor en Riesgo y el Tail Value at Risk, i.e. se estudiarán metodologías de estimación de éstos. Finalmente, todo curso que pretenda estudiar metodologías cuantitativas en finanzas, debiese incluir una sección de análisis de series de tiempo; dichos modelos surgen de manera natural en finanzas. Si bien este tema se analiza en el curso de Modelos de Supervivencia y de Series de Tiempo, éste se centrará en algunas aplicaciones financieras.

## 🧑🏻‍🏫 Dinámica de las sesiones 🧑🏻‍🏫
Las clases se llevarán a cabo de manera síncrona de 8:00 a 9:00 de la mañana mediante Google Meet. Toda comunicación e intercambio de archivos se llevará a cabo a través de Google Classroom (allí se distribuirán tareas, mensajes, exámenes, etc). También se dejarán algunas lecturas y videos para reforzar lo visto durante la clase.\\

+ **Requisitos sugeridos:** Mercados Financieros y Valuación de Instrumentos, Inferencia Estadística y Procesos Estocásticos I.\\

# 📊 Temario 📊

## Tema 1. Introducción a portafolios de inversión

+ Cálculo de rendimientos de instrumentos de inversión y carteras.
  + Media y varianza de rendimientos. Efecto de la diversificación sobre la varianza.
  + Distribución de probabilidad de rendimientos de acciones, bonos y carteras.
+ Conjunto factible y la frontera eficiente.
+ El modelo de Markowitz y sus problemas de optimización.
+ El Teorema de dos fondos de inversión.
+ Inclusión de un activo libre de riesgo.
+ El Teorema de un fondo de inversión.
+ Conos $n$-dimensionales. Lema de Farkas y valuación por arbitraje.
+ Medidas de desempeño. Benchmarks, Sharpe, Treynor y Jensen.
+ Modelos factoriales.
  + Modelo de un factor.
    + Estimación paramétrica.
    + Técnica de Blume.
  + Modelos multi-factor.
    + Tipos de modelos multifactor.
    + Ortogonalización en modelos multi-factor.
+ Modelo CAPM.
  + Suposiciones del modelo CAPM.
  + Recta de mercado de capitales y recta característica.
  + Evaluación del modelo CAPM.
+ Modelo APT.
  + Teoría APT.
  + Relación entre los modelos APT y CAPM.
  + Modelo Fama-French.
+ Algunas implementaciones en Python y R.

## Tema 2. Introducción a instrumentos financieros derivados

+ Definiciones y conceptos.
  + Definición de producto financiero derivado.
  + Ejemplos de productos derivados y conceptos asociados.
+ El concepto de arbitraje.
  + Supuesto de no arbitraje y el concepto de precio de no arbitraje. 
+ Definición y conceptos asociados a un contrato forward.
  + Precio de no arbitraje de un forward para varios subyacentes
  + Precio de no arbitraje de un forward en un subyacente que paga dividendos.
+ Opciones y estrategias con opciones. Paridad put-call.
  + Contratos de opciones y estilo de las opciones.
  + Algortimos de valuación con árboles.
  + Algoritmos de árboles binomiales.
  + Modelos con distribución log-normal.
  + La fórmula de Black \& Scholes.
  + Introducción a griegas y delta-hedging.
+ Algunas variaciones de opciones.
  + Opciones Gap, exchange, compuestas, barrera, asiáticas, forward-start, rainbow.
  + Algunas aplicaciones actuariales del concepto de opción.
+ Algunas implementaciones en Python y R.

## Tema 3. Medidas de riesgo

+ Definición de medidas de riesgo
+ Marcos axiomáticos para medidas de riesgo
+ Value-at-Risk
  + Estimaciones del Value-at-Risk
+ Tail Value-at-Risk
  + Estimaciones del Tail Value-at-Risk
+ Expected Shortfall
  + Estimaciones del Expected Shortfall.
+ Intervalos de confianza bootstrap para el VaR y ES.
+ Otras medidas de riesgo.
+ Algunas implementaciones en Python y R.

## Tema 4. Marco teórico para valuación riesgo neutro y opciones americanas

+ Procesos de portafolios en tiempo discreto.
  + Estrategias de inversión auto-financiadas.
  + Equivalencias para auto-financiamiento.
  + Completez y arbitraje en el modelo binomial.
  + El proceso de valor como martingala.
  + Teoremas fundamentales de valuación. Teorema de representación binomial.
  + Cambio de medida en tiempo discreto.
+ Introducción a cálculo estocástico
  + Movimiento Browniano.
  + Integrales estocásticas.
  + Lema de Ito.
  + Ecuaciones diferenciales estocásticas.
+ Procesos de portafolio en tiempo continuo.
  + Ecuaciones diferenciales estocásticas para el precio de acciones.
  + Teorema de Black \& Scholes.
  + Martingalas en tiempo continuo.
  + Teorema de Girsanov y teorema de representación martingala.
  + Valuación neutral al riesgo en tiempo continuo.
  + Heurística en el cambio de medida en tiempo continuo.
  + Heurística de la representación de Feynman-Kac.
+ Especificidades en opciones americanas.
  + Coberturas y tiempos de paro.
  + Ejercicio óptimo.
  + Algunos algoritmos de valuación clásicos (Tema opcional).

## Tema 5. Introducción a modelos de series de tiempo financieras

+ Procesos estacionarios.
+ Descomposiciones tradicionales de series de tiempo.
+ Auto-correlación y auto-correlación parcial
+ Procesos $AR$, $MA$, $ARMA$, $ARIMA$, $FARIMA$, $ARCH$ y $GARCH$.
+ Aplicaciones a históricos de precios de diferentes instrumentos financieros.
+ Implementaciones en Python y R.


## 📚 Bibliografía 📚

1. Lo, Ambrose. (2018). *Derivative Pricing. A Problem-Based Primer*. Taylor \& Francis Group, LLC
2.  McDonald, R. (2012). *Derivative Markets*. Third Edition. Pearson Series in Finance.
3. Baxter, M. \& Rennie, A. (1996). *Financial Calculus: An Introduction to Derivative Pricing*. 17th. Edition. Cambridge University Press.
4. Junghenn, H. (2019). *An Introduction to Financial Mathematics: Option Valuation*. 2nd. Edition. Chapman and Hall/CRC.
5. Elton, G., Gruber, M. Brown, S. \& Goetzmann, W. (2014). *Modern Portfolio Theory and Investment Analysis*. 9th Edition. Wiley.
6. Luenberger, D. (2013). *Investment Science*. 2nd Edition. Oxford University Press.
7. Alos, E. & Merino, R. (2022). *Introduction to Financial Derivatives with Python*. Chapman and Hall/CRC Financial Mathematics.
8. Flux, J. (2024). *Options Pricing with AI*. Independently published.
9. Kelliher, C. (2025). *Quantitative Finance with Case Studies in Python: A Practical Guide to Investment Management, Trading and Financial Engineering*. Chapman and Hall/CRC Financial Mathematics Series.
10. Ohsaki, S., Ruppert-Felsot, J. \& Yoshikawa, D. (2018). *R Programming and Its Applications in Financial Mathematics*. CRC Press.
11. Regenstein, J. (2018). *Reproducible Finance with R: Code Flows and Shiny Apps for Portfolio Analysis.* Chapman and Hall/CRC.
12. Ruppert, D. \& Matteson, D. (2015). *Statistics and Data Analysis for Financial Engineering: with R examples*. Springer Texts in Statistics.
13. Berk, J. \& DeMarzo, P. (2017) *Corporate Finance*. 4th Edition. Pearson.
14. Daróczi, G. *et al.* (2013). *Introduction to R for Quantitative Finance*. 1st Edition. Packt Publishing.
15. Charpentier, A. (2016). *Computational Actuarial Science with R*. 1st Edition. CRC Press.
16. Wickham, H. \& Grolemund, G. (2017) *R for Data Science*. 1st. Edition. O'Reilly.
17. Wickham, H. \& Grolemund, G. (2020) *R for Data Science*. 2nd. Edition. Versión en línea.

# 🎖 EVALUACIÓN 🎖
El curso será evaluado de la siguiente manera:

+ Tareas de casa y laboratorios/Prácticas/Proyectos de R \& Python: En equipos de a los más 4 integrantes y cuyo valor será del 30\% de la calificación final. 5 tareas aproximadamente.
+ Cuatro exámenes parciales: De manera individual en el salón de clases, cuyo valor es del 70\% de la calificación final.
+ Habrá dos reposiciones y un examen final (el mismo día)
+ La escala de calificaciones en la siguiente:
[0,6)-5, [6, 6.6)-6, [6.6, 7.6)-7, [7.6, 8,6)-8, [8.6, 9.6)-9 y [9.6, 10)-10
+ No se cambia ninguna calificación por NP. No hay renuncias a calificaciones.

# 🧐 ACLARACIONES 🧐

+ Las sesiones requieren asistencia plena, no sólo física.
+ Bajo ningún motivo se aceptarán tareas después de la fecha fijada de entrega.
+ No se realizarán exámenes extemporáneos por ningún motivo.
+ No se permiten teléfonos móviles encendidos y en consecuencia, queda prohibido salir del salón para contestar llamadas. En caso de hacerlo se retirará lo que resta de dicha sesión.
+ No se permite la entrada después de la hora más 15 minutos

# FORMA DE ENTREGA DE LAS TAREAS:
+ Se debe respetar el orden de las preguntas, y si no se contesta alguna, se debe escribir la pregunta y especificar que no se contestó. En caso de no ser así, no se revisará dicha tarea, obteniendo la calificación de cero en dicha tarea.
+ Limpieza y letra legible. Preferentemente en LaTeX o RMarkdown

# CALENDARIO

<img src="imagenes/calendario_unam.png" align="right" height="350" width="250" hspace="8">

## Exámenes Parciales
+ Tema 1. Viernes 28 de febrero de 2025.
+ Tema 2. Viernes 28 de marzo de 2025.
+ Temas 3 y 4. Viernes 25 de abril de 2025.
+ Tema 5. Viernes 23 de Mayo de 2024.

### Reposiciones y Examen Final
Fecha indicada por la División de Estudios Profesionales para el segundo periodo de exámenes finales.
