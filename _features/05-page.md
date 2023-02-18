---
id: Page Posts
name: Page Posts
heading: Page Posts
subheading: 

---
<ul>
  {% for article in site.pages %}
    {% if article.identifier == 'page' %}
      <li>
        <a href="{{ site.baseurl}}{{article.url }}">
          {{ article.title }}
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>


<!-- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="img-skill"> -->
          
          