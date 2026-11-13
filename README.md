# Your GitHub Learning Lab Repository for Introducing GitHub

Welcome to **your** repository for your GitHub Learning Lab course. This repository will be used during the different activities that I will be guiding you through. See a word you don't understand? We've included an emoji 📖 next to some key terms. Click on it to see its definition.

Oh! I haven't introduced myself...

I'm the GitHub Learning Lab bot and I'm here to help guide you in your journey to learn and master the various topics covered in this course. I will be using Issue and Pull Request comments to communicate with you. In fact, I already added an issue for you to check out.

![issue tab](https://lab.github.com/public/images/issue_tab.png)

I'll meet you over there, can't wait to get started!

This course is using the :sparkles: open source project [reveal.js](https://github.com/hakimel/reveal.js/). In some cases we’ve made changes to the history so it would behave during class, so head to the original project repo to learn more about the cool people behind this project.

## ScrollCraft

This site includes [ScrollCraft](https://github.com/Bilal-Studios/scroll-craft) (`scroll-craft` on npm), a small scroll animation library with reveal, counter and progress effects. Like reveal.js, it is installed in `node_modules/` and served directly by Jekyll.

- Demo page: `scrollcraft.html` (served at `/scrollcraft.html`)
- Use it in another page with an ES module import (in a Jekyll page, prefix the path with `{{ site.baseurl }}`):

```html
<script type="module">
  import { ScrollCraft } from '/node_modules/scroll-craft/dist/index.js';
  new ScrollCraft()
    .reveal('.card')
    .counter('[data-count]')
    .progress('#timeline .step');
</script>
```

To update it, run `npm install scroll-craft@<version>` and commit the changes in `node_modules/scroll-craft`.
