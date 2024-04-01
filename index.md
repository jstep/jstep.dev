## James Stephaniuk 

Check out my [CV]({% link cv.md %}), read [about]({% link about.md %}) me, or see my [Contact]({% link contact.md %}) Info

### Blog posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
