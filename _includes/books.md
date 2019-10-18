{% assign books = include.books %}
{% for book in books %}
{% include book.md book=book %}
{% endfor %}
