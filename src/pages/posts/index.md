---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hello world!
publishDate: 12 Sep 2021
name: Nate Moore
value: 128
description: Just a Hello World Post!
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

Not sure what the element above this is... it says `<Cool .../>`, but what does that even mean (component, and if so from where!?

Do variables work {frontmatter.value * 2}?
