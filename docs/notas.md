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

### Cambio de voz dentro del guión

Usa etiquetas estilo XML para etiquetar el texto que debe ser hablado por la otra voz:

`<voice required="Name=nombreDeVoz">` `Texto a ser hablado` `</voice>`

Los nombres de voz para inglés son:
* `Microsoft Dave Desktop`
* `Microsoft Zira Desktop`

Para español está:
* `Microsoft Sabina Desktop`

### Plantilla de comando para convertir texto a audio

Se espera que el comando de conversión genere un archivo de audio y sus respectivos subtítulos:

`balcon` `-f entrada.txt` `-srt` `-isb` `-w salida.wav`

* **`-f entrada.txt`**. Indica el archivo a leer.
* **`-srt`**. Produce un archivo de texto de subtítulos
* **`-isb`**. Ignorará el texto que esté entre corchetes en el archivo de entrada.
* **`-w salida.wav`**. Indica el archivo de salida.

## CLI FFMPEG

Convertir audio a video mostrando:

### Forma de onda

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]showwaves=mode=line:s=hd480:colors=#2FF3E0[v]" -map "[v]" -map 0:a -pix_fmt yuv420p -b:a 360k -r:a 44100` `salida.mp4`

### Histograma

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]ahistogram=s=1920x1080,format=yuv420p[v]" -map "[v]" -map 0:a` `salida.mp4`

### Histograma

`ffmpeg -i` `entrada.wav` `-filter_complex  "[0:a]showfreqs=s=1920x1080:mode=line:fscale=log,format=yuv420p[v]" -map "[v]" -map 0:a` `salida.mp4`

### Volumen

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]showvolume=f=0.5:c=VOLUME:b=4:w=1920:h=900,format=yuv420p[v]" -map "[v]" -map 0:a` `salida.mp4`

### Espectro

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]showspectrum=s=1920x1080,format=yuv420p[v]" -map "[v]" -map 0:a` `salida.mp4`