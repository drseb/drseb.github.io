---
layout: page-fullwidth
subheadline:  "Random walks and related"
title:  "Networks"
teaser: "This page give an overview about my work on complex network analysis in the life science domain."
breadcrumb: true
categories:
    - projects
permalink: /projects/networks/
header:
    image_fullwidth: "header_unsplash_8.jpg"
image:
    thumb: "header_unsplash_8.jpg"
---


Complex network analysis is an important field in the life science domain. Especially protein-protein interaction 
networks are an important tool for present-day biology and bioinformatics. Proteins do seldomly perform their function in isolation. Protein-protein interactions are the key determinants 
for cellular protein complexes, pathways, and others. 
Mining protein interaction networks - often containing more than 15.000 nodes - requires computational methods, often developed in the context of complex network analysis.

Determining the similarity between two proteins based on their relative location in the protein interaction network is often hampered by the
discrete nature of networks. In the simplest setting, two proteins can have a shortest-path distance of one, two, three, four... but seldomly more than five. Thus we
have employed a random-walk based method for calculating the similarity between proteins.
 
<figure>
	<img src="images/rw.png" width="100%" alt="Random walk for similarity calculations" itemprop="image">
	<figcaption class="text-right">Random walk for similarity calculations</figcaption>
</figure>

In the figure one can see how a random-walk based method can distinguish (increased similarity score) when two nodes are connected by increasing number of paths in the network - especially
in situations where the shortest-path distance is constant (here two).
The method we employed is very ineresting as it allows to calculate the similarity between multiple start-nodes and all other nodes in the network. We have applied this method to the problem of disease gene identification and had a remarkable success. The [publication](https://scholar.google.com/citations?view_op=view_citation&hl=de&user=fqukiWoAAAAJ&citation_for_view=fqukiWoAAAAJ:Tyk-4Ss8FVUC) has been cited more that 450 times according to Google Scholar.