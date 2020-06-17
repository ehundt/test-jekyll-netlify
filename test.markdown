---
# front matter tells Jekyll to process Liquid
layout: page
title: Test
permalink: /test
mystring: "hello bla"
---

## TESTtitle
test test

{{ page.mystring | downcase }}
