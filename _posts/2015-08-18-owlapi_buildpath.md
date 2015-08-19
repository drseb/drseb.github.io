---
layout: page
subheadline:  "Build path problems with OWL-API"
title:  "OWL-API 4.1.0 RC2"
teaser: "Just spend several hours fixing a build path problem... pheww"
categories:
    - ontologies
    - owlapi
tags:
    - ontologies
    - owlapi
header: no
---

Be sure you don't have any other libraries in your build path that may use a different version of OWLAPI. In my case, it was the wrong ELK version
in my build path, which leads to very mysterious errors such as:
<pre>Exception in thread "main" java.lang.NoSuchMethodError: 
  org.semanticweb.owlapi.model.PrefixManager.setPrefix(Ljava/lang/String;Ljava/lang/String;)V
</pre>

See also [this thread](http://sourceforge.net/p/owlapi/mailman/owlapi-developer/thread/CAD2jOMNsHZwTEKmQ53884rCgijy%2Bkt%2BLJ_u_oFbvUZ1SSGgJFw%40mail.gmail.com/#msg34384274) from the
OWL API mailing list.

I am nervously wating for version RC4.

### Other owlapi posts
{: .t60 }

{% include list-posts.html tag='owlapi' %}
