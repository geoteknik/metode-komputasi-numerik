---
id: Numerical Skills
name: Numerical Skills
heading: Numerical Skills
subheading: 
images: 
- "assets/media/pic/svg/fem.svg" 
- "assets/media/pic/svg/sph.svg" 
- "assets/media/pic/svg/fvm.svg" 
- "assets/media/pic/svg/fdm.svg" 
- "assets/media/pic/svg/dem.svg" 
- "assets/media/pic/svg/flip.svg" 
skill: 
- Finite Element Method (FEM)
- Smoothed Particle Hydrodynamics (SPH)
- Finite Volume Method (FVM)
- Finite Different Method (FDM)
- Discrete Element Method (DEM)
- Fluid Implicit Particle (FLIP)
---

<div class="row ">
    {% for i in (0..6) %}
    <div class="col-sm-3 item-center">
        <img src="{{ page.images[i] }}" class="img-skill " alt="{{ page.skill[i] }}"> 
        <div class="text-center">
            &nbsp;
        </div>
    </div> 
    {% endfor %}
</div>


<!-- <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" class="img-skill"> -->
          
          