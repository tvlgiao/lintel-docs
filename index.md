---
layout: default
title: Lintel theme documentation
lead: Everything you need to set up, customize and get support for Lintel, a Shopify theme by PapaThemes.
---

Lintel is an editorial Shopify theme built on Online Store 2.0. It ships with four presets, sections you arrange in the theme editor, a full-featured product page, filtering, a cart drawer, predictive search, color schemes with light and dark palettes, and translations in English, French and Spanish.

<ul class="cards">
  <li><a href="{{ '/getting-started/' | relative_url }}"><strong>Getting started</strong><span>Install the theme, choose a preset and learn the theme editor.</span></a></li>
  <li><a href="{{ '/theme-settings/' | relative_url }}"><strong>Theme settings</strong><span>Every global setting, group by group.</span></a></li>
  <li><a href="{{ '/sections/' | relative_url }}"><strong>Sections</strong><span>What each section does, with its settings and blocks.</span></a></li>
  <li><a href="{{ '/product-page/' | relative_url }}"><strong>Product page</strong><span>Gallery layouts, swatches, frequently bought together, size guide and more.</span></a></li>
  <li><a href="{{ '/collections/' | relative_url }}"><strong>Collections and filtering</strong><span>Layouts, sidebars, filters, sorting and pagination.</span></a></li>
  <li><a href="{{ '/colors/' | relative_url }}"><strong>Color schemes and dark mode</strong><span>Six schemes, each with a light and a dark palette.</span></a></li>
  <li><a href="{{ '/tutorials/' | relative_url }}"><strong>Custom code tutorials</strong><span>Custom CSS, Custom Liquid and safe code edits.</span></a></li>
  <li><a href="{{ '/support/' | relative_url }}"><strong>Support</strong><span>What support covers and how to reach us.</span></a></li>
</ul>

## Presets and demo stores

Lintel includes four presets. Each preset is the same theme with its own colors, fonts and home page content.

<div class="shots">
{% include figure.html src="index/home-lintel" alt="Lintel preset home page: a living room hero with the headline Designed for living" caption="Lintel" %}
{% include figure.html src="index/home-bisque" alt="Bisque preset home page: a ceramics hero with the headline Each piece, made by hand" caption="Bisque" %}
</div>
<div class="shots">
{% include figure.html src="index/home-neroli" alt="Neroli preset home page: a skincare hero with the headline Skin in season" caption="Neroli" %}
{% include figure.html src="index/home-savile" alt="Savile preset home page: a fashion hero with the headline Eight pieces. Finite quantity." caption="Savile" %}
</div>

| Preset | Demo store |
| --- | --- |
{%- for store in site.demo_stores %}
| {{ store.name }} | [{{ store.url | remove: 'https://' }}]({{ store.url }}) |
{%- endfor %}

## Need help?

Start with the [FAQ]({{ '/faq/' | relative_url }}). If your question isn't answered there, read the [support policy]({{ '/support/' | relative_url }}) and [contact support]({{ '/contact/' | relative_url }}). We reply {{ site.support_response_time }}.
