---
title: Home
---

# Harnessing the world's deadliest animal

A central question in neurobiology is how animal behavior and decision making is controlled. Using CRISPR/Cas9, optogenetics, electrophysiological, biochemical and cell biological approaches in the fruit fly, Drosophila melanogaster, and in the mosquito, Aedes aegypti, our laboratory is defining the neuronal mechanisms that impact on decisions ranging from food selection to choosing the ideal thermal landscape, mate selection and others. As part of this endeavor, we are also deciphering polymodal sensory roles of TRP channels, gustatory receptors, ionotropic receptors and rhodopsins, and defining the behaviors that they control. The goal of our most recent work on the mosquito vector, Aedes aegypti, is too control infectious diseases such as Dengue, Zika and others that affect hundreds of millions of people each year.



{%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
Our team publisehss blah blah blah

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  title="Our Protocols"
  flip=true
  text=text
%}

{% capture text %}
We have designed state of the art protocols for a variety of techniques and assays

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
