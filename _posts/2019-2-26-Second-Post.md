---
title: "Can I Include Code in my Blog?"
output: github_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(
	message = FALSE,
	warning = FALSE,
	include = FALSE
)

library(tidyverse)
dslabs::ds_theme_set(new="theme_minimal")
```

# Can I Include Code in my Blog Posts?

You can include R code in the document as follows:

```{r cars}
cars %>%
  ggplot(aes(dist, speed)) +
  geom_point(alpha=0.75) +
  ylab("Speed") +
  xlab("Distance")
```

It worked!
