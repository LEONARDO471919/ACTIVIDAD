# Ejercicio 04 - CSS

## Introducción
Las **Hojas de Estilo en Cascada** (CSS, por sus siglas en inglés) son el lenguaje encargado de definir la presentación visual de los documentos estructurados en HTML. Mientras que HTML provee el esqueleto y la lógica del contenido, CSS actúa como la capa de diseño que determina colores, tipografías, espaciados y disposiciones. Su propósito fundamental es separar el contenido de la presentación, permitiendo que un mismo documento pueda adaptarse a múltiples dispositivos y estilos de manera eficiente.

![imagen de CSS](https://areaf5.es/wp-content/uploads/2023/06/Lenguajes-2048x1366.jpg)

## Síntesis
CSS funciona mediante una sintaxis de **reglas**, compuestas por un selector y un bloque de declaración. El selector indica a qué elemento del HTML se le aplicará el estilo (ya sea por nombre de etiqueta, clase o ID), mientras que la declaración especifica la propiedad y el valor (por ejemplo, `color: blue;`). Un concepto vital que se vio en clase es la **cascada**, un algoritmo que determina qué estilos se aplican cuando existen reglas contradictorias. Esta jerarquía se basa en la especificidad del selector y el orden de aparición, permitiendo un control granular sobre el diseño final.

Otro pilar fundamental del CSS es el **Modelo de Caja** (Box Model). En este modelo, cada elemento en una página web es tratado como una caja rectangular que consta de cuatro partes: el contenido (content), el relleno (padding), el borde (border) y el margen (margin). Comprender cómo interactúan estas propiedades es esencial para controlar el tamaño de los elementos y el espacio entre ellos. Además, el diseño moderno se apoya en sistemas de disposición como **Flexbox** y **Grid**, que permiten crear interfaces complejas y adaptables (responsive) sin recurrir a técnicas obsoletas de flotación de elementos.

Finalmente, CSS permite la creación de experiencias visuales ricas mediante el uso de variables, animaciones, transiciones y consultas de medios (**media queries**). Estas últimas son las responsables de que un sitio web se vea correctamente tanto en un monitor de escritorio como en la pantalla de un teléfono móvil. Al aplicar estilos de manera externa (mediante archivos `.css`), los desarrolladores pueden mantener la consistencia visual de miles de páginas desde un solo lugar, optimizando drásticamente el flujo de trabajo y la carga del navegador.

## Reflexión
Lo que considero más útil de CSS es la **versatilidad y el control estético** que ofrece sobre la información. Es impresionante cómo un mismo archivo HTML puede transformarse completamente simplemente cambiando unas líneas de código en la hoja de estilos. Me parece que el concepto de "cascada" y especificidad es un reto lógico interesante, ya que obliga al programador a ser ordenado y estratégico en la forma en que estructura sus diseños, priorizando siempre la legibilidad y la experiencia del usuario.

## Conclusión
En conclusión, CSS es el lenguaje que otorga identidad y orden visual a la web. A través de este ejercicio, se ha explorado cómo la combinación de selectores, el modelo de caja y las técnicas de diseño adaptativo permiten crear interfaces profesionales y funcionales. Dominar CSS no es solo una cuestión de estética, sino de eficiencia técnica y usabilidad, consolidándose como una herramienta indispensable para dar vida a la estructura estática del HTML.