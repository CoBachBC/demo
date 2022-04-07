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

### Plantilla de comando para convertir texto a audio

Se espera que el comando de conversión genere un archivo de audio y sus respectivos subtítulos:

```balcon -f entrada.txt -srt -isb -w salida.wav

- **-f entrada.txt**
- **-srt**
- **isb**
- **-w salida.wav**