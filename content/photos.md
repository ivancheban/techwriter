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
{{< figure link="/img/gallery/aivazovskiy1.jpg" thumb="-thumb" >}}
{{< figure link="/img/gallery/aivazovskiy2.jpg" thumb="-thumb" >}}
{{< figure link="/img/gallery/aivazovskiy3.jpg" thumb="-thumb" >}}
{{< /gallery >}}
