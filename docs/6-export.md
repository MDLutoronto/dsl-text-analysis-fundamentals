---
title: "Export"
layout: "home"
staff:
    - name: Nick Field
      link: https://library.utoronto.ca/staff/nick-field
maintainer:
    - name: Nick Field
      link: https://library.utoronto.ca/staff/nick-field
created_date: 2022-03-10
nav_order: 6
parent: Text Analysis Fundamentals with the Digital Scholar Lab
---

# Digital Scholar Lab - Export


This tutorial demonstrates how to export documents and metadata from the Digital Scholar Lab.

Please note that Gale is periodically adding new documents to their collections, so your document counts and results may look slightly different from our screenshots and examples below.

1. Let's conclude by exporting texts from Gale Digital Scholar Lab. You can use these texts for your own research and if you have downloaded any of the tools used above (e.g. MALLET for topic modeling or perhaps you are trying spaCy in Python), you can use these texts in those tools. **Begin by clicking on My Content Sets on the top toolbar.** 
<img src='{{ '/assets/images/DSL_Export_001.png' | relative_url }}' alt='Click on My Content Set.' title='' width='600' height='' />

2. **Then, from the list of Content Sets, click on Stein.** 
<img src='{{ '/assets/images/DSL_Export_002.png' | relative_url }}' alt='My Content Sets page with “Stein” highlighted.' title='' width='800' height='' />

3. **Under the top-right tool bar, click on Download button.** 
<img src='{{ '/assets/images/DSL_Export_003.1.png' | relative_url }}' alt='The Stein Content Set with the download button highlighted.' title='' width='800' height='' />

    From the Drop-down menu, click on **Documents** 
        <img src='{{ '/assets/images/DSL_Export_003.2.png' | relative_url }}' alt='The download drop-down menu with Documents highlighted.' title='' width='600' height='' />
4. **In the popup that appears, leave Cleaning Configuration at its default, None, and click Generate Download.**       
<img src='{{ '/assets/images/DSL_Export_004.png' | relative_url }}' alt='Download Documents window with Generate Download highlighted.' title='' width='600' height='' />

    *Note: you can download a maximum of 5000 documents at one time. The maximum size of a content set is 10 000 documents.*
5. Back on the Stein Content Set overview, the Download Content Set button has changed to Generating Download. This is because Gale's servers are preparing the texts for you. **Wait a minute or two, then refresh the page.**<img src='{{ '/assets/images/DSL_Collections_Build_005.png' | relative_url }}' alt='Generating Downloads.' title='' width='800' height='' />
6. Once the **Generating** button has changed to **Download Ready**, click it.
    <img src='{{ '/assets/images/DSL_Export_006.1.png' | relative_url }}' alt='Download Ready Button on secondary tool bar.' title='' width='600' height='' />

    **Then, on the Download Content Set popup, click Download.**<img src='{{ '/assets/images/DSL_Export_006.2.png' | relative_url }}' alt='Download Content Set window with Download highlighted.' title='' width='600' height='' />
7. Your texts will be bundled together in a file called download.zip.  
**If you are using a Windows computer, use an unzipping program like [7-zip (download here)](https://www.7-zip.org/) to access the files. Right click on download.zip and select "Extract here".  
If you are using a Mac, double click on download.zip.  
When the folder has been unzipped, open it.**
8. You will now have a folder with a README.txt file and a folder called "original." **Open the "original" folder.**     
    <img src='{{ '/assets/images/DSL_Export_008.1.png' | relative_url }}' alt="Open the 'original' folder." title='' width='800' height='' />       

    Inside there is one file per text in your collection.
    <img src='{{ '/assets/images/DSL_Export_008.2.png' | relative_url }}' alt='"Original" folder with one text file per text.' title='' width='800' height='' />

    **Open the text file titled _Sikandar__the_Great_FP1800972885.txt (with the underscore at the beginning; it should be the third text, alphabetically).**
    
    <img src='{{ '/assets/images/DSL_Export_008.3.png' | relative_url }}' alt="Sample document 'Sikandar the Great' about Alexander the Great's travels." title='' width='800' height='' />

    This text has some OCR errors throughout but is mostly legible.     
    You now have access to OCRed copies of all of the texts in your corpus.
9. Now that you have access to the original texts, let's also download texts that have been cleaned using our cleaning configuration. **Click on Content set download ready again, but this time, click on the dropdown menu under Cleaning Configuration.**    
    <img src='{{ '/assets/images/DSL_Export_009.1.png' | relative_url }}' alt='Download Content Set window with the Cleaning Configuration drop-down menu highlighted.' title='' width='600' height='' />

    **From the list, choose Stein lower case.**<img src='{{ '/assets/images/DSL_Export_009.2.png' | relative_url }}' alt='Download Content Set window with the Cleaning Configuration drop-down menu open and Stein lower case highlighted.' title='' width='600' height='' />

    **Then, at the bottom of the window, click on Regenerate Download.​​​​​​​**<img src='{{ '/assets/images/DSL_Export_009.3.png' | relative_url }}' alt='Download Content Set window with Regenerate Download highlighted.' title='' width='600' height='' />

    **Wait a minute or two again, refresh, and download the new set.**

    **Unzip the folder, open the folder called Clean, and then open the text titled XX again.**<img src='{{ '/assets/images/DSL_Export_009.4.png' | relative_url }}' alt='Cleaned text with stop words missing.' title='' width='800' height='' />     
    This is the same text, after being cleaned through the cleaning configuration. All stop words (e.g. "the") have been removed, as have punctuation, numbers, and special characters, and all words are in lower case. It is no longer a readable text for humans but it helps immensely when running tools like Ngrams or Topic Modeling (via MALLET) on your own computer.
10. You can also download the metadata for your records. **Click the Download button and click on the Metadata.**   
​​​​​​​​​​​​​​<img src='{{ '/assets/images/DSL_Export_010.1.png' | relative_url }}' alt='Clicking on Metadata button in Download drop down list.' title='' width='600' height='' />

 **Then, click on the Download button.​​​​​​​**<img src='{{ '/assets/images/DSL_Export_010.2.png' | relative_url }}' alt='Download button in popup window.' title='' width='700' height='' />

You can download the metadata for up to 10 000 documents in your collection. You will receive the data as a .CSV file (which can be opened as a spreadsheet, e.g. in Excel).​​​​​​​<img src='{{ '/assets/images/DSL_Export_010.3.png' | relative_url }}' alt='Metadata in Excel.' title='' width='800' height='' />

That's it! You can now export data, visualizations, and both raw and cleaned text files from the*Digital Scholar Lab.*

[Return to the main Gale Digital Scholar Lab tutorial](https://mdl.library.utoronto.ca/technology/tutorials/digital-humanities-tools-digital-scholar-lab)

Technique: [Extracting data](https://mdlutoronto.github.io/tutorials-search/?technique=Extracting+data) | Tools: [Digital Scholar Lab](https://mdlutoronto.github.io/tutorials-search/?tool=Digital+Scholar+Lab)