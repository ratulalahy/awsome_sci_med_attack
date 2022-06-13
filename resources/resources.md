---
cover: >-
  https://www.zdnet.com/a/img/resize/4e393966bf2345c91c3ca0d8eaa85e7ee4b13218/2021/04/15/eec3dffa-92b5-433b-82ed-3203d20bf5f8/hospital-cyber.jpg?fit=bounds&auto=webp
coverY: 0
---

# Resources

## Research Papers

### BioMed

* [<mark style="background-color:red;">SciBERT</mark>](https://github.com/allenai/scibert): BERT model trained on Scientific texts.
* [<mark style="background-color:red;">BioBERT</mark>](https://github.com/dmis-lab/biobert): BERT model fine-tuned on Biomedical text for various tasks: NER, Relation Extract, QA..
  * [Paper](https://arxiv.org/abs/1901.08746)
  * [Pretrained Weights](https://github.com/naver/biobert-pretrained)

#### Embedding

* [BioSentVec](https://arxiv.org/abs/1810.09302): Creating sentence embeddings for biomedical texts
  * [BioSentVec](https://github.com/ncbi-nlp/BioSentVec): Sentence Vector Github Link&#x20;
  * [BioWordVec](https://github.com/ncbi-nlp/BioWordVec): Word Vector Github Link
* [STSb](http://ixa2.si.ehu.eus/stswiki/index.php/STSbenchmark): STS benchmark webpage
  * [Direct download link](http://ixa2.si.ehu.es/stswiki/images/4/48/Stsbenchmark.tar.gz)
* [Concepts and Synonymy in the UMLS Metathesaurus](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2850250/)
* [Exploiting MeSH indexing in MEDLINE to generate a data set for word sense disambiguation](https://d-nb.info/1082776696/34)
* [InferSent](https://github.com/facebookresearch/InferSent): Sentence embedding method that provides semantic representation.
  * Developed by FbResearch
* [<mark style="background-color:red;">SentEval</mark>](https://github.com/facebookresearch/SentEval): Evaluation toolkit for sentence embeddings
  * Developed by FbResearch
  * All STS similarity dataset is added
  * Multiple DownStream(QA, paraphrase detection, Semantic Similarity, NLI) and Probing model is there.
* [<mark style="background-color:red;">MedSentEval</mark>](https://github.com/nstawfik/MedSentEval)<mark style="background-color:red;">:</mark> SentEval for BioMedical Dataset
  * [Paper](https://www.sciencedirect.com/science/article/pii/S1532046420300253)
* <mark style="background-color:red;"></mark>[Universal Sentence Encoder](https://tfhub.dev/google/universal-sentence-encoder-large/5) by Google
* [FastText Word Vectors](https://fasttext.cc/docs/en/english-vectors.html)
* [<mark style="background-color:red;">2019 N2C2 Track-1</mark>: Clinical Textual Similarity Best RoBERTa model](https://github.com/uf-hobi-informatics-lab/2019\_N2C2\_Track1\_ClinicalSTS): Clinical STS 2019
  * [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7721552/#ref48)
* [MeshSim](https://github.com/luozhhub/pyMeSHSim)
  * [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03583-6)

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
* [PubTator](https://www.ncbi.nlm.nih.gov/research/pubtator/api.html): Return annotated abstract or full text for a given PubID and CUI \[WebAPI]
  * [Python Interface](https://www.ncbi.nlm.nih.gov/CBBresearch/Lu/Demo/tmTools/download/ExampleCode.Python.zip)
  * [Example Link](https://www.ncbi.nlm.nih.gov/research/bionlp/APIs/format/)

### Scientific Claim Verifications

* <mark style="background-color:red;"></mark>[<mark style="background-color:red;">Scifact</mark>](https://github.com/allenai/scifact)<mark style="background-color:red;"></mark>
  * [Paper](https://arxiv.org/abs/2004.14974)
* [MultiVerS](https://github.com/dwadden/multivers)
  * [Paper](https://arxiv.org/abs/2112.01640)
* [<mark style="background-color:red;">CovidFact</mark>](https://github.com/asaakyan/covidfact)
  * Also Generate counter claim
  *
  * [Paper](https://arxiv.org/pdf/2106.03794.pdf)
* <mark style="background-color:red;"></mark>[<mark style="background-color:red;">HealthVer</mark>](https://github.com/sarrouti/HealthVer)<mark style="background-color:red;"></mark>
  * [Paper](https://github.com/sarrouti/HealthVer/blob/master)

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

#### Synonym

* <mark style="background-color:red;"></mark>[<mark style="background-color:red;">Disease</mark> description and synonums](https://snap.stanford.edu/biodata/datasets/10021/10021-D-DoMiner.html)
* <mark style="background-color:red;"></mark>[<mark style="background-color:red;">Emerse Synonyms</mark>](https://project-emerse.org/synonyms.html)<mark style="background-color:red;"></mark>

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

### Name Entity Relationship (NER)

* [Who’s Who and What’s What: Advances in Biomedical Named Entity Recognition (BioNER)](https://towardsdatascience.com/whos-who-and-what-s-what-advances-in-biomedical-named-entity-recognition-bioner-c42a3f63334c)

### Text Generation

* [Data to Text generation with T5; Building a simple yet advanced NLG model](https://towardsdatascience.com/data-to-text-generation-with-t5-building-a-simple-yet-advanced-nlg-model-b5cce5a6df45)

### Others

* <mark style="background-color:red;"></mark>[<mark style="background-color:red;">Synonym</mark> and Antonym from WordNet](https://medium.com/@tameremil/synonyms-and-antonyms-from-wordnet-778f6274fb09)

## Survey

* [A survey of word embeddings for clinical text](https://www.sciencedirect.com/science/article/pii/S2590177X19300563)

## Notebooks

## Talks

## Misc

* [NLP task](https://git.doit.wisc.edu/YGAO/public-available-clinical-nlp-tasks): Git Link of A collection of research work.
* <mark style="background-color:red;">``</mark>[<mark style="background-color:red;">`MetaMap`</mark>](https://lhncbc.nlm.nih.gov/ii/tools/MetaMap.html):  Tool for Recognizing UMLS concepts in text.
  * [Python Interface](https://github.com/AnthonyMRios/pymetamap)
* [<mark style="background-color:red;">MetaThesaures</mark>](https://www.nlm.nih.gov/research/umls/knowledge\_sources/metathesaurus/index.html): Biomedical Thesaurus
  * [Example](https://uts.nlm.nih.gov/uts/umls/concept/C0018681)
  * Possible to get info and synonym by CUI
  * Local installable API available.
  * [MetamorphoSys](https://www.nlm.nih.gov/research/umls/implementation\_resources/metamorphosys/help.html): MetaThesaure customization tool
* [<mark style="background-color:red;">Specialist</mark> Lexicon](https://lhncbc.nlm.nih.gov/LSG/Projects/lexicon/current/web/index.html)
  * Collection of Lexical files of various concepts.
  * Can retrive info by CUI.
* [<mark style="background-color:red;">Specialist</mark> Lexical Tool](https://lhncbc.nlm.nih.gov/LSG/Projects/lvg/current/web/index.html)
  * [Example](https://lhncbc.nlm.nih.gov/LSG/Projects/lvg/current/docs/designDoc/LifeCycle/requirement/lvgOptions/antonymNegation.html)
  * Provide Synonym, Antonym, Normalization...
* [DNorm](https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/dnorm/): For a given PMID abstract, the abstract is normalize and Concept IDs are extracted
* [NCBI disease corpus](https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/)
* [BIONLP](https://www.ncbi.nlm.nih.gov/research/bionlp/Tools/) tools and Software collection by NCBI
* [<mark style="background-color:red;">LITSence</mark>](https://www.ncbi.nlm.nih.gov/research/litsense/?view=tutorial#tut-api)<mark style="background-color:red;">:</mark> Api for searching published literature (by intro, conclusion, abstract...) for given query or sentence or keyword
  * [Example](https://www.ncbi.nlm.nih.gov/research/litsense-api/api/?format=api\&query=Breast+cancers+with+HER2+amplification\&rerank=true)
* <mark style="background-color:red;"></mark>[<mark style="background-color:red;">PubTator</mark>](https://www.ncbi.nlm.nih.gov/research/bionlp/APIs/usage/): Get content and annotation of a published paper by PMID.&#x20;

## Knowledge Graph

* [Collection of Covid-19 Knowledge Graph (RDF dumps)](https://research.bioinformatics.udel.edu/covid19kg/rdfdumps)
* [All Pubmed Knowledge Graph Dataset](http://er.tacc.utexas.edu/datasets/ped)
