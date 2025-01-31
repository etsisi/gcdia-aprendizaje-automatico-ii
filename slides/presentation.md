---
marp        : true
title       : Presentación de la asignatura
paginate    : true
theme       : etsisi
header      : Presentación de la asignatura
footer      : Aprendizaje Automático II
description : >
    Presentación de la asignatura Aprendizaje Automático II. Grado en Ciencia de Datos e Inteligencia Artificial. Escuela Técnica Superior de Ingeniería de Sistemas Informáticos. Universidad Politécnica de Madrid.
keywords    : >
    Aprendizaje Automático, Inteligencia Artificial, Grado en Ciencia de Datos e Inteligencia Artificial, ETSISI, UPM
math        : mathjax
---

<!-- _class: titlepage -->

# Introducción al aprendizaje profundo

## Aprendizaje profundo

### Departamento de Sistemas Informáticos

#### E.T.S.I. de Sistemas Informáticos - UPM

##### 31 de marzo de 2025

[![height:30](https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/by-nc-sa.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

# Presentación

## Profesores

- Alberto Díaz Álvarez (**coordinador**), <[alberto.diaz@upm.es](mailto:alberto.diaz@upm.es)>, D4406.
- Francisco Serradilla García, <[francisco.serradilla@upm.es](mailto:francisco.serradilla@upm.es)>, D4408.

## De dónde sacar información

- Moodle de la asignatura
- X: @ermanitu, con el tag #AI
- [towardsdatascience.com](https://towardsdatascience.com/)

## Recomendaciones

- **Python** y **Jupyter** (pero sobre todo Python)

---

# ¿De qué va esta asignatura?

Datos vs. información vs. conocimiento

- **Datos**: hechos, cifras, observaciones
- **Información**: datos organizados
- **Conocimiento**: información interpretada
- ¿Cómo se pasa de uno a otro?

Trataremos el aprendizaje automático **avanzado**:

- **Aprendizaje profundo**
  - Problemáticas del entrenamiento de modelos y cómo solventarlas
- _Boosting_ y _bagging_
- Clústering probabilístico
- **Aprendizaje por refuerzo**
- Aplicaciones, explicabilidad y ética

---

# ¿De qué va esta asignatura?

Cuando nos enfrentamos a problemas reales

- ¿Qué necesitamos para empezar?
- ¿Cómo construimos modelos que representen el conocimiento que hay en los datos?
- ¿Cómo podemos utilizar los modelos para diferentes tareas?
  - Clasificar
  - Predecir
  - Optimizar
- ¿Cómo **garantizamos** que la solución va a funcionar bien con datos desconocidos?
  - Este es realmente el problema más importante de todos
  - Nada de lo que hagamos sirve de nada si nuestro  sistema no se comporta bien en el mundo real
- ¿Qué podemos hacer si en lugar de datos tenemos información no estructurada?

---

# IA, ML, DS, DL, ...

![](https://www.researchgate.net/publication/364952960/figure/fig2/AS:11431281178275259@1690855736326/The-position-of-deep-learning-in-artificial-intelligence-and-data-science-10.png)

---

# Objetivos

Continuación de la asignatura de Aprendizaje Automático I

- Incidiremos en los modelos más avanzados de AA
  - Sobre todo en **aprendizaje profundo**

Aprender y profundizar en los conceptos que más nos interesen

---

# Temario

1. Aprendizaje profundo
2. Clústering probabilístico
3. Clasificación supervisada probabilística
4. Algoritmos ensemble
5. Aprendizaje por refuerzo

---

# Organización de la asignatura

4 horas a la semana, divididas en

- 2 horas de teoría
- 2 horas de prácticas en laboratorio

Grupos de tres estudiantes

- Salvo cuestionarios, claro
- Todas las actividades obligatorias permiten llegar al notable
  - Para obtener más notas habrá que realizar algunas de las actividades optativas
- Las prácticas tienen un mínimo, pero no un máximo
  - Los alumnos interesados en profundizar pueden añadir lo que quieran o proponer prácticas adicionales

---

# Prácticas

- Perceptrones con numpy
- CNN con PyTorch (dataset de flechas)
- NLP de artículos
- Q-Learning (¿piedra, papel, tijera?) y Deep Q-Learning (¿pong?)
- Opcionales para subir nota

---

# Actividades

Cuestionarios de teoría, que incluyen examen de la parte práctica (50%)

- 25% examen de los temas teóricos
- 25% examen de la parte práctica

Prácticas (50%)

Alternativa a asistencia a clase: trabajo adicional de ~60 horas

- Lectura de 5 artículos complementarios y trabajo resumen
- Prácticas individuales

---

# Normas para cuestionarios

Normas para la realización de los cuestionarios:

- Se realizarán en clase en los momentos programados por el profesor
- Se realizarán de modo individual
- Las transparencias es solo una parte de lo que se va a preguntar. Conviene venir a clase
- La calificación será automática y estará disponible al cerrar el cuestionario
- Las respuestas correctas estarán visibles después de la fecha de cierre del cuestionario

---

# Prácticas

Normas para la realización de las prácticas:

- Se realizan en grupos de tres estudiantes
- Es **imprescindible que el código ejecute sin errores** para aprobar la práctica
- Se valorará:
  - Si se ajusta a los requisitos del enunciado
  - La aportación de funciones adicionales a las del enunciado
  - La estructura del código
  - La eficiencia en la ejecución
- Es obligatoria la entrega de todas las prácticas
- En la convocatoria de julio podrán completarse las entregas no realizadas

---

# Referencias

- Convolutional Neural Networks for Visual Recognition. Curso de redes de convolución para reconocimiento visual de la universidad de Stanford. [http://cs231n.github.io/](http://cs231n.github.io/)
- A Deep Learning Tutorial: From Perceptrons to Deep Networks. Artículo introductorio de Ivan Vasilev sobre redes de neuronas en general y deep learning en particular. [https://www.toptal.com/machine-learning/an-introduction-to-deep-learning-from-perceptrons-to-deep-networks](https://www.toptal.com/machine-learning/an-introduction-to-deep-learning-from-perceptrons-to-deep-networks)
- Evolutionary Computation – Part 1, 2, 3 y 4. Alan Zucconi. [https://
www.alanzucconi.com/2016/04/06/evolutionary-coputation-1/](https://www.alanzucconi.com/2016/04/06/evolutionary-coputation-1/)]
- Reading Data from the Web: Web Scraping & Regular Expressions. Tutorial de cómo hacer web scrapping con expresiones regulares. [https://www.summet.com/dmsi/html/readingTheWeb.html](https://www.summet.com/dmsi/html/readingTheWeb.html)
- Blog “Towards Data Science”, en https://towardsdatascience.com

---

# Licencia<!--_class: license -->

Esta obra está licenciada bajo una licencia [Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Puedes encontrar su código en el siguiente enlace: <https://github.com/etsisi/Aprendizaje-profundo>
