---
title: Bloques de construcción CSS
slug: Learn_web_development/Core/Styling_basics
original_slug: Learn/CSS/Building_blocks
---

{{LearnSidebar}}

Este módulo retoma donde [Primeros pasos en CSS](/es/docs/conflicting/Learn_web_development/Core/Styling_basics) finalizó — ahora que estás familiarizado con el lenguaje y su sintaxis, y que tienes algo de experiencia en su uso, es hora de bucear un poco más profundo. Este módulo se centra en el estilo en cascada de css y en el concepto de herencia, también veremos todos los tipos de selectores, unidades, tamaños, estilos de fondo, bordes, debugging y mucho más.

El objetivo aqui es proveerte de herramientas para que puedas escribir código CSS competentemente y ayudarte a entender lo escencial de la teoría antes de centrarnos en disciplinas más específicas como [text styling](/es/docs/Learn_web_development/Core/Text_styling) y [CSS layout](/es/docs/Learn_web_development/Core/CSS_layout).

## Prerrequisitos

Antes de comenzar este módulo deberías poseer:

1. Un entendimiento básico de la utilización de una computadora y de la
   navegación web a nivel de usuario.
2. Un entorno básico constituido en base a lo dispuesto en la guía [Instalación de software básico](/es/docs/Learn_web_development/Getting_started/Environment_setup/Installing_software), tanto como conocimiento acerca de la creación y la administración de archivos, como es detallado en [Dealing with files](/es/docs/Learn_web_development/Getting_started/Environment_setup/Dealing_with_files).
3. Una familiaridad básica con html, como es establecido en el módulo [Introdución a HTML](/es/docs/conflicting/Learn_web_development/Core/Structuring_content).
4. Un entendimiento elemental de CSS, como es discutido en el módulo [CSS first steps](/es/docs/conflicting/Learn_web_development/Core/Styling_basics).

