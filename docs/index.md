---
# https://vitepress.dev/reference/default-theme-home-page
layout: home
sidebar: false

hero:
  name: "Vue Patterns"
  text: "A Reference for Common Patterns in Vue"
  tagline: Collection of Essential Vue Patterns

  actions:
    - theme: brand
      text: Get Started
      link: /markdown-examples
    - theme: alt
      text: View on GitHub
      link: /api-examples

features:
  - title: Components
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
    icon: 🧩
  - title: Composables
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
    icon: 🔁
  - title: Global Project Patterns
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
    icon: 🎪
  - title: Package Suggestions
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
    icon: 📦️
---


<script setup>
import Home from '../src/components/Home.vue'

</script>

<Home />
