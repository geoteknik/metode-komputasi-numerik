---
id: Materi
name: Materi
heading: Materi
subheading: 

---

<ul>
{% for article in site.pages %}
  {% if article.identifier == 'page' %}
      <a class="my-link" href="{{ site.baseurl}}{{article.url }}">
        {{ article.title }}
      </a>
  {% endif %}
{% endfor %} 
</ul>


<!-- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="img-skill"> -->
          
          