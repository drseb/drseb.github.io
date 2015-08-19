---
layout: page
subheadline:  "Extracting labels"
title:  "OWL-API for extracting labels"
teaser: "Extracting labels using OWL-API"
categories:
    - ontologies
    - owlapi
tags:
    - ontologies
    - owlapi
header: no
---

If you have an OWL class with label L1. This class has some annotation X and this annotation X is itself annotated with a label L2, this will cause problems
with OWL-API 4.1.0 RC2. The reason is that <code>EntitySearcher</code> will return L1 and L2 and there is no way to distinguish the labels.

Here is Iganzio's reply:
<cite>
There was an issue reported about this, the problem is that getAnnotations() 
collects annotations on annotation axioms as well. Use getAnnotationObjects() 
available in the latest version4 branch. There is a RC 4 build available on 
Sonatype - to be released soonish.
</cite>

I am waiting for version RC4!

### Other owlapi posts
{: .t60 }

{% include list-posts.html tag='owlapi' %}
