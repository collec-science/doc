---
title: Introduction
type: docs
---

# Collec-Science documentation

Here you will find all the documentation for the Collec-Science software.

It has been compiled from Markdown files, and uses the [hugo](https://gohugo.io/) engine with the [hugo-book](https://themes.gohugo.io/themes/hugo-book/) theme for rendering. The first pages are copies of the documentation present in the application, some links are inoperative and some formatting commands have not been removed.

If you would like to contribute to this documentation :

- create a _fork_ repository [https://github.com/collec-science/docs](https://github.com/collec-science/docs)
- make the changes in the _develop_ branch, and then propose _request for merge_.

The documents should be placed in the `content/en/` or `content/en/` folder. The entries in the left-hand menu should be declared in the `content/fr/menu/index.md` file (or `en` for the English version).

## To test the site locally

Consult the _hugo_ documentation to find out how to configure your environment correctly.

For local operation, you need to check that the `hugo.toml` file contains the following line:

```
theme = 'hugo-book
```

The line with _github_ in the path is used for publication in Github.

To start the _hugo_ server, in the folder containing the code, run the following command:

```
hugo server -minify
```