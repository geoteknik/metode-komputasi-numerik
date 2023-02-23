---
id: Blog Posts
name: Blog Posts
heading: Blog Posts
subheading: 

---
<ul>
  {% for post in site.posts %} 
      <a class="my-link" href="{{ site.baseurl}}{{post.url }}">{{ post.title }}</a> 
  {% endfor %}
</ul>


<!-- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="img-skill"> -->
          
          