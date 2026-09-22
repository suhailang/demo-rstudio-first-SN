---
title: "README.md"
author: "Suhaila Ng"
date: "2026-09-22"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

#### This is a STAT545A Demo

library(usethis)
use_git()
#### Press button for yes

This is an edit I made on RStudio; I need to push it to GitHub

Now this is an edit I made on GitHub; I need to pull it to RStudio

This is a second edit I made on RStudio

This is an edit I'm going to send to GitHub using the terminal

Stage Changes: git add . stages all of your modified files (can also just name the files you want to commit instead of using .)

Commit Changes: git commit -m "some message" commits your changes, along with a message summarizing the changes

Push Changes: git push origin main pushes your changes to the GitHub repo (main branch, which is typically the default)