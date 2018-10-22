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

- Using Rhino3dm.py in CPython(Windows/Mac)
- Referencing the Rhino3dm.js with JavaScript (all major browsers/node.js)
- Starting with Rhino3dm.cs using C# (.NET)
- Developer for mobile usngin RhinoMobile
- Developer samples on GitHub
- Scripting discussions on Discourse


<!--column-->

<!--the .snagit project for this image can be found next to the image -->
[<img src="{{ site.baseurl }}/images/rhinopython-guides-col2.png">](https://docs.python.org/2/tutorial/index.html)

### Fundamentals

- The OpenNurbs Kernel
- Objects in Rhino3DM
- Points and Pointclouds
- Lines and Polylines
- Nurbs-curves
- Planes
- Circles, Ellipses and...
- Meshes
- Surfaces
- Poly-surfaces (BREPS)

### Additional Properties

- Getting Object Attributes
- Vectors
- Matrix Arithmetic
- User-Data
- Document
- Layers
- Annotation
- Vieports
- Materials

### Geometry Evaluation

- Transforms
- Simple Object interaction
- Matrix Math
- Spacial Decompensition (R-tree)


<!--column-->

<!--the .snagit project for this image can be found next to the image -->
[<img src="{{ site.baseurl }}/images/rhinopython-guides-col3.png">](http://www.rhino3d.com/download/IronPython/5.0/RhinoPython101)

### Intermediate

- Brep Loop & Edge Directions
- Importing Lightweight Extrusions
- Periodic Curves & Surfaces
- Reading Render Meshes
- Superfluous Knots
- Traversing Instance Definitions
- Reading and writing the 3dm file format
- Using Rhino.Compute
- Blocks and Instances
- Reading Per-Face Render Materials
- Testing for Object Visibility
- Developer samples on GitHub
- Scripting discussions on Discourse

### Samples

- Using Rhino3dm.py in CPython(Windows/Mac)
- Referencing the Rhino3dm.js with JavaScript (all major browsers/node.js)
- Starting with Rhino3dm.cs using C# (.NET)
- Developer samples on GitHub
- Scripting discussions on Discourse

### Other Resources

- Using Rhino3dm.py in CPython(Windows/Mac)
- Referencing the Rhino3dm.js with JavaScript (all major browsers/node.js)
- Starting with Rhino3dm.cs using C# (.NET)
- Developer samples on GitHub
- Scripting discussions on Discourse

<!--column-->

<!--the .snagit project for this image can be found next to the image -->
[<img src="{{ site.baseurl }}/images/rhinopython-guides-col3.png">](http://www.rhino3d.com/download/IronPython/5.0/RhinoPython101)
