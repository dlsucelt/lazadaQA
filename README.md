# lazadaQA
The Lazada Q&amp;A Intent Classification Project of the DLSU Center for Language Technologies is a project with the aim of classifying dialog acts of Taglish queries for the eventual goal of helping computers understand Taglish.

## Description
This repository currently contains the annotated dataset LazadaQA-Taglish-7k. 7,265 posts were scraped from the Question and Answer section of products from Lazada Philippines. The corpus was created to address the lack of Filipino corpora as well as the lack of e-commerce dialog act corpora. Existing corpora are usually general in nature and are collected before 2005. Since the available tagsets for dialog act classification are for general purposes, a new set of tags were created for the domain of e-commerce. The dataset currently contains the following columns:

- question (customer utterance)
- answer (seller utterance)
- customer (customer username)
- seller (seller name)
- time (relative time)
- tags (annotation)

The tags only correspond to the question asked, therefore during the annotation process, the answer, the customer, the seller, and the time are disregarded by the annotators. The assignment of tags were decided by majority agreement (i.e. a tag is assigned if 2 out of 3 annotators agree).

## Paper
This corpus is a part of a paper about to be presented in [ECONLP 2019](https://sites.google.com/view/econlp-2019) (EMNLP-IJCNLP 2019 Hong Kong). The pre-print is available at [ResearchGate](https://www.researchgate.net/publication/337005379_Annotation_Process_for_the_Dialog_Act_Classification_of_a_Taglish_E-commerce_QA_Corpus). The paper is soon to be published in the ACL Anthology as part of the proceedings of ECONLP 2019.
