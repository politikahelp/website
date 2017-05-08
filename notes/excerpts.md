# Using HTML comment

OOTB in Hexo, if you add a comment like this:

```html
<!-- more -->
```

in your .md source files (posts), you can split out excerpts from the main content.

This is great when the excerpt is part of the page content. When you want an excerpt with different text than that contained in the beginning part of post (.md file), use the following [Hexo Front Matter Excerpt plugin](https://github.com/lalunamel/hexo-front-matter-excerpt).

# Using Hexo Front Matter Excerpt plugin

This plugin has been installed (see package.json).

To use it, include an `excerpt` key in the YAML front matter, e.g.:

```yaml
---
title: Hello World
excerpt: "This is the post excerpt.
---
```