> [!NOTE]
> Si estás trabajando en una computadora, tablet, u otro dispositivo en el que no eres capaz de crear tus propios archivos puedes intentar la mayor parte de los ejemplos en código en un programa para trabajar código en linea como [JSBin](https://jsbin.com/) o [Glitch](https://glitch.com/).

## Guías

En este módulo encontrarás artículos que cubren los fundamentos más esenciales del lenguaje CSS. A lo largo del módulo encontrarás múltiples ejercicios que te permitirán poner a prueba tu entendimiento.

- [Cascada y herencia](/es/docs/Learn_web_development/Core/Styling_basics/Handling_conflicts)
  - : El objetivo de ésta lección es desarrollar tu entendimiento sobre algunos de los conceptos fundamentales de CSS - cascada, especificidad y herencia - los cuales controlan como CSS es aplicado a HTML y como sus conflitos son resueltos.
- [Selectores CSS](/es/docs/Learn_web_development/Core/Styling_basics/Basic_selectors)
  - : Hay una gran variedad de selectores disponibles en CSS, permitiendo una fina precision para seleccionar elementos de estilo. En este artículo y sub-artículos, repasaremos los diferentes tipos en detalle y veremos como funcionan. Los sub-artículos son los siguientes:
    - [Selectores de tipo, clase e ID](/es/docs/conflicting/Learn_web_development/Core/Styling_basics/Basic_selectors)
    - [Selectores de Atributos](/es/docs/Learn_web_development/Core/Styling_basics/Attribute_selectors)
    - [Pseudo-clases y pseudo-elementos](/es/docs/Learn_web_development/Core/Styling_basics/Pseudo_classes_and_elements)
    - [Combinadores](/es/docs/Learn_web_development/Core/Styling_basics/Combinators)

- [El modelo de caja](/es/docs/Learn_web_development/Core/Styling_basics/Box_model)
  - : Todo en CSS tiene una caja a su alrededor, y comprender estas cajas es clave para poder crear diseños con CSS, o para alinear elementos con otros elementos. En esta lección, analizaremos adecuadamente el modelo CSS Box, para que pueda pasar a tareas de diseño más complejas con una comprensión de cómo funciona y la terminología que se relaciona con él.
- [Fondos y bordes](/es/docs/Learn_web_development/Core/Styling_basics/Backgrounds_and_borders)
  - : En esta lección, veremos algunas de las cosas creativas que puede hacer con fondos y bordes CSS. Al agregar degradados, imágenes de fondo y esquinas redondeadas, los fondos y los bordes son la respuesta a muchas preguntas de estilo en CSS.
- [Manejo de diferentes direcciones de texto](/es/docs/Learn_web_development/Core/Styling_basics/Handling_different_text_directions)
  - : A medida que avance en su estudio y comience a trabajar con el diseño, comprenderá los modos de escritura será muy útil para usted, por lo tanto, los presentaremos en este artículo.
- [Contenido desbordante](/es/docs/Learn_web_development/Core/Styling_basics/Overflow)
  - : En esta lección veremos otro concepto importante en CSS: desbordamiento. El Overflow (o desbordamiento) es lo que sucede cuando hay demasiado contenido para contenerlo cómodamente dentro de una caja. En esta guía aprenderá qué es y cómo administrarlo.
- [Valores y unidades de CSS](/es/docs/Learn_web_development/Core/Styling_basics/Values_and_units)
  - : Cada propiedad utilizada en CSS tiene un valor o conjunto de valores permitidos para esa propiedad. En esta lección veremos algunos de los valores y unidades más comunes en uso.
- [Dimensionar elementos en CSS](/es/docs/Learn_web_development/Core/Styling_basics/Sizing)
  - : En las diversas lecciones hasta ahora, ha encontrado varias formas de dimensionar elementos en una página web utilizando CSS. Es importante comprender cuán grandes serán las diferentes características en su diseño, y en esta lección resumiremos las diversas formas en que los elementos obtienen un tamaño a través de CSS y definiremos algunos términos sobre el tamaño que lo ayudarán en el futuro.
- [Imágenes, medios y elementos de forma](/es/docs/Learn_web_development/Core/Styling_basics/Images_media_forms)
  - : En esta lección veremos cómo se tratan ciertos elementos especiales en CSS. Las imágenes, otros medios y elementos de formulario se comportan de manera un poco diferente en términos de su capacidad para diseñarlos con CSS que los cuadros normales. Comprender qué es y qué no es posible puede ahorrar un poco de frustración, y esta lección resaltará algunas de las cosas principales que necesita saber.
- [Dando estilo a una tabla](/es/docs/Learn_web_development/Core/Styling_basics/Tables)
  - : Diseñar una tabla HTML no es el trabajo más glamoroso del mundo, pero a veces todos tenemos que hacerlo. Este artículo proporciona una guía para hacer que las tablas HTML se vean bien, con algunas técnicas específicas de diseño de tablas resaltadas.
- [Depuración de CSS](/es/docs/Learn_web_development/Core/Styling_basics/Debugging_CSS)
  - : A veces, al escribir CSS, encontrará un problema en el que su CSS no parece estar haciendo lo que espera. Este artículo le dará orientación sobre cómo solucionar un problema de CSS y le mostrará cómo las DevTools incluidas en todos los navegadores modernos pueden ayudarlo a descubrir qué está sucediendo.
- [Organizando tu CSS](/es/docs/Learn/CSS/Building_blocks/Organizing)
  - : A medida que comience a trabajar en hojas de estilo más grandes y grandes proyectos, descubrirá que mantener un gran archivo CSS puede ser un desafío. En este artículo, analizaremos brevemente algunas de las mejores prácticas para escribir su CSS para que sea fácil de mantener, y algunas de las soluciones que encontrará en uso para ayudar a mejorar la capacidad de mantenimiento.

## Evaluaciones

¿Quieres probar tus habilidades de CSS? Las siguientes evaluaciones pondrán a prueba su comprensión del CSS cubierto en las guías anteriores.

- [Comprensión de CSS básica](/es/docs/Learn_web_development/Core/Styling_basics/Fundamental_CSS_comprehension)
  - : Esta evaluación evalúa su comprensión de la sintaxis básica, selectores, especificidad, modelo de caja y más.
- [Crear papel con membrete elegante](/es/docs/Learn/CSS/Building_blocks/Creating_fancy_letterheaded_paper)
  - : Si desea causar la impresión correcta, escribir una carta en papel con membrete puede ser un buen comienzo. En esta evaluación, lo retaremos a crear una plantilla en línea para lograr ese aspecto.
- [Una caja de aspecto genial](/es/docs/Learn/CSS/Building_blocks/A_cool_looking_box)
  - : Aquí aprenderás a usar el estilo de fondo y borde para crear un cuadro llamativo.

## Ver también

- [Efectos de estilo avanzados](/es/docs/Learn/CSS/Building_blocks/Advanced_styling_effects)
  - : Este artículo actúa como una caja de trucos, brindando una introducción a algunas características de estilo avanzadas e interesantes como sombras de caja, modos de fusión y filtros.
