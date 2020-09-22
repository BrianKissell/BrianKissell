---
date: "2020-09-22T00:00:00Z"
draft: true
lastmod: "2020-09-22T00:00:00Z"
linktitle: Understanding Causal Inference
menu:
  Understanding Causal Inference:
    name: Overview
    weight: 1
summary: Come to a better understanding of causal inference, including why it is important for your business. In this page, I describe and introduce a new project on the topic of causal inference.
title: Overview
toc: true
type: docs
weight: 1
---

## Why is causal inference important?

In 2008, I I am an experimental social psychologist, and thuThis feature can be used for publishing content such as:



The `courses` folder may be renamed. For example, we can rename it to `docs` for software/project documentation or `tutorials` for creating an online course.

## What is included within this project?

blablabla

* **Discussion of causal inference principles that can be easily understood.**
* **Project or software documentation**
* **Tutorials**

## Update site menu

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```

Or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated *Courses* menu configuration to:

```toml
[[main]]
  name = "Docs"
  url = "docs/"
  weight = 50
```

## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`.
