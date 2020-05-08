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
  {{< figure src="beautiful-bread.jpg" >}}
  {{< figure src="bountiful-sushi.jpg" >}}
  {{< figure src="California-Flower-1.jpg" >}}
{{< /gallery >}}

{{< load-photoswipe >}}
