---
layout: default
title: Notas técnicas
nav_order: 99
---

# Notas técnicas
{: .no_toc }

## Temas
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## CLI Balabolka

### Configuraciones predeterminadas

Puedes configurar características por defecto en `balcon.exe` creando un archivo de texto `**balcon.cfg**`. Escribiendo parámetros base para que todas las ejecuciones tengan dicha configuración. Por ejemplo, para que la voz por defecto sea *Microsoft Zira*:

{% highlight batch %}
-n Microsoft Zira
{% endhighlight %}

### Cambio de voz dentro del guión

Usa etiquetas estilo XML para etiquetar el texto que debe ser hablado por la otra voz:

`<voice required="Name=nombreDeVoz">` `Texto a ser hablado` `</voice>`

Los nombres de voz para inglés son:
* `Microsoft David Desktop`
* `Microsoft Zira Desktop`

Para español está:
* `Microsoft Sabina Desktop`

#### Formato final de etiquetas de apertura XML
* `<voice required="Name=Microsoft David Desktop">`
* `<voice required="Name=Microsoft Zira Desktop">`
* `<voice required="Name=Microsoft Sabina Desktop">`

#### Formato final de etiqueta de cierre XML
* `</voice>`

### Plantilla de comando para convertir texto a audio

Se espera que el comando de conversión genere un archivo de audio y sus respectivos subtítulos:

`balcon` `-f entrada.txt` `-srt` `-isb` `-w salida.wav`

* **`-f entrada.txt`**. Indica el archivo a leer.
* **`-srt`**. Produce un archivo de texto de subtítulos
* **`-isb`**. Ignorará el texto que esté entre corchetes en el archivo de entrada.
* **`-w salida.wav`**. Indica el archivo de salida.

## CLI FFMPEG

### Convertir audio a video

#### Forma de onda

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]showwaves=mode=line:s=hd480:colors=#2FF3E0[v]" -map "[v]" -map 0:a -pix_fmt yuv420p -b:a 360k -r:a 44100` `salida.mp4`

#### Histograma

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]ahistogram=s=1920x1080,format=yuv420p[v]" -map "[v]" -map 0:a` `salida.mp4`

#### Frecuencias

`ffmpeg -i` `entrada.wav` `-filter_complex  "[0:a]showfreqs=s=1920x1080:mode=line:fscale=log,format=yuv420p[v]" -map "[v]" -map 0:a` `salida.mp4`

#### Volumen

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]showvolume=f=0.5:c=VOLUME:b=4:w=1920:h=900,format=yuv420p[v]" -map "[v]" -map 0:a` `salida.mp4`

#### Espectro

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]showspectrum=s=1920x1080,format=yuv420p[v]" -map "[v]" -map 0:a` `salida.mp4`

## GAM

### Descargar registros de admins por rango temporal

`gam` `report admin` `start 20XX-XX-XXT00:00:00.000Z` `end 20XX-XX-XXT11:59:59.000Z` `> salida.csv`

### Desacargar lista de archivos en Drive de usuario

`gam` `user usuario@cobachbc.edu.mx` `show filelist title id fileextension filesize` `> salida.csv`