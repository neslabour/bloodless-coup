## Video Files

These files can be downloaded and shared via Social Media or used in other ways. 

{% assign section_tag = "video" %}

<ul>
  {% for post in site.tags.video %}
  {% assign image_path = "/assets/" | append: section_tag | append: "/" | append: post.post_asset %}
    <li style="list-style-type: none; margin: 0; padding: 0; vertical-align: top;">
    	<h3>{{ post.title }}</h3>    	
    	<video width="320" height="240" controls>
  			<source src="{{ image_path }}" type="video/mp4">
    	</video>
    	<p style="vertical-align: top; display: inline;">{{ post.summary }}</p>
    	<br>
    	<a href="{{ image_path }}" style="vertical-align: top; display: inline; font-size: 11px; font-weight: 600;" download="{{ post.title | append: ".png" }}">[Download]</a></li>
  {% endfor %}
</ul>
