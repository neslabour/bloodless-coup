## Lib Dem Style Charts (2023 Local Elections)

<ul>
  {% for post in site.tags.libdem_chart_2023 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.summary }}</li>
  {% endfor %}
</ul>