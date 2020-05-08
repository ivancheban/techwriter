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

{{< gallery >}}
{{< figure link="/img/gallery/aivazovskiy1.jpg" caption="Aivazovskiy1" >}}
{{< figure link="/img/gallery/aivazovskiy2.jpg" thumb="-thumb" >}}
{{< figure link="/img/gallery/aivazovskiy3.jpg" thumb="-thumb" >}}
{{< figure link="/img/gallery/artlib.jpg" thumb="-thumb" >}}
{{< figure link="/img/gallery/me-full.jpg" thumb="-thumb" >}}
{{< figure link="/img/gallery/me-embroidery.jpg" thumb="-thumb" >}}
{{< /gallery >}}
