---
title: "Cleaning"
layout: "home"
staff:
    - name: Nick Field
      link: https://library.utoronto.ca/staff/nick-field
maintainer:
    - name: Nick Field
      link: https://library.utoronto.ca/staff/nick-field
created_date: 2022-03-10
nav_order: 4
parent: Text Analysis Fundamentals with the Digital Scholar Lab
---

# Digital Scholar Lab - Cleaning


This tutorial demonstrates how to use and customize the Digital Scholar Lab's cleaning configurations.

Please note that Gale is periodically adding new documents to their collections, so your document counts and results may look slightly different from our screenshots and examples below.

1. Click on the Clean tab in the toolbar.  
<img src='{{ '/assets/images/DSL_Cleaning_001.png' | relative_url }}' alt='Clean tab in the toolbar.' title='' width='500' height='203' />

2. This is the Cleaning Configuration page, specifically the default configuration.  
    <img src='{{ '/assets/images/DSL_Cleaning_002.png' | relative_url }}' alt='The Clean page.' title='' width='800' height='448' />

3. Cleaning configurations produce higher quality analysis and visualizations by removing errors and extraneous data. The default cleaning configuration is a good start for most projects, but based on previous testing, it leaves in a lot of junk data with our current collection. For better results, let's make our own cleaning configuration. **Under the top-right tool bar, click on "\+ New Configuration."** 
    <img src='{{ '/assets/images/DSL_Cleaning_003.png' | relative_url }}' alt='The ‘New Configuration’ button highlighted.' title='' width='600' height='338' />

4. **Name it Stein and click Submit.** 
    <img src='{{ '/assets/images/DSL_Cleaning_004.png' | relative_url }}' alt='New Clean Configuration window with “Stein” entered in the Configuration Name field.' title='' width='500' height='211' />

5. **To make our corpus a little more useful, under Cleaning Configuration, check “Remove all extended ASCII characters”, “Remove all number characters”, “Remove all special characters”, “Remove all punctuation”, and "Remove all non-body content". Leave the other settings at their defaults.** 
    <img src='{{ '/assets/images/DSL_Cleaning_005.1.png' | relative_url }}' alt='Cleaning configuration options with several boxes highlighted and checked.' title='' width='800' height='749' />

    *Note: Extended ASCII characters are characters used in languages other than English (e.g. accented letters like é), as well as for some typesetting and mathematical uses. Since we’re exclusively working with modern English sources in this collection, extended ASCII characters will only appear as errors of the OCR process, and therefore excluding them will give us more meaningful results. Similarly, by excluding punctuation, numbers, and special characters, we will prevent the DSL from treating individual numbers or punctuation as words.*

    If we leave punctuation in, the Ngram tool reveals that the most popular "word" is the period/full stop, which is not very useful:<img src='{{ '/assets/images/DSL_Cleaning_005.2.png' | relative_url }}' alt='Messy word cloud with random letters, numbers, and punctuation.' title='' width='800' height='533' />

    ***Don't be like this; be sure to exclude punctuation, numbers, and special characters!***
6. Also, when you create a new configuration, you need to set a list of stop words. Stop words are common words, like “a” and “you,” that we filter out before running analyses on our corpus. If we don’t exclude them, then it turns out that the most common word in almost every English corpus is “the.” **Under Stop Words, click Choose a Starter List.** 
<img src='{{ '/assets/images/DSL_Cleaning_006.png' | relative_url }}' alt='Choose a starter list.' title='' width='800' height='372' />

7. **Select English, then click Select starter lists.** 
<img src='{{ '/assets/images/DSL_Cleaning_007.png' | relative_url }}' alt='List of several languages, with English highlighted.' title='' width='600' height='828' />

    *Note: you can select multiple languages, if you are working with a corpus that includes texts in multiple languages. We'll stick with just English for this collection.*
8. Your Stop Words list is now populated with the most common English words.  
<img src='{{ '/assets/images/DSL_Cleaning_008.png' | relative_url }}' alt='Initial interface with common stop words.' title='' width='800' height='390' />

