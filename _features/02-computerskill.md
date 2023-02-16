---
id: Computer Skills
name: Computer Skills
heading: Computer Skills
subheading: 
images:
- "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg"
- "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg"
- "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"
- "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"
- "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg"
- "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"
- "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" 
- "assets/media/pic/svg/fem.svg" 
skill:
- C++
- C
- Python
- Git
- Linux
- Html
- Javascript
- FEM
---

<div class="row ">
    {% for i in (0..6) %}
    <div class="col-lg-3 item-center">
        <img src="{{ page.images[i] }}" class="img-skill "> 
        <div class="text-center">
            {{ page.skill[i] }}
        </div>
    </div> 
    {% endfor %}
</div>


<!-- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="img-skill"> -->
          
          