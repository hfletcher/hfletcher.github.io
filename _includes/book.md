{% assign book = include.book %}
## {{ book.title }}
### {{ book.author }}
**{{ book.publish_location }}: Anson Jones Press, {{ book.year }}**<br>
**{{ book.pages }}, {{ book.dimensions }}**

{% if book.description %}
{{ book.description }}
{% endif %}

{% if book.images %}
{% include gallery gallery=book.images %}
{% endif %}
