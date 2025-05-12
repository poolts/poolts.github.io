---
layout: home
title: "Welcome!"
hero:
  image: /assets/images/hero.jpg    # optional banner image
  title: "Hi, I’m Jane Doe"
  text: "I build web apps, write about code, and occasionally dabble in design."
  actions:
    - label: Resume
      link: /assets/Jane_Doe_Resume.pdf
    - label: Contact
      link: /contact/

# Now define which “sections” appear on the page, in order:
sections:
  - home: projects
    title: "My Projects"
    limit: 6
    order: desc                # newest first
  - home: posts
    title: "Latest Posts"
    limit: 3
  - home: about
    title: "About Me"
---