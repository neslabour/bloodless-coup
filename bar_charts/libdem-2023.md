## Lib Dem Style Charts (2023 Local Elections)

{% assign section_tag = "libdem_chart_2023" %}

<ul>
  {% for post in site.tags.libdem_chart_2023 %}
  {% assign image_path = "/assets/{{ section_tag }}/{{ page.post_asset }}" %}
    <li><img style="max-width: 256px" src="{{ image_path }}"><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.summary }} - {{ post.size }} - {{ post.post_asset }}</li>
  {% endfor %}
</ul>