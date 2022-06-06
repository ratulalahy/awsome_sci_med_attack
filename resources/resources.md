---
cover: >-
  https://www.zdnet.com/a/img/resize/4e393966bf2345c91c3ca0d8eaa85e7ee4b13218/2021/04/15/eec3dffa-92b5-433b-82ed-3203d20bf5f8/hospital-cyber.jpg?fit=bounds&auto=webp
coverY: 0
---

# Resources

## Research Papers

### BioMed

#### Embedding

* [BioSentVec](https://arxiv.org/abs/1810.09302): Creating sentence embeddings for biomedical texts
  * [BioSentVec](https://github.com/ncbi-nlp/BioSentVec): Sentence Vector Github Link&#x20;
  * [BioWordVec](https://github.com/ncbi-nlp/BioWordVec): Word Vector Github Link
* [STSb](http://ixa2.si.ehu.eus/stswiki/index.php/STSbenchmark): STS benchmark webpage
  * [Direct download link](http://ixa2.si.ehu.es/stswiki/images/4/48/Stsbenchmark.tar.gz)
* [<mark style="background-color:red;">SentEval</mark>](https://github.com/facebookresearch/SentEval)<mark style="background-color:red;">: evaluation toolkit for sentence embeddings</mark>

#### Similarity Score measure

* SimMatrics: [Github Link](https://github.com/Simmetrics/simmetrics)
  * _Comment: Java Code_

#### (Inference) NLI measure

* [Stress Test Evaluation for Natural Language Inference](https://arxiv.org/abs/1806.00692)
  * [Webpage](https://abhilasharavichander.github.io/NLI\_StressTest/) containing overview and leaderboard
  * [Github Link](https://github.com/AbhilashaRavichander/NLI\_StressTest)
  * [Google Drive link](https://drive.google.com/file/d/1hA2ZiAH2mC1U0yolft3Y8Ike-fjHmNmw/view?usp=sharing)

#### Sentence Generation

* [Biomedical Data-to-Text Generation via Fine-Tuning Transformers](https://aclanthology.org/2021.inlg-1.40/)
  * [Github Link](https://github.com/bayer-science-for-a-better-life/data2text-bioleaflets)
  * [Dataset](https://zenodo.org/record/5196178#.Yogu\_5PMJhC)

#### Name Entity Recognition (NER)

* [Biomedical named entity recognition using deep neural networks with contextual information](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3321-4)
* [Improving biomedical named entity recognition with syntactic information](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03834-6)

#### Covid

#### Entity Representation and Entity Linking

* [BioSyn](https://arxiv.org/abs/2005.00239): **Bio**Medical Entity Representation with **Syn**onym Migration
  * [Github Link](https://github.com/dmis-lab/BioSyn)
  * :hugging: available
* [Ab3P](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2576267/): Abbreviation definition identification based on automatic precision estimates
  * [Github Link](https://github.com/ncbi-nlp/Ab3P)&#x20;
  * _Comment: C++ code_
* [BERT might be overkill](https://arxiv.org/pdf/2109.02237.pdf): A Tiny but Effective Biomedical Entity Linker based on Residual Convolutional Neural Network
  * [Github Link](https://github.com/laituan245/rescnn\_bioel)
* [SapBERT](https://arxiv.org/pdf/2105.14398.pdf): Self-alignment pretraining for BERT (Learning Domain-Specialised Representations for Cross-Lingual Biomedical Entity Linking)
  * [Github Link](https://github.com/cambridgeltl/sapbert)

#### **Entity Recognition (NER)**

* [Cord NER](https://arxiv.org/abs/2003.12218):  Comprehensive NER on CORD-19 with Distant or Weak Supervision.
  * [Github Link](https://xuanwang91.github.io/2020-03-20-cord19-ner/): Overview of the methodology and Results.
  * [Kaggle Link](https://www.kaggle.com/code/xuanwangstat/cord-ner/notebook): Kaggle notebook curated NER using Cord19 Dataset.
  * [Dropbox Link](https://uofi.app.box.com/s/k8pw7d5kozzpoum2jwfaqdaey1oij93x/file/651148518303): JSON file of the dataset.
* [Cord NERD](https://drive.google.com/file/d/1uJgtqqggkVXv7uGLuG3wYWstIaa7bqRO/view): Not sure which work this Dataset belongs to :confused:



## Datasets

### Generic

#### Inference (NLI)

* [SNLI](https://aclanthology.org/C08-1066/)
  * [Webpage](https://nlp.stanford.edu/projects/snli/) containing updated info
  * [Direct .zip download link](https://nlp.stanford.edu/projects/snli/snli\_1.0.zip)
* [e-SNLI](https://github.com/OanaMariaCamburu/e-SNLI): Explanation of SNLI annotation.
  * [Publication link](https://papers.nips.cc/paper/8163-e-snli-natural-language-inference-with-natural-language-explanations.pdf)
* [MultiNLI](https://cims.nyu.edu/\~sbowman/multinli/paper.pdf)
  * [Webpage](https://cims.nyu.edu/\~sbowman/multinli/) containing updated detailed info
  * [Direct .zip download link v\_1.0](https://cims.nyu.edu/\~sbowman/multinli/multinli\_1.0.zip)
* [SciTail](https://ojs.aaai.org/index.php/AAAI/article/view/12022): A Textual Entailment Dataset from Science Question Answering
  * [Allenai page](https://allenai.org/data/scitail)
  * [Github](https://github.com/allenai/scitail)
  * [Direct Download](https://ai2-public-datasets.s3.amazonaws.com/scitail/SciTailV1.1.zip)

### BioMed

#### Sentence Pair Dataset

* [BIOSSES](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5870675/)
  * [Github Link](https://github.com/gizemsogancioglu/biosses)
  * [Dataset Link](https://tabilab.cmpe.boun.edu.tr/BIOSSES/DataSet.html)
  * [.rar Download Link](https://tabilab.cmpe.boun.edu.tr/BIOSSES/DataSet.html)
* MedSTS
  * [Paper Link ](https://medinform.jmir.org/2020/11/e23375/#ref13)
  * [Potential Git Link for Code](https://github.com/uf-hobi-informatics-lab/2019\_N2C2\_Track1\_ClinicalSTS/tree/master/src) :confused:
  * [Dataset Reproduction tutorial](https://www.protocols.io/view/a-reproducibility-protocol-and-dataset-on-the-biom-36wgq429xvk5/v3)
  * _Comment: Access request to Mayo Clinic_ :yellow\_circle:__
* [MedNLI: A Natural Language Inference Dataset For The Clinical Domain](https://physionet.org/content/mednli/1.0.0/)
  * [Home page](https://jgc128.github.io/mednli/)
  * [Github Link](https://github.com/jgc128/mednli)
  * Derived from: [MIMIC-III Clinical Database](https://physionet.org/content/mimiciii/1.4/)
  * _Comment: Requires CITI certification to access the dataset._ :yellow\_circle:__
* [CORD19STS](https://arxiv.org/abs/2007.02461): Covid 19 Semantic Textual Similarity Dataset
  * [Git Link](https://gitlab.vista.isi.edu/xiaoguo/cord\_19/-/tree/master): Overview and Results with `scripts`

#### Covid

#### **Semantic textual Similarity (STS)**

* [CORD19STS](https://arxiv.org/abs/2007.02461): COVID-19 Semantic Textual Similarity Dataset (Also in [SNLI](resources.md#semantic-textual-similarity-sts-1))
  * [Git Link](https://gitlab.vista.isi.edu/xiaoguo/cord\_19/-/tree/master/): Model weight links, Results, Overview

#### **Inference (NLI)** <a href="#inference_nli" id="inference_nli"></a>

* [CORD19STS](https://arxiv.org/abs/2007.02461): COVID-19 Semantic Textual Similarity Dataset
  * [Git Link](https://gitlab.vista.isi.edu/xiaoguo/cord\_19/-/tree/master/): Model weight links, Results, Overview

## Tutorials

## Blogs

### Entity Linking

* Entity linking approach proposed and explained by Nvidia : [Self-alignment Pre-training for Biomedical Entity Representations](https://arxiv.org/abs/2010.11784v2)

## Notebooks

## Talks

## Misc

* [NLP task](https://git.doit.wisc.edu/YGAO/public-available-clinical-nlp-tasks): Git Link of A collection of research work.
