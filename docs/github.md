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

![](/assets/images/github-crear-cuenta-01.png){: .img-tutorial}

Pantalla inicial para crear cuenta
{: .img-tutorial-leyenda}

![](/assets/images/github-crear-cuenta-02.png){: .img-tutorial}

Paso 1. Ingresa tu correo
{: .img-tutorial-leyenda}

![](/assets/images/github-crear-cuenta-03.png){: .img-tutorial}

Paso 2. Crea tu contraseña
{: .img-tutorial-leyenda}

![](/assets/images/github-crear-cuenta-04.png){: .img-tutorial}

Paso 3. Crea tu nombre de usuario
{: .img-tutorial-leyenda}

![](/assets/images/github-crear-cuenta-05.png){: .img-tutorial}

Paso 4. Verifica que no eres un robot y crea tu cuenta
{: .img-tutorial-leyenda}

## Crear un repositorio

Pages are split into sections that can be searched individually.
The sections are defined by the headings on the page.
Each section is displayed in a separate search result.

```yaml
# Split pages into sections that can be searched individually
# Supports 1 - 6, default: 2
search.heading_level: 2
```

## Administrar un repositorio

A search result can contain previews that show where the search words are found in the specific section.

```yaml
# Maximum amount of previews per search result
# Default: 3
search.previews: 3

# Maximum amount of words to display before a matched word in the preview
# Default: 5
search.preview_words_before: 5

# Maximum amount of words to display after a matched word in the preview
# Default: 10
search.preview_words_after: 10
```

## Publicar un repositorio

The default is for hyphens to separate tokens in search terms:
`gem-based` is equivalent to `gem based`, matching either word.
To allow search for hyphenated words:

```yaml
# Set the search token separator
# Default: /[\s\-/]+/
# Example: enable support for hyphenated search words
search.tokenizer_separator: /[\s/]+/
```
