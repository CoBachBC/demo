---
layout: default
title: Inicio
nav_order: 1
description: "Material didáctico de reforzamiento"
permalink: /
---

# Material didáctico de reforzamiento 1er. Semestre
{: .fs-9 }


## Descarga

Baja una copia de este sitio para poder consultar toda la información sin usar tus datos:

1. Descarga en tu celular, tableta, o laptop [la aplicación Kiwix](https://www.kiwix.org/en/download/)
1. Descarga en ese mismo dispositivo [el archivo ZIM de este sitio](/assets/demo-asesorias.zim)
1. Abre Kiwix y ubica el archivo que descargaste
1. Ahora puedes consultar toda la información que ves aquí fuera de línea

---

## Materia 1

[Ver temas](/docs/materia-1){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

## Química I

[Ver temas](/docs/quimica-1){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

## Informática I

[Ver temas](/docs/informatica-1){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }


# Asignaturas

{% for doc in site.docs %}
    {{doc.title}}
{% endfor %}

{{ include.pages }}

{{ site.title }}