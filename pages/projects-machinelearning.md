---
layout: page-fullwidth
subheadline:  "Machine learning"
title:  "Machine learning"
teaser: "This page give an overview about machine learning projects around human disease and phenotypes"
breadcrumb: true
categories:
    - projects
permalink: /projects/machinelearning/
header:
    image_fullwidth: "header_unsplash_8.jpg"
image:
    thumb: "header_unsplash_8.jpg"
---


We are applying several machine learning methods to better understand rare and common human diseases and the interrelation between different diseases.

We have used Support Vector Machines to identify disease-relevant proteins from Protein-Interaction Networks. 

We have adopted bayesian learning and applied it to phenotype ontologies to create a tool for the differential diagnosis. In principle this method is applicable to any set of items that have been annotated with the classes of an ontology.

For example we have create a network, with the nodes representing Mendelian diseases and the edges representing phenotypic similarity calculated by ontological similarity measures.


<figure>
	<img src="{{ site.url }}{{ site.baseurl }}/images/disease-net.png" style="display: table-caption; margin: 0 auto;" width="70%" alt="Ontolgies for constructing networks of diseases" itemprop="image">
	<figcaption class="text-right">A network of diseases based on ontological similarity in HPO.</figcaption>
</figure>

Such networks can be used for several bioinformatics problems, such as analysis of GWAS results. 

We often use Ensemble methods for integrating different predictions made with different machine learning methods and from different data sources.


