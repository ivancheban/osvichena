---
title: Головна
sections:
  - type: heroblock
    template: heroblock
    section_id: hero
    component: hero_block.html
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
  - type: contentblock
    template: contentblock
    title: Про мене
    section_id: about
    actions:
      - label: Зв’язатися зі мною
        url: /contact
    component: content_block.html
    content: >-
      This is the "about" excerpt. It can be used to provide a paragraph about
      yourself that people can read on the homepage to get a sense of who you
      are. There also exists a dedicated about page where you can write more
      about yourself for those who are interested.
  - type: postsblock
    template: postsblock
    title: Останні дописи
    section_id: recent-posts
    actions:
      - label: Дивитися блог
        url: blog/index.html
    component: posts_block.html
    num_posts_displayed: 4
menu:
  main:
    name: Головна
    weight: 1
layout: home
---
