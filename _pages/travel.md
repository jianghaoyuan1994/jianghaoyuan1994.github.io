---
permalink: /travel/
title: "Travel"
excerpt: "Places I have visited"
author_profile: true
---

<span class="anchor" id="travel"></span>

# Travel

Beyond research and work, I enjoy traveling and exploring different places, cultures, landscapes, and everyday life around the world.

The map below records places I have visited. It is a small personal archive of my journeys, memories, and future inspiration for where to go next.

{% assign travel_photos = "Z9L_3491.jpeg,Z9L_3982.jpeg,IMG_4192.jpeg,IMG_4289.jpeg,IMG_4459.jpeg,Z9L_4638.jpeg,IMG_4467.jpeg,IMG_4518.jpeg,IMG_4713.jpeg,IMG_5090.jpeg,IMG_5136.jpeg,IMG_5282.jpeg,IMG_5349.jpeg,IMG_5888.jpeg,Z9L_4967.jpeg" | split: "," %}

<style>
  .travel-gallery {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.9rem;
    margin: 1.2rem 0 2rem;
  }

  .travel-gallery a {
    display: block;
    aspect-ratio: 4 / 3;
    overflow: hidden;
    border-radius: 6px;
    box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12);
  }

  .travel-gallery img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  @media (max-width: 900px) {
    .travel-gallery {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 560px) {
    .travel-gallery {
      grid-template-columns: 1fr;
    }
  }
</style>

## Visited Places Map

<div style="position: relative; width: 100%; height: 0; padding-bottom: 62.5%; margin-top: 1.5rem; overflow: hidden; border: 1px solid #e5e5e5;">
  <iframe
    src="https://www.google.com/maps/d/embed?mid=11tno0aOFc9xwh1A_z00KpjtX_7AYepM&ll=37.74115885415971%2C34.34639104337854&z=4"
    title="Places I have visited"
    style="position: absolute; inset: 0; width: 100%; height: 100%; border: 0;"
    loading="lazy">
  </iframe>
</div>

## Photos of the Year

<div class="travel-gallery">
  {% for photo in travel_photos %}
    <a href="/images/travel/{{ photo }}">
      <img src="/images/travel/{{ photo }}" alt="Travel photo {{ forloop.index }}" loading="lazy">
    </a>
  {% endfor %}
</div>
