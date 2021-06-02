---
title: Project 1
parent: Category 1
grand_parent: Projects
nav_order: 1
---

# Wikipedia webcrawler and network visualization
---

Python{: .label }
<p class="label">Python</p>
[view on GitHub](http://example.com/){: .btn }


## Introduction

In this project I made a webcrawler to go to a [random Wikipedia page](https://en.wikipedia.org/wiki/Special:Random) and then follow the first link in the first paragraph that is not in  a text block that is surrounded by parentheses, since these are usually the pronounciation or translation links. Following this algorithm you will end up in one of the following cases:

- You will end up at the [Philosophy page](https://en.wikipedia.org/wiki/Philosophy).
- You will encounter a loop of several pages.
- There is not a link that satisfies the algorithm.

To keep my algorithm going I specified a variable of maximum depth, which is the maximum number of pages that will be visited before starting over. If the Philosophy page is encountered, we also start a new random page.

Performing this algorithm and logging the titles for all the pages we encounter and documenting from which page the link came we will be able to make a graph of the network of Wikipedia articles.

## Visualization
