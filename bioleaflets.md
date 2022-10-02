---
description: Biomedical Data-to-Text Generation via Fine-Tuning Transformers
cover: https://www.sampurnagraphics.in/images/insert3.jpg
coverY: 6.334841628959275
---

# BioLeaflets

* [PapersWithCode](https://paperswithcode.com/paper/biomedical-data-to-text-generation-via-fine)
* [arxiv](https://arxiv.org/pdf/2109.01518v1.pdf)
* [Github](https://github.com/bayer-science-for-a-better-life/data2text-bioleaflets)
* `text generation`, `T5`, `T5 Conditional Generation` , `acl`, `NLG`, `biomed`, `transfer learning`, `dataset`

{% hint style="info" %}
**`Package leaflets`** are included in the packaging of medicinal products and contain information to help patients use the product safely and appropriately.&#x20;
{% endhint %}

### Contribution

* Introduced biomedical dataset `BioLeaflets`
* Provide base model using Transformer to generate multi-sentence text from the dataset.

### Dataset Generation

> Dataset is generated from package leaflets contents. The content of each section is not standardized, yet it is still well-structured.

**Construction**

* Corpus: 1336 package leaflets (_90% medicine products_)
* Train 80%, Validatation 10%, Test 10%

<details>

<summary>Each leaflet contains 6 sections</summary>

1. What the product is and what it is used for
2. What you need to know before you take the product
3. How to take the product
4. Possible side effects
5. How to store the product
6. Content of the pack and other information

</details>

![Original Section content](<.gitbook/assets/Screen Shot 2022-05-30 at 12.38.png>)

**Annotation:**

* Augment each document by NER with:
  * [Amazon Comprehend Medical](https://aws.amazon.com/comprehend/medical/) (ACM)
  * [Stanza](https://stanfordnlp.github.io/stanza/)
* Used ACM to detect medical conditions and medication (from RxNorm)
*   26 unique entity types

    * Ex: _problem_(migraine pain, active chronic hepatitis), _system-organ-site_ (blood vessel, kidneys), _treatment_...



**Proposed generation approach**\
****Conditional generation task: Given an ordered set of entities to produce a multi-sentence section.



<details>

<summary>Walk thrue</summary>

## Dataset Generation



</details>
