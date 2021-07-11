---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our lab is part of the [Department of Chemical Engineering](), at the [Samuel Gin College of Engineering]().
We are located on the 1st floor of the _ building.

{%
  include link.html
  type="email"
  icon=""
  text="pmistriotis@auburn.edu"
  tooltip=""
  link="pmistriotis@auburn.edu"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="(555) 555-5555"
  tooltip=""
  link="+1-555-555-5555"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/Auburn+University+Department+of+Chemical+Engineering/@32.6054842,-85.4835017,321m/data=!3m1!1e3!4m5!3m4!1s0x888cf31c9dd90d99:0xc9c6a8d52b04ca1a!8m2!3d32.6050944!4d-85.4838409?hl=en"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

149 Ross Hall  
Auburn AL, 36830 
United States of America
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/auburn_campus.jpg"
  caption="Auburn University"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/rosshall.jpeg"
  caption="Department of Chemical Engineering"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
