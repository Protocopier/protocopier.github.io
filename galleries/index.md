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
	<h1>Our Galleries</h1>
        {% for gallery in site.data.galleries %}
	<h2>{{ gallery.id }}</h2>
	<a href="{{ site.baseurl }}/galleries/{{ gallery.id }}" title="{{ gallery.description }}">
	<img src="{{ site.baseurl }}{{ gallery.imgfolder }}/cover.jpg" style="width: 25em">
	</a>
        {% endfor %}
      </div>
    </div>
  </div>
</div>
