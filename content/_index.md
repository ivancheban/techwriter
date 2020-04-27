---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: hero_block.html
  content: I built this site with Hugo as a template for a technical writer's blog.
    It takes 5 minutes and a few mouse clicks. Here, I use GitHub, Forestry, Netlify,
    and Stackbit to glue them all together.
  title: ''
  actions: []
- type: contentblock
  template: contentblock
  title: About
  section_id: about
  actions:
  - label: Contact Me
    url: "/contact"
  component: content_block.html
  content: I started building my first sites back in 2005. I used the ugly CMSs available
    in those times. In 2010, WordPress seemed a beautiful and shiny technology for
    years to come. Now, in 2020 I reload my site-building CMS experience with Hugo,
    Netlify, Forestry, and other new and shiny things. Let's see what happens in the
    next decade.
  image: ''
- type: postsblock
  template: postsblock
  title: Recent Posts
  section_id: recent-posts
  actions:
  - label: View Blog
    url: blog/index.html
  component: posts_block.html
  num_posts_displayed: 4
layout: home
menu:
  main:
    weight: 1

---
