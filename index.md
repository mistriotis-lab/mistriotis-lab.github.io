---
title: Home
---

# Under construction

This is the [website](https://mistriotis-lab.github.io/) of Mistriotis Laboratory at Auburn University.
 
{%
  include link.html
  type=""
  icon=""
  text="See Auburn University's website"
  link="https://auburn.edu/"
  style="button"
%}
{%
  include link.html
  type=""
  icon=""
  text="See our Department's website"
  link="https://www.eng.auburn.edu/chen/"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/Group-photo.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
Our research lies at the interface of engineering, biophysics, cell & molecular biology and biochemistry with applications in aging, vascular diseases and cancer metastasis.

[Learn more about our research &nbsp;→](research)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  headline="Our Research"
  text=text
%}

{% capture text %}
Our lab is part of the Department of Chemical Engineering, at the Samuel Gin College of Engineering.

[See our resources &nbsp;→](resources)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  headline="Our Resources"
  text=text
%}

{% capture text %}
Learn more about the members of Mistriotis Lab.

[Meet our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  headline="Our Team"
  text=text
%}
