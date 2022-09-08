# Data-analysisisis

---
title: "Cyclistic bike-share case study"
author: "Terence Chau"
date: "18/6/2021"
output:
  pdf_document: default
  html_document: default
---

```{r echo=FALSE}
library(RPostgres)
con <- dbConnect(RPostgres::Postgres(), host="localhost", dbname="bike_trip", user=rstudioapi::askForPassword("postgres"), password=rstudioapi::askForPassword("pgP@ssw0rd"))
```

\ <br>
\ <br>
