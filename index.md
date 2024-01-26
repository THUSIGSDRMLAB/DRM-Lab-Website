---
carousels:
  - images: 
    - image: /images/carousel/QuanTi1.jpg
    - image: /images/carousel/QuanTi2.jpg
---

# THUSIGSDRMLAB's Website

Shenzhen International Graduate School of Tsinghua University, Shenzhen Information Security and Digital Content Protection Technology Engineering Laboratory ( referred to as DRM) was established in 2008, and was approved by Shenzhen Development and Reform Commission to build a special Internet project in 2012. DRM's research area covers four first-level disciplines in our institute, namely, electronic science and technology, information and communication engineering, computer science and technology, and control science and engineering, and it mainly conducts research in the direction of communication in the medical field, system chip integrated circuit design, and new generation network. DRM conducts research in the direction of communication, system-on-chip integrated circuit design and new generation network in the medical field, and at the same time carries out research on application technology, key technology and transformation of technological achievements.
DRM has undertaken more than 20 national major projects and industrial projects in the past three years. DRM has applied for more than 40 national and international invention patents, and is responsible for, and has won 3 provincial and ministerial awards such as the Science and Technology Award of Broadcasting and Television, and has formulated 15 relevant standards in the field of medical equipment and broadcasting and television, and has published more than 40 high-level papers. DRM's UTI machine-card separation, content protection, anti-counterfeiting traceability and other DRM's scientific research achievements in UTI card separation, content protection, anti-counterfeiting traceability, etc. have generated sales of over ten million in China, and many of the scientific research achievements of its medical projects have been clinically applied in more than six thousand cases in many tertiary hospitals and their medical associations.

{% include section.html %}

{% include section.html full=true %}

{% include carousel.html height="40" unit="%" duration="10" number="1" %}

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
