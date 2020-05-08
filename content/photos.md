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
{{< pswp-init >}}
{{< gallery >}}
{{< figure link="/img/gallery/A-full-house.jpg" thumb="-thumb" caption="Wine" >}}
{{< figure link="/img/gallery/bountiful-sushi.jpg" thumb="-thumb" caption="Sushi" >}}
{{< /gallery >}}
