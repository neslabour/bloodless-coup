## Lib Dem Style Charts (2023 Local Elections)

{% assign section_tag = "libdem_chart_2023" %}

<ul>
  {% for post in site.tags.libdem_chart_2023 %}
    <li><img src="/assets/{{ section_tag }}/{{ page.asset }}"><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.summary }}</li>
  {% endfor %}
</ul>