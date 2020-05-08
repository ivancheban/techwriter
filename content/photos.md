---
title: My Photo Gallery
resources:
- src: "/img/gallery/*.jpg"
  name: gallery-:counter
  title: gallery-title-:counter
menu:
  main:
    name: My Photo Gallery
    weight: 6
layout: page
---

.HasShortcode "gallery"
{{< load-photoswipe >}}
{{< pswp-gallery >}}
  {{< pswp-figure link="/img/gallery/Sleepy-Koala.jpg" thumb="-thumb"
                  size="1440x960"
                  caption="" >}}
  {{< pswp-figure link="/img/gallery/California-Flower-2.jpg" thumb="-thumb"
                  size="1440x960"
                  caption="" >}}
  {{< pswp-figure link="/img/gallery/California-Flower-1.jpg" thumb="-thumb"
                  size="1440x960"
                  caption="" >}}
  {{< pswp-figure link="/img/gallery/beautiful-bread-2.jpg" thumb="-thumb"
                  size="2160x1440"
                  caption="" >}}
{{< /pswp-gallery >}}
