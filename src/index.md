---
title: "Casa tradicional luso-brasileira"
description: >
  Documentário da arquitetura doméstica publicada na bibliografia de referência
layout: "layouts/base.njk"
header:
  overlay_image: "https://i.pinimg.com/originals/f7/76/49/f7764902ee90d4fc48b6f795307bc366.jpg"
  overlay_filter: 0.7
  caption: "Abigail de Andrade, Estrada do Mundo Novo, 1888"
triptych: especiais
pagination:
  data: collections.casa
  reverse: true
  size: 6
  alias: posts
templateEngineOverride: njk,md
---

```{=html}
{%- if not lang -%}
  {%- set lang = site.locale -%}
{%- endif %}
````

# Coleções especiais #

```{=html}
{% include "partials/triptych.njk" %}
````

# Inclusões recentes #

```{=html}
<div class="row row-cols-md-2 row-cols-xl-3 g-3 mx-5">
{% for post in pagination.items %}
  {% include "partials/album.njk" %}
{% endfor %}
</div>
<div class="d-flex flex-columns row-cols-md-2 row-cols-lg-3 mx-auto mt-4 justify-content-center">
  <a type="button" href="/casa/" class="btn btn-outline-primary btn-lg">
    {{ ui_text[lang].load_all }}
  </a>
</div>
````