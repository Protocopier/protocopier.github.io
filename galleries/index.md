---
layout: default
title: Gallery
---
<!-- Slider Start -->
<section id="global-header">
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <div class="block">
          <h1>Drop Us A Note</h1>
          <p>Don’t just take our word for it. Get in touch to know more about the protocopier project.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!--Gallery Start -->
<div class="container">
  <div class="row">
    <div class="col-md-12">
      <div class="block">
	<h1>Our Photos</h1>
        {% for gallery in site.data.galleries %}
        - [{{ gallery.description }}]({{ gallery.id }})
        {% endfor %}
      </div>
    </div>
  </div>
</div>
