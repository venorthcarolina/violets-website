---
title: Contact
nav:
  order: 4
  tooltip: Email & LinkedIn
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you'd like to learn more about me, or simply chat about cats, marathon training, or solo traveling, please feel free to contact me via email or LinkedIn below. Let’s connect!

{%
  include button.html
  type="email"
  text="vwevans at alumni.unc.edu"
  link="vwevans@alumni.unc.edu"
%}

{%
  include button.html
  type= "button"
  tooltip="LinkedIn"
  link="https://www.linkedin.com/in/violet-wen-evans/"
%}


{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/team antares.jpg"
  caption="NCSU Practicum Team Blue 8"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/IMG_3917.jpg"
  caption="NCSU Summer Practicum Team"
%}

{% endcapture %}

{% include section.html dark=true %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
