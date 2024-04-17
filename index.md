Hi there 👋 
I'm James Stephaniuk, a software developer interested in Bitcoin, distributed systems, and Austrian economics.

This is a showcase site of my professional work and writings.

Check out my [CV]({% link cv.md %}) for more on what I've been up to.

Get in touch with me via [email 📧](mailto:jimstephaniuk@gmail.com)

### Blog posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