9. You can add words to your stop word list by typing them in. You must separate each word with paragraph returns (i.e. by hitting the Enter key). **Add the following words to the stop word list by copying and pasting them into the list above the first word in the English stop word list ("a"):** 

    `b`  
    `c`  
    `d`  
    `e`  
    `f`  
    `g`  
    `h`  
    `j`  
    `k`  
    `l`  
    `m`  
    `n`  
    `o`  
    `p`  
    `q`  
    `r`  
    `s`  
    `t`  
    `u`  
    `v`  
    `w`  
    `x`  
    `y`  
    `z`  
    `th`  
    `pp`  
    `Sec`  
    `ii`  
    `iii`  
    `iv`  
    `vi`  
    `vii`  
    `vii`  
    `ix`  
    `xi`  
    `xii`  
    `xiii`  
    `xiv`  
    `xv`  
    `xvi`  
    `xvii`  
    `xviii`  
    `xix`  
    `xx`  
    `xxi`  
    `xxii`  
    `xxiii`  
    `xxiv`  
    `xxv`  
    `xxvi`  
    `xxvii`  
    `xxviii`  
    `xxix`  
    `xxx`  
    `no.`  
    `sec.`  
    `said`  
    `tho`  

    <img src='{{ '/assets/images/DSL_Cleaning_009.png' | relative_url }}' alt='Pasting additional stop words at top of list.' title='' width='800' height='529' />

    Be sure to avoid erasing the English stop word list.    

    *Note: by adding these "words" to the list, which are a mix of abbreviations (like "Sec." for "section"), Roman numerals, and individual letters, we do two things: (1) we remove commonly used words that are related to the structure rather than the contents of the text, like "Sec." or the Roman numerals; and (2) we account for some OCR errors. Since the OCR process sometimes misreads a word, inserting a space where there should be none (e.g. misreading "apple" as "a pple"), single or paired letters appear as common "words" in some text collections. This isn't true for every collection, but it is true for this particular collection.*

10. Cleaning configurations can also replace words. One use is to treat variations of a key word or phrase as a single word. To prevent the various tools from treating "Stein," "Aurel Stein," "Sir Aurel Stein," etc. as different words, **scroll down to the Replacements section.** 
<img src='{{ '/assets/images/DSL_Cleaning_010.png' | relative_url }}' alt='The replacement section.' title='' width='800' height='233' />

11. **In the first row, under "Replace this...", type** ***Sir Aurel Stein*****. On the same row, under "With this...", type** ***Aurel Stein*****.** 
<img src='{{ '/assets/images/DSL_Cleaning_011.png' | relative_url }}' alt='Add first replacement condition in the first row.' title='' width='800' height='225' />

12. **On the next row, replace** ***Aurel*** **with** ***Aurel Stein*** **. Repeat this process on the next row, replacing** ***Sir Stein*** **with** ***Aurel Stein*** **.** 
<img src='{{ '/assets/images/DSL_Cleaning_012.png' | relative_url }}' alt='Add replace conditions into each row.' title='' width='800' height='223' />

    Now all of these variations on his name will show up as the same version, "Aurel Stein," in our future analysis and visualizations.
13. **Finally, click Save.** 
<img src='{{ '/assets/images/DSL_Cleaning_013.png' | relative_url }}' alt='The ‘Save’ button highlighted.' title='' width='700' height='365' />

    *Note: when you work with your own projects, you might need to adjust your cleaning configuration several times in order to remove errors specific to your texts.*

That's it! You've now cleaned your texts using a variety of tools.

[Continue on to Analysis](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-analysis)  
[Return to the main Gale Digital Scholar Lab tutorial](https://mdl.library.utoronto.ca/technology/tutorials/digital-humanities-tools-digital-scholar-lab)

Technique: [Cleaning data](https://mdlutoronto.github.io/tutorials-search/?technique=Cleaning+data) | Tools: [Digital Scholar Lab](https://mdlutoronto.github.io/tutorials-search/?tool=Digital+Scholar+Lab)