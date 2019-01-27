---
title: "Habits"
author: John Doe
date: March 22, 2005
output: github_document
---

---
title: "Habits"
output:
  github_document:
    html_preview: true
---


library(viridis)
library(rmarkdown)

The code below demonstrates two color palettes in the [viridis](https://github.com/sjmgarnier/viridis) package. Each plot displays a contour map of the Maunga Whau volcano in Auckland, New Zealand.

## Viridis colors


image(volcano, col = viridis(200))

## Magma colors


image(volcano, col = viridis(200, option = "A"))

render("1-example.Rmd")