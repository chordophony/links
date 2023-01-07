# chordophony's links

- [Reverb shop!](https://reverb.com/shop/bs-gear-4?utm_source=rev-ios-app&utm_medium=ios-share&utm_campaign=shop&utm_content=1231466)
- [chordophony github](http://github.com/chordophony)
- [IG](http://instagram.com/chordophony)
- ChatGPT Songs
  - [Across the Universe](./songs/chatgpt/across_the_universe)

## Blog ##
{% for post in site.blogposts %}
- {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
