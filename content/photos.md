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
{{< figure link="/img/gallery/aivazovskiy2.jpg" caption="Aivazovskiy2" >}}
{{< figure link="/img/gallery/aivazovskiy3.jpg" caption="Aivazovskiy3" >}}
{{< figure link="/img/gallery/artlib.jpg" caption="Ships" >}}
{{< figure link="/img/gallery/me-full.jpg" caption="Ivan" >}}
{{< figure link="/img/gallery/me-embroidery.jpg" caption="Betlab" >}}
{{< /gallery >}}
