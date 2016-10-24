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
          <h1>A view of our project</h1>
          <p>We've been snapping away over the course of the project, check out our snaps below!</p>
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
	<a href="{{ site.baseurl }}/galleries/{{ gallery.id }}">
        <h1>[{{ gallery.description }}]</h1><br />
	</a>
        {% endfor %}
      </div>
    </div>
  </div>
</div>
