## Lib Dem Style Charts (2023 Local Elections)

{% assign section_tag = "libdem_chart_2023" %}

<ul>
  {% for post in site.tags.libdem_chart_2023 %}
  {% assign image_path = "/assets/" | append: section_tag | append: "/" | append: post.post_asset %}
    <li><img style="max-width: 256px; max-height: 192px" src="{{ image_path }}"><h3>{{ post.title }}</h3> {{ post.summary }} <span>{{ post.size }}</span></li>
  {% endfor %}
</ul>