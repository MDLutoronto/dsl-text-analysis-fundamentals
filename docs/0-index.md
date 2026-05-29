---
title: "Text Analysis Fundamentals with the Digital Scholar Lab"
layout: "home"
description: "This tutorial introduces Gale's Digital Scholar Lab (DSL), a digital humanities tool."
permalink: "/"  #! Remove this if not the homepage
staff:
    - name: Nick Field
      link: https://library.utoronto.ca/staff/nick-field
maintainer:
    - name: Nick Field
      link: https://library.utoronto.ca/staff/nick-field
created_date: 2020-04-21
has_children: true
has_toc: false
nav_order: 0
---

# Text Analysis Fundamentals with the Digital Scholar Lab

This tutorial introduces [Gale's Digital Scholar Lab](https://gale.com/digital-humanities-tools/gale-digital-scholar-lab) (DSL), a digital humanities tool. In this tutorial, you will learn how to:

* Build a collection of texts, including uploading your own materials
* Create collaborative workspaces
* Clean texts
* Run analytical tools on texts and visualize the results
* Download the data, graphs, and other visualizations produced through this tool
* Download the scanned texts in your collection, so that you can use them in other programs
* Find additional training and resources

*Note: Gale periodically updates the Digital Scholar Lab, so some features of this tutorial might not always match the latest interface. This tutorial was last updated in March 2023.*

Table of Contents
=================

Our tutorial for the Digital Scholar Lab (DSL) includes the introductory page you are reading, plus seven major sections. Click on any of the links on the menu to the left to jump to the relevant tutorial. We suggest following them in order:

1. **Access** covers how to find and log into the DSL.  
2. **Collaboration and Notes,** an optional guide, shows you how to create team workspaces.  
3. **Collections** includes uploading your own texts and using advanced search options to locate primary sources from Gale.  
4. **Cleaning** discusses how to prepare your texts for best results.  
5. **Analysis** covers the DSL's six tools in detail.  
6. **Export** shows you how to export data, graphs, and full texts.  
7. **Additional training** includes resources from Gale, including sample projects and recorded webinars.

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

The DSL makes it easier to learn and understand how these tools work by providing user-friendly graphical user interfaces, documentation, and demonstration videos. External links to the code or programs behind each tool are also made available should you wish to run the tool on your own computer and use its more advanced features.

What collections does it have?
------------------------------

When you use the DSL through your University of Toronto connection, you can use any of the Gale primary source collections that the University has licensed, including hundreds of thousands of documents in multiple languages with broad historical and geographical coverage. (Once you are logged in, see [these instructions to view all accessible collections](https://mdlutoronto.github.io/dsl-text-analysis-fundamentals/7.1-see-which-texts-available/).) Extensive coverage, however, should not be confused with universal coverage; many perspectives are not represented in these text collections. For example, most of the colonial-era documents included in these collections were produced and collected by colonizing people, organizations, or institutions, rather than by colonized peoples. It is up to you as a critical scholar to decide on which questions can and cannot be answered by these collections. Note that some are downloadable open source tools whereas others will require knowledge of Python.

Digitization
------------

The texts available in the DSL have gone through several steps: (1) various institutions like libraries and archives collected the texts; (2) Gale scanned the text; (3) through a process called [Optical Character Recognition (OCR)](https://en.wikipedia.org/wiki/Optical_character_recognition) these scans—which are essentially photographs of texts—are converted into readable, searchable text.

OCR uses image-recognition algorithms to identify characters and create a text file based on the image. OCR is powerful, but it is also prone to errors such as misidentifying characters (e.g. reading a zero as the letter 'O') or adding or removing spaces. There are [additional challenges for scanning older English texts](https://tedunderwood.com/2013/12/10/a-half-decent-ocr-normalizer-for-english-texts-after-1700/), such as those that use the long 's' ('ſ*'*), which resembles a lowercase 'f'. We discuss this process further in the section on Cleaning, but for now it is sufficient to know that this process can often leave errors in the text files produced through OCR.

Additional Help
--------------------------------------------------
For assistance, or to take the DSL's tools further in your own research, please [contact the Map & Data Library](https://mdl.library.utoronto.ca/about/contact-form).
* [Recorded webinars from Gale](https://support.gale.com/training/products/dslab)
* [Upcoming webinars from Gale](https://support.gale.com/training/webinars/)


Further Reading
---------------

* D’Ignazio, Catherine, and Lauren F. Klein. [Data Feminism](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/14bjeso/alma991106734515806196). MIT Press, 2020.
* Gitelman, Lisa. [“Raw Data” Is an Oxymoron](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/14bjeso/alma991106190587006196). Infrastructures Series. Cambridge, Mass: The MIT Press, 2013.
* Loukissas, Yanni A. [All Data Are Local: Thinking Critically in a Data-Driven Society](https://librarysearch.library.utoronto.ca/permalink/01UTORONTO_INST/fedca1/cdi_askewsholts_vlebooks_9780262352222). Cambridge, Massachusetts: The MIT Press, 2019.
* Onuoha, Mimi, Sparshith Sampath, Myles Braithwaite, and Corin Faife. On Missing Data Sets, 2018. [https://github.com/MimiOnuoha/missing-datasets](https://github.com/MimiOnuoha/missing-datasets).
* Posner, Miriam. “Humanities Data: A Necessary Contradiction.” Miriam Posner’s Blog, June 25, 2015. [https://miriamposner.com/blog/humanities-data-a-necessary-contradiction/](https://miriamposner.com/blog/humanities-data-a-necessary-contradiction/).

See also our [bibliography of works that critically analyze data studies](https://mdl.library.utoronto.ca/support/guides/critical-data-and-maps-equity-diversity-and-inclusion-edi), mapping and GIS from antiracist, feminist, queer, LGBTQIA2S+ and Indigenous perspectives.

Frequently Asked Questions
---------------
### Citations
Gale asks that you cite the various tool settings that you use and the document collections that you create. Many thanks to Dr. Sarah Ketchley, Senior Digital Humanities Specialist at Gale for the explanation and examples below.

#### Citing Tool Settings
Please include:

* Name of Tool
* Platform (i.e. Gale Digital Scholar Lab)
* Year or version
* Date of Access
* URL

Examples:

Chicago Manual of Style Note Format:
“Named Entity Recognition”, Gale Digital Scholar Lab, accessed February 15, 2022, [https://go.gale.com/ps/textAnalysisTools?p=DSLAB&jobId=48290&method=analysisResults&u=omni&authType=Microsoft&type=NER&contentSet=1589225177088&triggerTool=treeView&result=treeView&toolVersion=2](https://go.gale.com/ps/textAnalysisTools?p=DSLAB&jobId=48290&method=analysisResults&u=omni&authType=Microsoft&type=NER&contentSet=1589225177088&triggerTool=treeView&result=treeView&toolVersion=2)

MLA Format:
“Named Entity Recognition.” Gale Digital Scholar Lab. 2022. Web. February 15, 2022. [https://go.gale.com/ps/textAnalysisTools?p=DSLAB&jobId=48290&method=analysisResults&u=omni&authType=Microsoft&type=NER&contentSet=1589225177088&triggerTool=treeView&result=treeView&toolVersion=2](https://go.gale.com/ps/textAnalysisTools?p=DSLAB&jobId=48290&method=analysisResults&u=omni&authType=Microsoft&type=NER&contentSet=1589225177088&triggerTool=treeView&result=treeView&toolVersion=2)

#### Citing Your Document Collections
Please follow protocols for citing datasets generally, including:

* Author
* Title of Content Set (created by the researcher, and can be edited)
* Source of Content Set (put "Gale Digital Scholar Lab [Distributor].")>
* Date of Creation of Content Set
* Content Set URL (open the content set in a tab and paste the URL)

Examples:

Chicago Manual of Style Bibliographic Format:
Ketchley, Sarah L. 1840-1849 American Fiction Female Authors. Gale Digital Scholar Lab [distributor]. February 2022. [https://go.gale.com/ps/myContentSets?method=viewCSDocs&u=omni&p=DSLAB&contentSet=1539283042148](https://go.gale.com/ps/myContentSets?method=viewCSDocs&u=omni&p=DSLAB&contentSet=1539283042148)

MLA Format:
Sarah L. Ketchley. 1840-1849 American Fiction Female Authors. Gale Digital Scholar Lab [distributor]. February 2022. [https://go.gale.com/ps/myContentSets?method=viewCSDocs&u=omni&p=DSLAB&contentSet=1539283042148](https://go.gale.com/ps/myContentSets?method=viewCSDocs&u=omni&p=DSLAB&contentSet=1539283042148)

### Uploading Texts
The DSL allows you to upload your own texts as individual .txt files (under 10 MB each). The following explanations regarding security measures, privacy, and licensing restrictions come from the [DSL's FAQ.](https://go.gale.com/ps/helpCenter?userGroupName=utoronto_main&inPS=true&nspage=true&prodId=DSLAB&docId=UCHJJN776013164) (login required)

What measures are in place to secure my uploaded documents?

All documents pass through a Sentinel One security scanner and file sniffer to ensure what is uploaded is a plain text file. There is also cross-scripting on the text entry and metadata forms to prevent any malicious attacks on the environment. All documents are stored in an encrypted cloud-based storage solution with high availability.

Are there any rights restrictions around uploaded content?

Gale provides a text upload feature that allows users to analyze non-Gale content within Gale Digital Scholar Lab. The upload of personally identifiable information is not recommended. Additionally, users assume sole responsibility for clearing rights to any content loaded into this feature. In the event texts are loaded into the platform without proper rights clearance, the user indemnifies Gale from resulting litigation related to the use of that content outside the bounds of its legally stated use."

**Technique:** [Text and Data Mining](https://mdlutoronto.github.io/tutorials-search/?technique=Text+and+Data+Mining), [Cleaning data](https://mdlutoronto.github.io/tutorials-search/?technique=Cleaning+data), [Extracting data](https://mdlutoronto.github.io/tutorials-search/?technique=Extracting+data) \| **Tools:** [Digital Scholar Lab](https://mdlutoronto.github.io/tutorials-search/?tool=Digital+Scholar+Lab)
