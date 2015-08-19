---
layout: page
subheadline:  "Joining sets of Strings"
title:  "Nice methods to join strings"
teaser: "I often used very unreadable code for joining Strings in Java"
categories:
    - java
tags:
    - guava
    - java
header: no
---

If you ever want to join Strings into a String, where each element is separated by some 'separator', I have
just recently discovered that there are methods for that (embarrassing).

The <code>java.lang.String</code> offers the static method <code>String.join</code>, which you just give a separator and the set of elements. See the [java-doc][1]. 

The google guava library provides a <code>Joiner</code> class. There you just have to call <code>Joiner.on(", ").join(elems);</code>. 
Read the explanations on the [guava page][2].

### Other java posts
{: .t60 }

{% include list-posts.html tag='java' %}


 [1]: https://docs.oracle.com/javase/8/docs/api/java/lang/String.html#join-java.lang.CharSequence-java.lang.Iterable-
 [2]: https://code.google.com/p/guava-libraries/wiki/StringsExplained