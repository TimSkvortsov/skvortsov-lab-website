---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Current lab members



{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait-nonpi" filters="role: phd " %}



{% include section.html %}
<h2 class="center">Our alumni</h2>

{% include list.html data="members" component="portrait-nonpi" filters="role: alumnus" %}