Hi there 👋 
I'm James Stephaniuk, a software developer interested in Bitcoin, distributed systems, and Austrian economics.

This is a showcase site of my professional work and writtings.

If you want to see what I've been up to with my life, check out my [CV]({% link cv.md %}).

Get in touch with me via [email](mailto:jimstephaniuk@gmail.com) 📧

### Blog posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
