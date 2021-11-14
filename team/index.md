---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team


{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{:.center}
{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

The Mistriotis Lab is always looking for qualified Ph.D. candidates. Competitive candidates with a strong academic performance, creativity, and passion are encouraged to apply. For program information and application, click [here](https://eng.auburn.edu/chen/academics/graduate/index.html).

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

