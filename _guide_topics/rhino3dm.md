---
title: Rhino3dm Guides
description: A geometry library available for many platforms.
authors: unset
author_contacts: unset
sdk: unset
languages: ['Python', 'JavaScript', 'C#']
platforms: ['Windows', 'Mac']
categories: ['Unsorted']
origin: unset
order: 1
keywords: ['rhino', 'developer']
layout: guide-homepage
---

<!--the .snagit project for this image can be found next to the image -->
[<img src="{{ site.baseurl }}/images/rhinopython-guides-col1.png">]({{ site.baseurl }}/guides/rhinopython/what-is-rhinopython/)

### Overview

<div class="trigger">
  {% assign guides = site.guide_topics | sort:"order" %}
  <ul>
  {% for guide in guides %}
    {% if guide.sdk contains 'Rhino3dm' and guide.categories contains 'Overview' %}
      {% if guide.title and guide.order %}
        <li><a class="page-link" href="{{ guide.url | prepend: site.baseurl }}" title="{{ guide.description }}">{{ guide.title }}</a></li>
      {% endif %}
    {% endif %}
  {% endfor %}
  </ul>
</div>

### Getting Started

- Your First Python Script in Rhino ([Windows]({{ site.baseurl }}/guides/rhinopython/your-first-python-script-in-rhino-windows), [Mac]({{ site.baseurl }}/guides/rhinopython/your-first-python-script-in-rhino-mac), [Grasshopper]({{ site.baseurl }}/guides/rhinopython/your-first-python-script-in-grasshopper))
- [Where to get help...]({{ site.baseurl }}/guides/rhinopython/python-where-to-find-help)
- [Troubleshooting Installation]({{ site.baseurl }}/guides/rhinopython/python-troubleshooting-install)
- [Developer samples on GitHub](https://github.com/mcneel/rhino-developer-samples)
- [Scripting discussions on Discourse](https://discourse.mcneel.com/c/scripting)



<!--column-->

<!--the .snagit project for this image can be found next to the image -->
[<img src="{{ site.baseurl }}/images/rhinopython-guides-col2.png">](https://docs.python.org/2/tutorial/index.html)



<!--column-->

<!--the .snagit project for this image can be found next to the image -->
[<img src="{{ site.baseurl }}/images/rhinopython-guides-col3.png">](http://www.rhino3d.com/download/IronPython/5.0/RhinoPython101)



<!--column-->

<!--the .snagit project for this image can be found next to the image -->
[<img src="{{ site.baseurl }}/images/rhinopython-guides-col3.png">](http://www.rhino3d.com/download/IronPython/5.0/RhinoPython101)
