---
layout: page
title: Learn
permalink: /learn/
---
<!-- Slider Start -->
<section id="global-header">
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <div class="block">
          <h1>Getting Started with Protocopier</h1>
          <p>Learn more about the whole process of 3D scanning, modeling, and printing.</p>
        </div>
      </div>
    </div>
  </div>
</section>


 {% for tutorial in site.data.tutorials %}
<div class="post-area">
  
  <a href="https://www.youtube.com/embed/{{ tutorial.youtubeid }}" class="bold">{{ tutorial.title }}</a>
  <p>
  <div style="width:800px; margin:0 auto;">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/{{ tutorial.youtubeid }}" frameborder="0" allowfullscreen></iframe>
	</div>
  <hr/>
    {{ tutorial.description }}
  </p>
  <hr/>
</div>
{% endfor %}



