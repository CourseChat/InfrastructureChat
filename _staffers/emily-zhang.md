---
name: Emily Zhang
role: Teaching Assistant
email: zhangqinglai0120@berkeley.edu
website: https://kevinl.info
photo: emily-1024x1024.jpg
---
{% assign external_image = site.external-images | where: "title", "Emily Zhang" | first %}
{% if external_image %}
  <img src="{{ external_image.image_url }}" alt="{{ external_image.title }}">
{% endif %}

Emily
