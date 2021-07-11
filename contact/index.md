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
  link="https://www.google.com/maps/place/That+St+%26+The+Other+St,+Porters+Lake,+NS+B3E+1H3,+Canada/@44.7389237,-63.3033296,20.78z/data=!4m5!3m4!1s0x4b5a31023bb02565:0xb9505694e83a53d7!8m2!3d44.7389353!4d-63.3030828"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

That St & The Other St  
Porters Lake, NS B3E 1H3  
Canada
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
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
