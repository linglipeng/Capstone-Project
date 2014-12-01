---
title       : Capstone Project Deck
subtitle    : Text Prediction App
author      : Lingli Peng
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Plan for creating a prediction algorithm and Shiny app

1. After exploring the small training data, build the ngram model with bigger data set by aggregating smaller TermDocumentMatrix.Need experimentation on how big the machine can handle.

2. Convert TermDocumentMatrix to frequence table, and build probability matrix.

3. Apply smoothing to handle unseen words.

4. Based on probability matrix, predict the most likely words next.

5. Deploy to Shiny app.

--- 




