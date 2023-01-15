# chordophony's links

|[Reverb shop!](https://reverb.com/shop/bs-gear-4?utm_source=rev-ios-app&utm_medium=ios-share&utm_campaign=shop&utm_content=1231466)|[IG](http://instagram.com/chordophony)|

{% for collection in site.collections %}
  {% assign name = collection.label %}
# {{ name }} #
    {% for post in site.[name] %}
[{{ post.title }}]({{ post.url }})
    {% endfor %}
{% endfor %}
