---
layout: archive
permalink: /
---

<style>

a {
  color: #e86850;
}

a:hover {
  color: #ffd800;
}

</style>

![main photo](/images/main-photo.jpg)

I am a PhD candidate in the <a href="https://wolfelab.wordpress.com/" target="_blank">Wolfe Lab</a>  at Ohio State University. I study evolutionary genetics looking specifically at the occurrence of polyploidy.
Much of my work involves the development of statistical models to understand population genetic processes in polyploids, as well as trying to untangle the origins of hybrid-derived polyploid taxa. All of my work is done in the genus <a href="https://wolfelab.wordpress.com/penstemon-photo-gallery/" target="_blank"><em>Penstemon</em></a> (Plantaginaceae), which is an amazingly diverse group of plants in North America.


----

#### Posts

<div class="tiles">
{% for post in site.posts %}
   {% include post-list.html %}
{% endfor %}
</div><!-- /.tiles -->
