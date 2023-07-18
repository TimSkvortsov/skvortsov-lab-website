---
title: Contact us
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}How to find us

We are based at the School of Pharmacy, Queen's University Belfast. If you would like to get in touch, please use the contact details below. If you prefer to visit us in person, please see the map at the bottom of the page.

{%
  include button.html
  type="email"
  text="t.skvortsov@qub.ac.uk"
  link="t.skvortsov@qub.ac.uk"
%}
{%
  include button.html
  type="twitter"
  text="@timskvortsov"
  link="https://twitter.com/timskvortsov"
%}
{%
  include button.html
  type="linkedin"
  text="TimSkvortsov"
  link="https://www.linkedin.com/in/timofey-skvortsov"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/hnACmhLNwUfvyZvC6"
%}


{% include section.html %}
<h2 class="center">Our address</h2>
<p class="center">
Room 03.013, McClay Research Centre<br> 
School of Pharmacy, Queen's University Belfast<br> 
97 Lisburn Road, Belfast BT9 7BL, Northern Ireland, UK<br>
</p>

<iframe src="https://www.google.com/maps/embed?pb=!3m2!1sen!2suk!4v1687938404343!5m2!1sen!2suk!6m8!1m7!1suFv7XpnaIotmBrNqc3IZ9A!2m2!1d54.58648951327463!2d-5.942735977660377!3f243.37527671740742!4f5.574387228770917!5f0.7820865974627469" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

{%- comment -%}
{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
{%- endcomment -%}