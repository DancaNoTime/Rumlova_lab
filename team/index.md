---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We believe that great people make great science. Our lab welcomes people of all backgrounds, regardless of nationality, ethnicity, gender, or identity.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/vscht.jpg" dark=true %}

We don't forget about fun either :]

{% include section.html %}

{% capture content %}

{% include figure.html image="images/fun1.jpg" %}
{% include figure.html image="images/fun2.jpg" %}
{% include figure.html image="images/fun3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
