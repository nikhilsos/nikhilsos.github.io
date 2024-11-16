---
title: "Pine Wilt Disease Segmentation with Deep Metric Learning Species Classification for Early-Stage Disease and Potential False Positive Identification"
collection: publications
category: manuscripts
permalink: https://www.mdpi.com/2079-9292/13/10/1951
excerpt: ' This study presents a method for Pine Wilt Disease detection and classification. We worked on orthomapped images from drones as input. In case of PWD, the diseased objects have close remblance to other natural objects which causes usual methods to have very high false positives, and also there is high similarity in the different species of trees the PWD affects. The objective was to segment the diseased areas but also infer the class of the species affected. So we used YOLOv8 for segmenting diseased areas, followed by cropping the diseased regions from the original image with sufficient background context and applying Deep Metric Learning for classification. Using a ResNet50 model with semi-hard triplet loss to obtain embeddings, and subsequently trained a Random Forest classifier, we got better results than using multi class segmentation using YOLOv8'
date: 16 May 2024
venue: 'Electronics, MDPI'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.