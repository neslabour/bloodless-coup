## Lib Dem Style Charts (2023 Local Elections)

{% assign section_tag = "libdem_chart_2023" %}

<ul>
  {% for post in site.tags.libdem_chart_2023 %}
  {% assign image_path = "/assets/" | append: section_tag | append: "/" | append: post.post_asset %}
    <li style="list-style-type: none; margin: 0; padding: 0; vertical-align: top;"><h3>{{ post.title }}</h3><img style="max-width: 256px; max-height: 192px" src="{{ image_path }}"> {{ post.summary }} <span style="background-color: rgb(225, 236, 244); border-bottom-color: rgba(0, 0, 0, 0); border-bottom-left-radius: 3px; border-bottom-right-radius: 3px; border-bottom-style: solid; border-bottom-width: 1px;">{{ post.size }}</span> <a href="{{ image_path }}" download="{{ post.title | append: ".png" }}">[Download]</a></li>
  {% endfor %}
</ul>
