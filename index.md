---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<ul>
{% for country in site.data.countries %}
<li>{{ country.name }}</li>
{% endfor %}
</ul>
