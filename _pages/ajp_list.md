---
layout: single
sidebar:
  nav: ajp
title: Anson Jones Press - List of Publications
permalink: /ajp_list
---
A complete list of all publications by the Anson Jones Press
{% assign books = site.data.books %}
{% assign all_books = books.thirties | concat: books.forties | concat: books.fifties | concat: books.sixties | concat: books.seventies %}
{% for book in all_books %}
1. {{ book.title }}
{% endfor %}
