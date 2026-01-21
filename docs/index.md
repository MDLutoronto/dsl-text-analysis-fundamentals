---
title: "Text Analysis Fundamentals with the Digital Scholar Lab"
layout: "home"
description: ""
permalink: "/"  #! Remove this if not the homepage
---

# Text Analysis Fundamentals with the Digital Scholar Lab

This tutorial introduces[Gale's Digital Scholar Lab](https://mdl.library.utoronto.ca/technology/text-data-mining-software/gale-digital-scholar-lab) (DSL), a digital humanities tool. In this tutorial, you will learn how to:

* Build a collection of texts, including uploading your own materials
* Create collaborative workspaces
* Clean texts
* Run analytical tools on texts and visualize the results
* Download the data, graphs, and other visualizations produced through this tool
* Download the scanned texts in your collection, so that you can use them in other programs
* Find additional training and resources

*Note: Gale periodically updates the Digital Scholar Lab, so some features of this tutorial might not always match the latest interface. This tutorial was last updated in March 2023\.*

Table of Contents
=================

Our tutorial for the Digital Scholar Lab (DSL) includes the introductory page you are reading, plus seven major sections. Click on any of the links below to jump to the relevant tutorial. We suggest following them in order:

1. [Access](https://mdl.library.utoronto.ca/technology/tutorials/logging-digital-scholar-lab-through-catalog)
2. [Collaboration and Notes](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-collaboration-and-notes)
3. [Collections](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-collections)
4. [Cleaning](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-cleaning)
5. [Analysis](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-analysis)
6. [Export](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-export)
7. [Additional training](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-additional-training)

**Access** covers how to find and log into the DSL.  
**Collaboration and Notes,**an optional guide, shows you how to create team workspaces.  
**Collections**includes uploading your own texts and using advanced search options to locate primary sources from Gale.  
**Cleaning**discusses how to prepare your texts for best results.  
**Analysis**covers the DSL's six tools in detail.  
**Export**shows you how to export data, graphs, and full texts.  
**Additional training**includes resources from Gale, including sample projects and recorded webinars.

What is Gale Digital Scholar Lab?
---------------------------------

The Digital Scholar Lab (DSL) is an online tool for analyzing texts, visualizing the results, and exporting data, graphs, and texts from the platform. You can access a variety of primary sources (newspaper articles and archival documents such as books, pamphlets, reports, and ephemera), as well as upload your own tets. It runs in your Internet browser and does not need any additional software. You do not need to know any coding to use this tool.

The DSL has six analysis tools:

1. Document Clustering
2. Named Entity Recognition
3. Ngrams
4. Parts of Speech
5. Sentiment Analysis
6. Topic Modeling

The DSL makes it easier to learn and understand how these tools work by providing user\-friendly graphical user interfaces, documentation, and demonstration videos. External links to the code or programs behind each tool are also made available should you wish to run the tool on your own computer and use its more advanced features.

What collections does it have?
------------------------------

When you use the DSL through your University of Toronto connection, you can use any of the Gale primary source collections that the University has licensed, including hundreds of thousands of documents in multiple languages with broad historical and geographical coverage. (Once you are logged in, see [these instructions to view all accessible collections](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-additional-training#available_texts).) Extensive coverage, however, should not be confused with universal coverage; many perspectives are not represented in these text collections. For example, most of the colonial\-era documents included in these collections were produced and collected by colonizing people, organizations, or institutions, rather than by colonized peoples. It is up to you as a critical scholar to decide on which questions can and cannot be answered by these collections. Note that some are downloadable open source tools whereas others will require knowledge of Python.

Digitization
------------

The texts available in the DSL have gone through several steps: (1\) various institutions like libraries and archives collected the texts; (2\) Gale scanned the text; (3\) through a process called [Optical Character Recognition (OCR)](https://en.wikipedia.org/wiki/Optical_character_recognition)these scans—which are essentially photographs of texts—are converted into readable, searchable text.

OCR uses image\-recognition algorithms to identify characters and create a text file based on the image. OCR is powerful, but it is also prone to errors such as misidentifying characters (e.g. reading a zero as the letter 'O') or adding or removing spaces. There are [additional challenges for scanning older English texts](https://tedunderwood.com/2013/12/10/a-half-decent-ocr-normalizer-for-english-texts-after-1700/), such as those that use the long 's' ('ſ*'*), which resembles a lowercase 'f'. We discuss this process further in the section on Cleaning, but for now it is sufficient to know that this process can often leave errors in the text files produced through OCR.

Where do I find more information and videos on it?
--------------------------------------------------

In addition to the in\-depth tutorials above, we have a variety of pages and videos related to the DSL:

* [Getting started with the Digital Scholar Lab](https://mdl.library.utoronto.ca/technology/tutorials/gale-digital-scholar-lab-information-tutorials-and-workshops)
* [General overview and Frequently Asked Questions](https://mdl.library.utoronto.ca/technology/text-data-mining-software/gale-digital-scholar-lab) (FAQ)
* [Short demo video](https://play.library.utoronto.ca/watch/dcee158db446cb9a2dc4168eccf30f77?t=350)
* [In\-depth recorded workshop](https://play.library.utoronto.ca/watch/59c47c549cf5ddc92a44a346d3662c1f) (with captions and [slides](https://docs.google.com/presentation/d/1F69Q1wq_yjA7blqtDMPdbF6B0ElM4rQwX34Zwmqx6k4/edit?usp=sharing))
* [Additional training from Gale](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-additional-training#Gale_official) (recorded and live webinars)
* [Text Analysis Tools Comparison Cheat Sheet](https://docs.google.com/spreadsheets/d/1ejQ2mBVaa7ETi5zOoQi6wgFJhrJmtHmwb36RA-LBUi0/edit?usp=sharing)(compares the Digital Scholar Lab, Constellate, TDM Studio, and the HathiTrust Research Center)

Who do I contact for more help?
-------------------------------

If you would like help or want to take any of the DSL's tools further in your own analysis, you can always[contact Digital Scholarship Services](https://onesearch.library.utoronto.ca/digital-scholarship/contact-digital-scholarship-services).

Note: if you are experiencing an HTTP 400 error when attempting to log in, please close your browser, reopen, and retry. You may have timed out, which can cause errors on some browsers.

Further Reading
---------------

* D’Ignazio, Catherine, and Lauren F. Klein. [Data Feminism](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/14bjeso/alma991106734515806196). MIT Press, 2020\.
* Gitelman, Lisa. [“Raw Data” Is an Oxymoron](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/14bjeso/alma991106190587006196). Infrastructures Series. Cambridge, Mass: The MIT Press, 2013\.
* Loukissas, Yanni A. [All Data Are Local: Thinking Critically in a Data\-Driven Society](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/fedca1/cdi_askewsholts_vlebooks_9780262352222). Cambridge, Massachusetts: The MIT Press, 2019\.
* Onuoha, Mimi, Sparshith Sampath, Myles Braithwaite, and Corin Faife. On Missing Data Sets, 2018\. [https://github.com/MimiOnuoha/missing\-datasets](https://github.com/MimiOnuoha/missing-datasets).
* Posner, Miriam. “Humanities Data: A Necessary Contradiction.” Miriam Posner’s Blog, June 25, 2015\. [https://miriamposner.com/blog/humanities\-data\-a\-necessary\-contradiction/](https://miriamposner.com/blog/humanities-data-a-necessary-contradiction/).

See also our [bibliography of works that critically analyze data studies](https://mdl.library.utoronto.ca/support/guides/critical-data-and-maps-equity-diversity-and-inclusion-edi), mapping and GIS from antiracist, feminist, queer, LGBTQIA2S\+ and Indigenous perspectives.

Technique: [Text and Data Mining](/technique/text-and-data-mining), [Cleaning data](/technique/cleaning-data), [Extracting data](/technique/extracting-data) \| Tools: [Digital Scholar Lab](/tools/digital-scholar-lab-0)**Date Created:** 2020\-04\-21**Updated:** 2025\-12\-18
