# Clon de Twitch con Tailwind CSS

<!-- hide -->

Por [@marcogonzalo](https://github.com/marcogonzalo), [@ehiber](https://github.com/ehiber) y [otros contribuidores](https://github.com/4GeeksAcademy/twitch-clone-tailwind/graphs/contributors) en [4Geeks Academy](https://4geeksacademy.com/)

[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![4Geeks Academy](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=x)](https://x.com/4geeksacademy)

_These guidelines are also [available in English](./README.md)_.

**Antes de empezar**:

> Te necesitamos. Estos ejercicios se construyen y mantienen en colaboracion con personas como tu. Si encuentras algun error o falta de ortografia, por favor contribuye y/o reportalo.

<!-- endhide -->

---

## Tu reto

En el mundo tech, una de las maneras mas efectivas de aprender a construir proyectos es replicar interfaces reales a partir de referencias que ya existen en Internet. En esta ocasion, tu reto sera crear una replica de Twitch, la conocida plataforma de streaming.

Este proyecto sera un poco mas sofisticado porque trabajaremos con **Tailwind CSS**, una biblioteca de estilos que te ayuda a construir interfaces de forma rapida y ordenada, manteniendo consistencia visual y buena estructura.

Ademas, el foco estara en algo clave hoy en dia: el **diseno responsive**. Las personas consumen contenido desde cualquier dispositivo, y en muchos casos el movil es el principal. Por eso, tu replica debe adaptarse correctamente a distintos tamanos de pantalla.

A continuacion encontraras las capturas de referencia de Twitch en sus versiones de PC, tablet y movil, junto con una vista adicional marcada por capas para ayudarte a detectar secciones y componentes visuales.

![Referencia Twitch desktop](./assets/optimized/twitch-pc-screenshot.png "Referencia Twitch desktop")

![Referencia Twitch tablet](./assets/optimized/twitch-tablet-screenshot.png "Referencia Twitch tablet")

![Referencia Twitch mobile](./assets/optimized/twitch-mobile-screenshot.png "Referencia Twitch mobile")

![Referencia Twitch desktop por capas](./assets/optimized/twitch-xl-layered.png "Referencia Twitch desktop por capas")

---

## Como iniciar el proyecto

Abre el repositorio de plantilla usando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recomendado) o clonalo en local:

```text
https://github.com/4GeeksAcademy/html-hello
```

Sigue los pasos en [como comenzar un proyecto de codificacion](https://4geeks.com/es/lesson/como-comenzar-un-proyecto-de-codificacion).

Importante: crea un nuevo repositorio en GitHub para tu codigo, actualiza el remoto (`git remote set-url origin <tu-nueva-url>`) y sube los cambios con `add`, `commit` y `push`.

---

## Que debes hacer

Lo primero que debes hacer es identificar elementos o componentes visuales dentro de la interfaz; esto te ayudara a definir con mas claridad tu estrategia. Por ejemplo:

- Tiene navbar o cabecera?
- Tiene sidebar o menu lateral?
- Como se divide el contenido principal?
- Tiene varias secciones?

Te recomendamos empezar por la version movil, pues es la que tiene menos elementos y un espacio mas limitado, pero no pierdas de vista los elementos que se emplean en los otros formatos, porque tambien deberan tener su espacio.

Te sugerimos tener en cuenta el atributo `visibility` para manejar los elementos que aparecen o desaparecen segun el viewport.

Solo debes usar:

- HTML
- Tailwind CSS

No debes usar:

- React
- Vue
- Angular
- JavaScript de componentes
- Cualquier framework adicional de interfaz

Actividades adicionales:

- Agregar efectos visuales avanzados y animaciones con CSS

---

## Que vamos a evaluar

- [ ] Correcta diagramacion del contenido con Tailwind
- [ ] Correcta agrupacion de elementos y componentes visuales
- [ ] Presentacion adecuada en movil, tablet y escritorio
- [ ] Uso correcto de HTML semantico
- [ ] Uso consistente de utilidades de Tailwind CSS

---

## Como entregar este proyecto

Debes entregar un repositorio con:

- El documento HTML que contenga toda la estructura
- El documento CSS que tenga los estilos adicionales y las media queries necesarias, si corresponde
- Una replica responsive basada en las referencias visuales incluidas en este repositorio

---

Este y muchos otros proyectos son construidos por estudiantes como parte de los [Coding Bootcamps](https://4geeksacademy.com/) de 4Geeks Academy. Encuentra mas acerca de los [cursos](https://4geeksacademy.com/es/comparar-programas) de [Full-Stack Software Developer](https://4geeksacademy.com/es/programas-de-carrera/desarrollo-full-stack), [Data Science & Machine Learning](https://4geeksacademy.com/en/career-programs/data-science-ml), [Ciberseguridad](https://4geeksacademy.com/es/programas-de-carrera/ciberseguridad) e [Ingenieria de IA](https://4geeksacademy.com/es/programas-de-carrera/ingenieria-ia).
