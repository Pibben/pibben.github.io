<h2>Projects</h2>
<ul>
{% for page in site.projects %}
  <li><a href="{{ page.title }}">{{ page.url }}</a></li>
{% endfor %}  <!-- page -->
</ul>
