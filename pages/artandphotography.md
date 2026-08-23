---
layout: page
title: Art & Photography
permalink: /about/
weight: 3
---

# Art & Photography

{% include gallery-carousel.html photos=site.data.gallery id="gallery-carousel" %}

{%- if site.data.gallery.size == 0 -%}
Photos and short notes, coming soon.
{%- endif -%}

<p class="gallery-section-title">The Chronicles of LEB members</p>

{% include gallery-carousel.html photos=site.data.leb_gallery id="leb-gallery-carousel" %}

{%- if site.data.leb_gallery.size == 0 -%}
Photos coming soon.
{%- endif -%}
