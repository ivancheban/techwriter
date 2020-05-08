---
title: My Photo Gallery
resources:
- src: "gallery/*.jpg"
  name: gallery-:counter
  title: gallery-title-:counter
menu:
  main:
    name: My Photo Gallery
    weight: 6
layout: page
---

{{< load-photoswipe >}}
{{< figure link="/img/gallery/Sleepy-Koala.jpg" thumb="-thumb" >}}


