---
---

# Welcome to Violet's Website



{% include section.html %}

## Highlights

{% capture text %}

Hi everyone! My name is Violet, and I am a recent graduate of the Institute for Advanced Analytics (IAA) at North Carolina State University.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
