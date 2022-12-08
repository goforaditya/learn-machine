---
title: "Hugo Cheatsheet"
date: 2022-12-08T12:02:53+05:30
linkTitle: "Hugo Cheatsheet"
weight: 1
description: >
    Some important Hugo snippets.
draft: flase
---

#### Creating a new section and content

Tried `>hugo new books/_index.md` didn't work.

Adding `<br>` tag adds new line in markdown.

Hugo directory structure ()[https://gohugo.io/getting-started/directory-structure/#directory-structure-explained]

(Docsy Shortcodes)[https://www.docsy.dev/docs/adding-content/shortcodes/]

The minimum frontmatter you need to provide is a title: everything else is up to you! However, if you leave out the page weight, your navigation may get a little disorganized. You may also want to include description since Docsy uses that to generate the meta description tag used by search engines. See Search Engine Optimization (SEO) meta tags for details.

```
---
title: "Adding Content"
linkTitle: "Adding Content"
weight: 1
description: >
    Add different types of content to your Docsy site.
---

```


