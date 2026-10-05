---
permalink: /program/
title: "Program"
---


# Critical Approaches to Automatic Text Recognition for the Digital Humanities 

Estelle Guéville  
David Joseph Wrisley  
Master Rare Book and Digital Humanities, [UMLP](https://www.openstreetmap.org/node/13340610978#map=19/47.233729/6.025524), Besançon 2026


## Day 1: Monday 19 Oct 2026

**Summary of day 1:** This first day introduces participants to each other and to the course, asking why searchable text matters for access, discovery and the study of cultural heritage materials. Through examples of OCR/HTR tools, platforms, digital collections, and hands-on exercises, it frames text recognition not only as a technical process but also as a question of infrastructure, sustainability, audience, access, and scholarly power.

### Session 1: Introductory talk

**1000-1200:** Introduction of course participants, beginning of course introduction 

**Why searchable text?**

* Digitization of cultural heritage materials and access   
* Searchability, discoverability, computational tractability  
* Researcher: HTR as a Starting Point for Editing and Studying Texts  
* Institutional: Discoverability 

**1200-1400 Lunch**

### Session 2: Exploring digital collections and their transcriptions 

**1400-1530:**  Exercise #1:

* [Internet Archive](https://archive.org/details/lesoriginesdemon00mont/page/2/mode/2up)   
* Gallica (BnF) ([example 1](https://gallica.bnf.fr/ark:/12148/bpt6k1187466x/f1.vertical#), [example 2](https://gallica.bnf.fr/ark:/12148/bpt6k6567155j))  
* QDL ([handwritten](https://www.qdl.qa/en/search/site/IOR%252015), [typewritten](https://www.qdl.qa/en/archive/81055/vdc_100025648640.0x000006))  
* [Arabic Collections Online](https://aco.dlib.nyu.edu/book/auc_aco000444/1)  
* [Transkribus Sites](https://www.transkribus.org/sites)  
* [CoMMA](https://comma.inria.fr/about) 

Discussion points: What kinds of information do these sites contain? What formats are they in? Why were they created? Can you relate them to Zaagsma (2022)?

**Exercise #2 : Computable Objects I** :

** Exercise with [Voyant Tools](https://beta.voyant-tools.org/) and general discussion on searchable text (ElKhatib and Ross, 2022) / Notebook: "Anatomy of a Word Cloud" ([posit.cloud](https://posit.cloud/))

**1530-1545:** Break

**1545-1645**: **Examples of HTR/OCR environments**

* Starting points, platforms, methods, audiences, business models, national & disciplinary norms for research  
* [Digital sobriety](https://journals.openedition.org/revuehn/4304): Not driving your Ferrari when you can take public transport  
* Demo for Tesseract ([Programming Historian](https://programminghistorian.org/en/lessons/?search=tesseract)) / Abby FineReader  
* TrOCR / OCR-D  
* eScriptorium / CALFA  
* Rescribe / Treventus / LLMs  
* OLM / Transkribus

Discussion points: TBD

**1645-onward**: eScriptorium clinic : troubleshooting in setup and installation

**Homework:**

- Find a textual object and try it in one of the tools: Google Drive, [OLM](https://olmocr.allenai.org/), [transkribus.ai](http://transkribus.ai), other LLMs ([Possible](https://drive.google.com/drive/folders/1PLaT-7KRt0RODT2JuZ_XxDC8kEYx621m?usp=drive_link) documents to try)  
- Try the Programming Historian tutorial “[Working with Batches of PDF files](https://programminghistorian.org/en/lessons/working-with-batches-of-pdf-files),” especially the part on downloading tesseract as a command line tool.    
- Run the output in [Voyant tools](https://voyant-tools.org/) and be prepared to discuss the outputs in class

**Zotero library:** We have put together a Zotero library [ATR\_HTR\_for\_DH](https://www.zotero.org/groups/6465155/atr_htr_for_dh) for the course that contains much more reading material. If you would like to contribute to it, sent a request from your account at Zotero. Other libraries put together by others on the subject include [ATR with LLM](https://www.zotero.org/groups/6308130/atr_with_llm), [ATR History](https://www.zotero.org/groups/5646174/atr_history).

## Day 2: Tuesday 20 October 2026

**Summary of day 2:** This second day takes a glimpse into the “black box” of automated text recognition, demonstrating its constituent steps: layout analysis, segmentation, baseline detection, transcription guidelines, ground truth creation and alignment with digitized sources as well as post-correction and fine tuning. Through hands-on work with [Transkribus](https://www.transkribus.org/), [eScriptorium](http://www.escriptorium.org/), and LLMs, participants compare general and custom models while asking how language, script, period, institutional access, and bias shape what machines can and cannot, will and will not read.

### Session 3: 

**0830-1000: Visit to the [Bibliothèque d'étude et de conservation, Besançon](https://www.openstreetmap.org/relation/537364#map=17/47.235127/6.028737): From physical objects to digitized objects.** Discovery of institutional, non-digitized collections in different languages and a smartphone photo session.

<div style="width:100%; height:75vh; min-height:600px;">
  <iframe
    src="https://www.openstreetmap.org/export/embed.html?bbox=6.018%2C47.230%2C6.040%2C47.241&amp;layer=mapnik&amp;relation=537364"
    style="width:100%; height:100%; border:0; display:block;"
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>

**1030-1100: Homework discussion**

**1100-1200: ATR workflows - Transkribus & eScriptorium** 

- Discussion of your homework findings  
- Layout analysis  
- Segmentation  
- Baseline detection  
- Training data/ground truth  
- Ground truth and its meaning for the humanities

Discussion points: Which sources seen at the library are best suited to ATR? Why? 

**1200-1400: Lunch** 

### Session 4: HTR Models and Transcription Guidelines

**1400-1545: Different kinds of ATR models**  
- Why use an ATR? (General/super models, bespoke models)
- When to use frontier AI LLMs?
- Is the gap between scholarly ATR and frontier AI closing?

# Transcription guidelines and why they matter

**Exercise:** Transcription bias comparison

- 10 transcriptions (Pages from several documents produced in different centuries/languages 
- Models from eScriptorium, Transkribus super model, Transkribus public model “non-transformer,” eScriptorium, different LLMs) and discuss the results

Discussion points: TBD

**1545-1600: Break**

**1600-1700: Hands-on with documents with Transkribus and/or eScriptorium**  
Practice uploading, performing layout analysis, finding models, and HTR.

**Homework:** Explore [Reviews in Digital Humanities](https://reviewsindh.pubpub.org/) to identify some kind cultural data and what digital scholarship does with it.  


## Day 3: Wednesday 21 October 2026

**Summary of day 3:** This day focuses on how to train ATR models in Transkribus and eScriptorium for your own needs. It also addresses the question of LLM-based transcriptions and prompting strategies. It then asks how HTR outputs become computable objects, looking at examples of semantic annotation for mapping.

### Session 5:

**9000-1000: Training models: examples, process and Hands on in Transkribus**

**1030-1045: Break**

**1045-1200: From archival sources to digital objects:** 

- An HTR model & corresponding ground truth  
- TEI encoded file(s) and digital editions  
- Computational analysis of transcribed text (stylometry)  
- Annotated text for mapping, storymaps, NER  
- Network visualization based on transcribed text  
- Digital exhibits ([Wax](https://minicomp.github.io/wax/), [Collection Builder](https://collectionbuilder.github.io/))  
- RAG   

Discussion points: If you have ATR-created text, what kinds of post-processing do you anticipate for different kinds of digital scholarship?

**1200-1400: Lunch** 

### Session 6: 

**1400-1500: Try Gemini/Mistral-Vibe/chatGPT and prompting for transcription**

**1500-1515: Break**

**1515-1700: Computable Objects II:** Human semantic tagging with Recogito of transcribed book on regional topics from the [Internet Archive](http://archive.org). Comparison with automatic tagging with NER. 

Discussion points: How does human and machine tagging compare? What are issues that arise with ATR-created texts and tagging? 


## Day 4: Thursday 22 October 2026 

**Summary of day 4:** This day continues asking how HTR outputs become computable objects, looking at examples of TF-IDF and stylometry to show how machine-readable texts can become starting points for interpretation rather than final products. In the afternoon, students will reflect on how HTR, AI, and computational humanities are changing what gets transcribed, what gets counted, and how cultural heritage research can remain critical, inclusive, and accountable. Volunteers will then present their theses and get feedback.

### Session 7: 

**900-1045: Computable Objects III:**   
**Exercise:** TF-IDF classification 

- Charles Weiss journals (using HTR’d using eScriptorium & scraped [printed edition](https://books.openedition.org/pufc/person/1347)) 
- general discussion 

Discussion points: How well does ATR-created text lend itself to computational forms of distant reading, such as classification with TF IDF? What difference does text quality make? 

**1045-1100: Break**

**1100-1200: Wrap-up and Questions** 

### Session 8:  

**1400-1700: M2 Student Thesis Topic Presentations and Feedback**

## Day 5: Friday 23 October 2026 

### Session 9: 

**900-1200: M2 Student Thesis Topic Presentations, Feedback and General Discussion** 

