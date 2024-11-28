---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our current research works focus on Medical Robotics, Soft Robotics and Mechatronics in Medicine.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'rf'" %}
{% include list.html data="members" component="portrait" filter="role == 'ra'" %}


{% include section.html background="images/background.jpg" dark=true %}
## Gallery
{% include section.html %}

{% capture content %}

{% include figure.html image="images/group photo1.jpg" %}
{% include figure.html image="images/group photo2.jpg" %}
{% include figure.html image="images/group photo3.jpg" %}


{% endcapture %}

{% include grid.html style="square" content=content %}
