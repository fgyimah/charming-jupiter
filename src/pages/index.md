---
title: Home
sections:
  - section_id: hero
    component: HeroBlock
    type: heroblock
    content: >-
      I am gyimah Francis, a fullstack web and mobile developer, with keen interest in DevOps and Machine Learning
      I am open to new opportunities. Feel free to get in contact with me anytime and let's talk
  - section_id: about
    component: ContentBlock
    type: contentblock
    title: About
    content: >-
      My skills include backend web development in express and nestjs in both TypeScript and JavaScript. 
      Frontend developement with ReactJS, VueJS and Angular. Good knowledge of databases like MySQL, PostgreSQL and MongoDB.
      I love DevOps, CI/CD with CircleCI and containerization with Docker and Kubernetes.
    actions:
      - label: Contact Me
        url: /contact
  - section_id: recent-posts
    component: PostsBlock
    type: postsblock
    title: Recent Posts
    num_posts_displayed: 4
    actions:
      - label: View Blog
        url: blog/index.html
menus:
  main:
    weight: 1
    title: Home
template: home
---
