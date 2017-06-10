<h2>Projects</h2>
<ul>
{% for page in site.projects %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}  <!-- page -->
</ul>
