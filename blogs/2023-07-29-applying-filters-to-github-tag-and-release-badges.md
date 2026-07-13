---
title: "Applying filters to GitHub Tag and Release badges"
url: "https://shields.io/blog/tag-filter"
date: "2023-07-29"
author: ""
feed_url: "https://shields.io/blog/rss.xml"
---
We recently shipped a feature which allows you to pass an arbitrary filter to the GitHub tag and release badges. The filter param can be used to apply a filter to the project's tag or release names before selecting the latest from the list. Two constructs are available: * is a wildcard matching zero or more characters, and if the pattern starts with a !, the whole pattern is negated.
