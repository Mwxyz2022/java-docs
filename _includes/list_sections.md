{% assign sorted_pages = site.pages | sort: "nav_order" %}
{% for page in sorted_pages %}
{% if page.parent == 'Головна Сторінка Конспектів Java' and page.has_children %}
- [{{ page.title }}]({{ page.url | relative_url }})
  {% endif %}
  {% endfor %}