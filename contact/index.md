---
title: Contact
nav:
  order: 4
  tooltip: Email & LinkedIn
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you're interested in learning more about me or just want to chat about cats, marathon training, or solo traveling, feel free to reach out via email or LinkedIn below. Let’s connect!

{%
  include button.html
  type="email"
  text="vwevans at alumni.unc.edu"
  link="vwevans@alumni.unc.edu"
%}

{%
  include button.html
  type= "link"
  text="My LinkedIn Profile"
  link="https://www.linkedin.com/in/violet-wen-evans/"
%}

{% capture col1 %}
{%
  include figure.html
  image="images/team antares.jpg"
  caption="NCSU Practicum Team Blue 8"
%}
<style>
  img {
    max-width: 250px;
    max-height: 300px;
  }
</style>
{% endcapture %}

{% capture col2 %}
{% 
  include figure.html image="images/IMG_3917.jpg"
  caption="NCSU Summer Practicum Team"
%}
<style>
  img {
    max-width: 250px;
    max-height: 300px;
  }
</style>
{% endcapture %}

{% capture col3 %}
{% 
  include figure.html image="images/Violet Evans.jpg"
  caption="Shaking Dr. Rappa's Hand at Graduation"
%}
<style>
  img {
    max-width: 250px;
    max-height: 300px;
  }
</style>
{% endcapture %}

{% include section.html dark=true %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
