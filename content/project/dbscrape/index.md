---
title: DBScrape
summary: Scrape HTML Tables from DrugBank 
tags:
- Text mining
date:

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/ptogias/dbscrape"

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/ptogias99
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Export HTML tables from DrugBank to dataframes. This function can come in handy in cases where downloading and processing the full database is not viable. Code was kept as simple as possible, using only the xpath of each table and spliting respective urls in a manner that takes pagination into account.
