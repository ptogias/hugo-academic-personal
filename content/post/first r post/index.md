---
title: Test R post
subtitle: first test r post

# Summary for listings and search engines
summary: first test r post

# Date published
date: "2023-06-25"

authors:
- admin
---

## Overview

This a test post for R-related content.

## Tech

Some R code:

```r
library(data.table)

dt <- data.table(V1 = c(1,2,3),
                 V2 = c("one", "two", "three"))

dt[V1 >= 1, .(two, three)]

```
