---
layout: default
title: GitHub
nav_order: 2
---

# GitHub
{: .no_toc }

## Temas
{: .no_toc .text-delta }

1. TOC
{:toc}

---

GitHub es un servicio que permite compartir código de cualquier lenguaje de programación, desarrollar proyectos abiertos y colaborativos, así como hospedar código. Los usuarios pueden crear repositorios (proyectos donde suben código organizado) y pueden compartirlo y publicarlo.

Los temas que vemos aquí están escritos desde la perspectiva del uso de GitHub para proyectos basados en HTML y CSS.

El sitio web está disponible solo en inglés, hay una app para [Android](https://play.google.com/store/apps/details?id=com.github.android) y [iOS](https://apps.apple.com/app/github/id1477376905?ls=1) pero requiere la creación previa de la cuenta del usuario.

## Crear una cuenta

La pantalla por defecto para creación de cuentas tiene un diseño tipo gamificado. Solicita al usuario ingrese datos tradicionales para crear una cuenta.

![](/assets/images/github-crear-cuenta-01.png){: .img-tutorial-v}

Pantalla inicial para crear cuenta
{: .img-tutorial-leyenda}

![](/assets/images/github-crear-cuenta-02.png){: .img-tutorial-v}

Paso 1. Ingresa tu correo
{: .img-tutorial-leyenda}

![](/assets/images/github-crear-cuenta-03.png){: .img-tutorial-v}

Paso 2. Crea tu contraseña
{: .img-tutorial-leyenda}

![](/assets/images/github-crear-cuenta-04.png){: .img-tutorial-v}

Paso 3. Crea tu nombre de usuario
{: .img-tutorial-leyenda}

![](/assets/images/github-crear-cuenta-05.png){: .img-tutorial-v}

Paso 4. Verifica que no eres un robot y crea tu cuenta
{: .img-tutorial-leyenda}

## Crear un repositorio

Los repositorios son los proyectos en los que almacenamos código. Podemos crear tantos repositorios como necesitemos.

En el contexto de una clase de diseño web, lo más práctico puede ser que el alumno cree un único repositorio en el cuál puede crear a su vez carpetas para organizar sus prácticas. 

### Clonar un repositorio existente

Al iniciar el aprendizaje de una nueva herramienta, normalmente es más sencillo partir de una base ya hecha para entender su funcionamiento. El siguiente ejemplo indica cómo copiar un repositorio ya existente de otro usuario y empezar a usarlo en una versión propia.

El primer paso es ubicar el repositorio existente que deseamos utilizar. La URL es la forma de identificarlos. Para este propósito, hemos creado este [repositorio de demostración](https://github.com/CoBachBC/DemoEjerciciosWeb) con la estructura de documentos simulando prácticas.

![](/assets/images/github-clonar-repo-01.jpg){: .img-tutorial-h}

Paso 1. En GitHub usando tu cuenta, tienes la opción de crear un repositorio nuevo, elige esa opción.
{: .img-tutorial-leyenda}

![](/assets/images/github-clonar-repo-02.jpg){: .img-tutorial-h}

Paso 2. En lugar de crearlo desde cero, elige la opción para importar uno existente.
{: .img-tutorial-leyenda}

![](/assets/images/github-clonar-repo-03.jpg){: .img-tutorial-h}

Paso 3. Ingresa el URL del repositorio  que quieres clonar.
{: .img-tutorial-leyenda}

![](/assets/images/github-clonar-repo-04.jpg){: .img-tutorial-h}

Paso 4. Dale un nombre nuevo con el que lo verás en tus repositorios y márcalo como público.
{: .img-tutorial-leyenda}

![](/assets/images/github-clonar-repo-05.jpg){: .img-tutorial-h}

Paso 5. Aplica los cambios con el botón verde.
{: .img-tutorial-leyenda}

![](/assets/images/github-clonar-repo-06.jpg){: .img-tutorial-h}

Paso 6. Verás un mensaje de confirmación cuando termine.
{: .img-tutorial-leyenda}


### Crear un repositorio nuevo

Un repositorio nuevo es un proyecto en blanco, el cuál vamos a estructurar con los archivos y carpetas que necesitamos.

Para crerlo es un proceso muy similar a la clonación, pero únicamente hay que darle nombre, por lo que es más sencillo.

![](/assets/images/github-crear-repo-01.jpg){: .img-tutorial-h}

## Administrar un repositorio

Para administrar un repositorio, simplemente selecciónalo y verás una lista de su contenido

![](/assets/images/github-administrar-repo-01.jpg){: .img-tutorial-h}

Verás una lista de su contenido, como si estuvieras explorando una carpeta. Puedes darle clic a cualquier elemento para entrar a las carpetas o abrir los archivos.

## Publicar un repositorio

![](/assets/images/github-publicar-repo-01.jpg){: .img-tutorial-h}

Paso 1. Entra a tu repositorio, verás los archivos que contiene, y en la parte superior varias opciones, selecciona la que corresponde a configuración (Settings).
{: .img-tutorial-leyenda}


![](/assets/images/github-publicar-repo-02.jpg){: .img-tutorial-h}

Paso 2. De las opciones de configuración, selecciona <strong>Pagesz</strong>.
{: .img-tutorial-leyenda}


![](/assets/images/github-publicar-repo-03.jpg){: .img-tutorial-h}

Paso 3. Verás que no hay ninguna seleccionada, haz clic en el botón para elegir.
{: .img-tutorial-leyenda}


![](/assets/images/github-publicar-repo-04.jpg){: .img-tutorial-h}

Paso 4. La opción principal (Main) es la que te permitirá publicar todo tu contenido.
{: .img-tutorial-leyenda}


![](/assets/images/github-publicar-repo-05.jpg){: .img-tutorial-h}

Paso 5. Asegúrate de guardar los cambios.
{: .img-tutorial-leyenda}


![](/assets/images/github-publicar-repo-06.jpg){: .img-tutorial-h}

Paso 6. Verás una confirmación y un enlace a tu web publicada.
{: .img-tutorial-leyenda}

## Usar un repositorio publicado para ejercicios de clase

Una vez que has publicado un respositorio, puedes usar su estructura de carpetas como la estructura de carpetas de un servidor web, partiendo de la dirección que te da GitHub, para los ejemplos de esta sección, el repositorio es [CoBachBC/DemoEjerciciosWeb](https://github.com/CoBachBC/DemoEjerciciosWeb) publicado en [https://cobachbc.github.io/DemoEjerciciosWeb/](https://cobachbc.github.io/DemoEjerciciosWeb/)

La estructura de carpetas actual es (se muestra cuando en la carpeta existe un archivo llamado <code>index.html</code>):

    - DemoEjerciciosWeb
        - Ejemplos
        - Ejercicio1
            - <code>index.html</code>
        - Ejercicio2
            - <code>index.html</code>
        - Ejercicio3
            - <code>index.html</code>
        - Ejercicio4
            - <code>index.html</code>
        - Ejercicio5
            - <code>index.html</code>
        - Ejercicio6
            - <code>index.html</code>

Cuando en una carpeta existe un archivo <code>index.html</code> podemos usar el nombre de esa carpeta como parte de la dirección