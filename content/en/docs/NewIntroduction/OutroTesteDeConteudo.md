---
title: "OutroTesteDeConteudo"
description: ""
lead: ""
date: 2023-02-05T23:58:47-03:00
lastmod: 2023-02-05T23:58:47-03:00
draft: false
images: []
menu:
  docs:
    parent: "newintroduction"
weight: 20
toc: true
---
{{< alert icon="💡" text="You can change the commands in the scripts section of `./package.json`." />}}

## create

Create new content for your site:

```bash
npm run create [path] [flags]
```

See also the Hugo docs: [hugo new](https://gohugo.io/commands/hugo_new/).

### Docs based tree

Create a docs based tree — with a single command:

```bash
npm run create -- --kind docs [section]
```

For example, create a docs based tree named guides:

```bash
npm run create -- --kind docs guides
```