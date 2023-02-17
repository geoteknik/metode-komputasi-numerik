---
id: Teaching
name: Teaching
heading: Teaching
subheading: 

---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl}}{{post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


<!-- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="img-skill"> -->
          
          