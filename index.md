## James Stephaniuk Personal website

Check out my [CV]({% link cv.md %})

Read [about]({% link about.md %}) me

[Contact]({% link contact.md %}) Info

# Blog posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
