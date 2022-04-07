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

$$Cambio de voz dentro del guión$$

Usa etiquetas estilo XML para etiquetar el texto que debe ser hablado por la otra voz:

`<voice required="Name=nombreDeVoz">` `Texto a ser hablado` `</voice>`

Los nombres de voz para inglés son:
* Microsoft Dave Desktop
* Microsoft Zira Desktop

### Plantilla de comando para convertir texto a audio

Se espera que el comando de conversión genere un archivo de audio y sus respectivos subtítulos:

`balcon` `-f entrada.txt` `-srt` `-isb` `-w salida.wav`

* **_-f entrada.txt_**. Indica el archivo a leer.
* **_-srt_**. Produce un archivo de texto de subtítulos
* **_-isb_**. Ignorará el texto que esté entre corchetes en el archivo de entrada.
* **_-w salida.wav_**. Indica el archivo de salida.

## CLI FFMPEG

### Convertir  audio a video con forma de onda

`ffmpeg -i` `entrada.wav` `-filter_complex "[0:a]showwaves=mode=line:s=hd480:colors=#2FF3E0[v]" -map "[v]" -map 0:a -pix_fmt yuv420p -b:a 360k -r:a 44100` `salida.mp4`