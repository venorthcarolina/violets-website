---
title: Contact
nav:
  order: 4
  tooltip: Email and LinkedIn
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

As a recent graduate of the Institute for Advanced Analytics at North Carolina State University (NCSU) with an M.S. in Analytics, I am enthusiastic about applying my statistics and data science knowledge to explore organizations that leverage big data to tackle pressing challenges. I also have undergraduate experience in biostatistics, health equity, and research from UNC Chapel Hill. 

If you'd like to chat more, please feel free to contact me at my email or LinkedIn below. Let’s connect!


{%
  include button.html
  type="email"
  text="vwevans at alumni.unc.edu"
  link="vwevans@alumni.unc.edu"
%}

{%
  include button.html
  type= "LinkedIn"
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

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
