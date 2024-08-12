---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

SCUBA Lab is affiliated with the [SeaTech]{https://www.fau.edu/engineering/ome/labs-centers/seatech/} within the Ocean and Mechanical Engineering Department ([OME]{https://www.fau.edu/engineering/ome/}) at Florida Atlantic University (FAU).

{%
  include button.html
  type="email"
  text="pmukherjee@fau.com"
  link="pmukherjee@fau.com"
%}
{%
  include button.html
  type="phone"
  text="(612) 707-5435"
  link="+1-612-707-5435"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Florida+Atlantic+University-SeaTech/@26.0550363,-80.1132633,4510m/data=!3m1!1e3!4m6!3m5!1s0x88d9aab85f81c4db:0x8613c6b78878fab1!8m2!3d26.0550363!4d-80.1132633!16s%2Fg%2F1ts3gdtp?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

<!-- {%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%} -->

{% endcapture %}

{% capture col2 %}

<!-- {%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%} -->

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}



{% capture col2 %}
101 N Beach Rd, 
Dania Beach, 
FL 33004
{% endcapture %}


{% include cols.html col1=col1 col2=col2 col3=col3 %}
