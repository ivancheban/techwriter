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
layout: post
---

{{< gallery >}}
{{< figure link="/img/gallery/beautiful-bread.jpg" thumb="-thumb" caption="Bread" >}}
{{< figure link="/img/gallery/bountiful-sushi.jpg" thumb="-thumb" caption="Sushi" >}}
{{< figure link="/img/gallery/California-Flower-1.jpg" thumb="-thumb" caption="Flower" >}}
{{< /gallery >}}

{{< pswp-init >}
