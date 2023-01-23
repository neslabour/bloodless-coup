## Lib Dem Style Charts (2023 Local Elections)

{% assign section_tag = "libdem_chart_2023" %}

<ul>
  {% for post in site.tags.libdem_chart_2023 %}
  {% assign image_path = "/assets/" | append: section_tag | append: "/" | append: post.post_asset %}
    <li><img style="max-width: 256px" src="{{ image_path }}">{{ post.title }} - {{ post.summary }} - {{ post.size }} - {{ post.post_asset }} - {{ image_path }}</li>
  {% endfor %}
</ul>