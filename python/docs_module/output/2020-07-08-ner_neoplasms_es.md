---
layout: model
title: Neoplasms NER
author: John Snow Labs
name: 
class: 
language: 
repository: clinical/models
date: 2020-07-08
tags: [clinical,ner,cantemist,es]
article_header:
   type: cover
use_language_switcher: "Python-Scala-Java"
---

{:.h2_title}
## Description 
Neoplasms NER is a Named Entity Recognition model that annotates text to find references to tumors. The only entity it annotates is MalignantNeoplasm. Neoplasms NER is trained with the 'embeddings_scielowiki_300d' word embeddings model, so be sure to use the same embeddings in the pipeline.

 {:.h2_title}
## Predicted Entities
MORFOLOGIA_NEOPLASIA 

{:.btn-box}
<button class="button button-orange" disabled>Live Demo</button><br/><button class="button button-orange" disabled>Open in Colab</button><br/>[Download](https://s3.amazonaws.com/auxdata.johnsnowlabs.com/clinical/models/ner_neoplasms_es_2.5.3_2.4_1594168624415.zip){:.button.button-orange.button-orange-trans.arr.button-icon}<br/>

## How to use 
<div class="tabs-box" markdown="1">

{% include programmingLanguageSelectScalaPython.html %}

```python

```

```scala

```
</div>



{:.model-param}
## Model Information
{:.table-model}
|-------------------------|----------------------------------|
| Model Name              | ner_neoplasms                    |
| Model Class             | NerDLModel                       |
| Spark Compatibility     | 2.5.3                            |
| Spark NLP Compatibility | 2.4                              |
| License                 | Licensed                         |
| Edition                 | Official                         |
| Input Labels            | sentence, token, word_embeddings |
| Output Labels           | ner                              |
| Language                | es                               |
| Case Sensitive          | False                            |
| Upstream Dependencies   | embeddings_scielowiki_300d       |





{:.h2_title}
## Data Source
Named Entity Recognition model for Neoplasic Morphology.
