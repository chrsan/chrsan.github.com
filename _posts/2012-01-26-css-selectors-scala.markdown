---
layout: post
title: "CSS Selectors Scala"
---

# {{ page.title }}

I've been working on a project similar to
[https://github.com/chrsan/css-selectors](https://github.com/chrsan/css-selectors)
but implemented in my language of choise these days,
[Scala](http://scala-lang.org).
It uses the combinator parsers present in the standard Scala library to parse
the selector string, and I've provided a default implementation which
traverses a standard Scala XML tree. Starting from a specified
[`scala.xml.Elem`](http://www.scala-lang.org/api/current/index.html#scala.xml.Elem).

I'll just polish it some more before pushing it to Github, and write
some sample code at the project wiki.

Stay tuned!
