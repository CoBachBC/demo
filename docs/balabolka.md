---
layout: default
title: Balabolka
nav_order: 5
---

# Balabolka
{: .no_toc }

## Temas
{: .no_toc .text-delta }

1. TOC
{:toc}

---
<style>
    .container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
    }
    .video {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>

## Balabolka

Balabolka es una herramienta para la generación de voz a partir de texto. Funciona (en Windows) con el set de voces SAPI que tenga instalado el sistema operativo.

Es versátil pues puede leer texto desde el portapapeles, copiado-pegado, o desde archivos de texto. Y se puede utilizar tanto como en forma de aplicación solitaria o como utilidad de la línea de comando, lo que permite automatizar la generación de texto hablado a partir de archivos de texto.

En conjunto con la aplicación *open-source* **FFMPEG** permite la creación de videos subtitulados. Esto permite generar material didáctico que para idiomas muy facilmente, como lo muestran los siguientes videos:

<div class="container">
    <iframe class="video" src="https://www.youtube.com/embed/videoseries?list=PLdGXgLDHGSQvG-zPavPE_XkQnfDcCn5w-" frameborder="0" allowfullscreen></iframe>
</div>

## ¿Cómo generar archivos para producir material hablado?

Los equipos docentes que contribuyan a la generación del material didáctico **no** necesitan capacitarse en el uso de Balabolka, ya que esta herramienta es de carácter técnico.

La contribución docente es en el ámbito del contenido, y para este propósito pueden seguir la presente guía.

### Organizando las ideas

Para producir un video de un tema, técnicamente se espera recibir un archivo de texto. Tomemos como ejemplo la asignatura **Inglés 1**, en la **Unidad 1**, en la página 15 del libro, donde se presenta el uso del verbo *to be* con los pronombres.

![](/assets/images/balabolka-01-01.png){: .img-tutorial-h}

El tema seleccionado para ejemplificar, es el verbo *To be*, de la página 15 del libro, de Inglés 1
{: .img-tutorial-leyenda}

Continuando con la suposición, pensemos que se desea producir un material audiovisual que repita claramente la diferencia entre **I am** y su contracción **I'm**.

### 1. Registro de entrada

En la [hoja de cálculo Entradas ESL CoBach BC](https://docs.google.com/spreadsheets/d/1DhRetj90AisoGd01740jlRBOGsHwRS2JzkQ1BGucOm0/edit?usp=sharing), captura los datos requeridos (solo podrás ingresar información si eres parte del equipo de colaboradores defininido por Actividades Educativas) tomando en cuenta las siguientes consideraciones:

- Las columnas en verde se completan automáticamente.
- Las columnas en gris son para uso de Informática exclusivamente.

Tomando esto en cuenta, procede primero a registrar los datos del material que vas a generar. Si tu material corresponde al libro, usa la columna **Página** y captura su número de página, y captura en cero la columna **Índice**. La columna índice la usarás solo cuando el material que quieras producir no corresponda al libro, en ese caso captura Página en 0 y usa un consecutivo tomando en cuenta todos los materiales que vayas a querer producir que no estén relacionados con el libro.

Para *Nombre corto* **no uses acentos, signos de puntuación, ni eñe**, escríbelo en inglés y reduce las palaras al mínimo, ya que servirá para el nombre de archivo. Que sea tan reducido como sea posible, pero que sea lo suficientemente descriptivo para saber cuál es el tema.

![](/assets/images/balabolka-01-02.gif){: .img-tutorial-h}

Datos específicos del tema seleccionado
{: .img-tutorial-leyenda}

Al capturar los datos del material que vas a redactar, la hoja de cálculo te proporciona un nombre de archivo. Ese nombre de archivo es el que utilizarás para el archivo de texto que vas a guardar.

![](/assets/images/balabolka-01-03.png){: .img-tutorial-h}

Selecciona la celda **Nombre de archivo** y **cópiala**.
{: .img-tutorial-leyenda}

### 2. Creación del archivo de texto

Busca un editor de texto. Si estás usando Windows el **Bloc de notas** es una buena opción, que ya viene preinstalado, y en MacOS puedes encontrar **TextEdit**. Los ejemplos que verás están basados en Windows 10 y el Bloc de notas.

![](/assets/images/balabolka-01-04.png){: .img-tutorial-h}

Al abrirlo, como acabas de copiar el texto del nombre de archivo producido por la hoja de cálculo, haz que tu primera acción sea guardarlo.

![](/assets/images/balabolka-01-05.png){: .img-tutorial-h}

Antes de empezar a escribir, guarda el documento para facilitar su organización
{: .img-tutorial-leyenda}

Elige la ubicación donde lo quieras guardar. Una sugerencia es que crees una carpeta exclusiva para este tipo de archivos, pero puedes guardarlo como mejor te parezca de acuerdo a tus hábitos de organización. Solo asegúrate de pegar el nombre que copiaste. El tipo de archivo por defecto ya es TXT.

![](/assets/images/balabolka-01-06.png){: .img-tutorial-h}

Pega el nombre copiado y guarda
{: .img-tutorial-leyenda}

Verás que tu archivo ya tiene el nombre único generado por la hoja de cálculo.

![](/assets/images/balabolka-01-07.png){: .img-tutorial-h}

### 3. Redacción del contenido

Esos pasos son suficientes para que tu archivo esté listo para redactar. De acuerdo al tema que elegiste, redacta los ejemplos. Toma en cuenta las siguientes sugerencias.

- No dejes espacios en blanco innecesarios. El archivo será leído por un programa, por lo que no requiere formato para presentación, solo estructurar en orden los enunciados que quieres sean producidos.
- Considera iniciar con el nombre completo del tema.
- Puedes usar lo siguiente para generar pausas:
    - Punto y a parte (**.**)
    - Punto y seguido (**.**)
    - Punto y coma (**;**)
    - Dos puntos (**:**)
    - Coma (**,**)
    - Puntos suspensivos (**...**)
- Es aconsejable dejar un renglón en blanco entre el tema y los enunciados que desees producir, ya que el archivo que produzcas también será utilizado para incorporarse en la descripción del video, y eso le ayudará a tener legibilidad.

![](/assets/images/balabolka-01-08.png){: .img-tutorial-h}

En YouTube, el texto que redactas será mostrado como descripción del video
{: .img-tutorial-leyenda}

- El uso de mayúsculas y minúsculas no representa un cambio en la voz, pero te puede servir para acentuar palabras o conceptos, ya que en los subtítulos se mostrarán en mayúsculas.

#### 3.1 Uso de apóstrofe para contracciones

Verifica la configuración de tu teclado y usa el caracter correcto para los apóstrofes en las contracciones. En un teclado típico con configuración para Latinoamérica (tiene la Ñ presente), normalmente se encontrará en la tecla siguiente al cero.

El código ASCII para este caracter es **`ALT + 39`**, en caso de no poder ubicarlo en la distribución del teclado.

![](/assets/images/balabolka-01-09.png){: .img-tutorial-h}

Ubicación del caracter de apóstrofe en una distribución típica Español Latinoamérica
{: .img-tutorial-leyenda}

Con eso en cuenta, tu archivo redactado puede verse similar a esto:

![](/assets/images/balabolka-01-10.png){: .img-tutorial-h}

### 4. Números y cantidades

#### 4.1 Números enteros simples

Puedes escribir los número simples directamente. Opcionalmente, puedes escribir una coma para separar las centenas de los millares, y los millares de los millones, si deseas mejorar la legibilidad del número en los subtítulos.:

- 5
- 94
- 604
- 1546 o 1,546
- 65983 o 65,983
- 352486 o 352,486
- 1586543 o 1,586,543

Cualquiera que sea la opción que elijas **no uses espacios** para separar los dígitos de un solo número

#### 4.2 Números telefónicos

Utiliza guiones para separar números telefónicos, usa el formato de 10 dígitos de la siguiente manera:

- 123-456-7890

Si necesitas agregar el identificador de país puedes anteponerlo usando paréntesis, de la siguiente manera:

- (52) 123-456-7890

#### 4.3 Dinero

Anteponiendo el signo **$** convertirá el número en un valor monetario. Cuando expreses cantidades monetarias **usa siempre** comas cada 3 dígitos cuando sean necesarias, y finaliza la cantidad con **.00**, expresa los centavos cuando necesites en esta última parte. **Nunca uses espacios** dentro de una cantidad. Por ejemplo:

- $25.00
- $486.52
- $5,034.00
- $71,340.10
- $314,854.03
- $9,014,357.07

#### 4.4 Fechas

Usa el formato **mes día año** para que identifique automáticamente las fechas. El año lo puedes escribir con 4 dígitos para que lo pronuncie completo, o con 2 dígitos para que pronuncie solo las decenas. Puedes usar **guiones o diagonales** para separar el día, del mes, del año. Por ejemplo:

- 05-03-2022
- 05/03/2022
- 05-03-22
- 05/03/22

### 5. Créditos

Si deseas añadir créditos que se muestren en la descripción del video, pero no sean parte de la voz hablada, puedes incorporarlos dentro de corchetes (**[]**) al final de tu archivo de texto.

Es aconsejable que los redactes por línea de una forma similar a la siguiente:

![](/assets/images/balabolka-01-11.png){: .img-tutorial-h}

En este caso se muestran ordenados por nombre en orden alfabético ascendente. Pueden ser ordenados de la forma que el equipo de trabajo convenga.

### 6. Voces diferenciadas

Los archivos pueden generarse con una sola voz, o con una combinación de ellas. Para el idioma inglés, dispone de una voz femenina (Zira), y una voz masculina (Dave).

Para agregar variación de voces, es necesario que el texto sea etiquetado, de tal forma que el programa sepa cuándo usar una voz distinta. **Por defecto hablará en inglés con la voz femenina Zira**.

Cuando se quiera indicar el uso de la voz masculina, Dave, será necesario rodear el texto que se desea sea pronunciado por *él* con etiquetas especiales para saber cuándo empieza a hablar Dave y cuándo termina de hablar.

- **`{dave}`** (llave de apertura + dave + llave de cierre): Dave empieza a hablar
- **`{findave}`** (llave de apertura + findave + llave de cierre): Dave termina de hablar

Entonces, un fragmento leído por Dave se debe mostrar: `{dave}Hi, my name is Dave{findave}`

Por lo que un guión de texto con voces intercaladas se vería algo como esto:

![](/assets/images/balabolka-01-12.png){: .img-tutorial-h}

### 7. Archivo terminado

Podrás saber que tienes un archivo válido para producir material didáctico verificando los siguientes puntos:

- Todos los datos requeridos están capturados en [Entradas ESL CoBach BC](https://docs.google.com/spreadsheets/d/1DhRetj90AisoGd01740jlRBOGsHwRS2JzkQ1BGucOm0/edit?usp=sharing).
- El archivo de texto está titulado con **Nombre de archivo** proporcionado por la hoja de cálculo.
- Existe en la primera línea un título que describe la estructura o tema.
- Los enunciados están redactados en líneas.
- Las frases que se espera sean pronunciadas por la segunda voz están debidamente etiquetadas (dónde empieza a hablar y dónde termina de hablar Dave).
- Redactaron los créditos al final del archivo de texto entre [corchetes].

Con estas comprobaciones podemos asumir que el archivo será compatible para su procesamiento, de acuerdo a la estructura de organización que implemente el equipo, los archivos TXT serán compartidos con las personas coordinadoras en Actividades educativas.

![](/assets/images/balabolka-01-13.png){: .img-tutorial-h}

Archivo terminado cotejado con la lista de verificación
{: .img-tutorial-leyenda}