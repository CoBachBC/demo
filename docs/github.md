---
layout: default
title: GitHub
nav_order: 9
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

## Crear una cuenta

In your site's `_config.yml`, enable search:

```yaml
# Enable or disable the site search
# Supports true (default) or false
search_enabled: true
```

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
