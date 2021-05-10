# Gujarati Natural Language Processing Wiki
The aim of the page is to have a common wiki for all NLP literature and tools existing for the Gujarati language. 


## Literature
For dataset papers, refer to the [Data section](https://github.com/caffeine96/gujarati-nlp-wiki#classification).

### Part of Speech
1. Patel, Chirag, and Karthik Gali. "Part-of-speech tagging for Gujarati using conditional random fields." Proceedings of the IJCNLP-08 Workshop on NLP for Less Privileged Languages. 2008. [[Paper](https://www.aclweb.org/anthology/I08-3019.pdf),[Cite](https://www.aclweb.org/anthology/I08-3019.bib)]

### Stemming
1. Suba, Kartik, Dipti Jiandani, and Pushpak Bhattacharyya. "Hybrid inflectional stemmer and rule-based derivational stemmer for gujarati." Proceedings of the 2nd workshop on South Southeast Asian natural language processing (WSSANLP). 2011. [[Paper](https://www.aclweb.org/anthology/W11-3001.pdf),[Cite](https://www.aclweb.org/anthology/W11-3001.bib)]
2. Patel, Pratikkumar, Kashyap Popat, and Pushpak Bhattacharyya. "Hybrid stemmer for Gujarati." Proceedings of the 1st Workshop on South and Southeast Asian Natural Language Processing. 2010. [[Paper](https://www.aclweb.org/anthology/W10-3607.pdf),[Cite](https://www.aclweb.org/anthology/W10-3607.bib)]

### WordNet
1. Bhensdadia, C. K., Brijesh Bhatt, and Pushpak Bhattacharyya. "Introduction to Gujarati wordnet." Third national workshop on indowordnet proceedings. Vol. 494. 2010. [[Paper](http://www.cfilt.iitb.ac.in/wordnet/webhwn/IndoWordnetPapers/01_iwn_GujaratiWordNet.pdf), [Browser](http://www.cfilt.iitb.ac.in/gujarati/first?langno=1&queryword=boy)]

### Grammar
1. Gujarati Grammar [Wikipedia Page](https://en.wikipedia.org/wiki/Gujarati_grammar)

### Language Models
1. **Indic-BERT:** Kakwani, Divyanshu, Anoop Kunchukuttan, Satish Golla, N. C. Gokul, Avik Bhattacharyya, Mitesh M. Khapra, and Pratyush Kumar. "iNLPSuite: Monolingual Corpora, Evaluation Benchmarks and Pre-trained Multilingual Language Models for Indian Languages." In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: Findings, pp. 4948-4961. 2020. [[Paper](https://indicnlp.ai4bharat.org/papers/arxiv2020_indicnlp_corpus.pdf),[Documentation](https://indicnlp.ai4bharat.org/indic-bert/),[Model](https://storage.googleapis.com/ai4bharat-public-indic-nlp-corpora/models/indic-bert-v1.tar.gz)]
2. **Indic-FT:** Kakwani, Divyanshu, Anoop Kunchukuttan, Satish Golla, N. C. Gokul, Avik Bhattacharyya, Mitesh M. Khapra, and Pratyush Kumar. "iNLPSuite: Monolingual Corpora, Evaluation Benchmarks and Pre-trained Multilingual Language Models for Indian Languages." In Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing: Findings, pp. 4948-4961. 2020. [[Paper](https://indicnlp.ai4bharat.org/papers/arxiv2020_indicnlp_corpus.pdf),[Documentation](https://indicnlp.ai4bharat.org/indicft/),[Model](https://storage.googleapis.com/ai4bharat-public-indic-nlp-corpora/embedding-v2/indicnlp.ft.gu.300.bin)]

## Data 
### Text Corpora
1. Dakshina (Size: 200k sentences, Year: 2020, Source: Wikipedia)[[Data](https://github.com/google-research-datasets/dakshina), [Repo](https://github.com/google-research-datasets/dakshina), [Cite](https://www.aclweb.org/anthology/2020.lrec-1.294.bib)]  
2. AI4Bharat-IndicNLP (Size: 7.8 M sentences, Year : 2020, Source: News Articles) [[Data](https://storage.googleapis.com/ai4bharat-public-indic-nlp-corpora/data/monolingual/indicnlp_v1/sentence/gu.txt.gz),[Paper](https://arxiv.org/abs/2005.00085),
[Cite](https://github.com/AI4Bharat/indicnlp_corpus#citing)]
3. Gujarati Wikipedia Articles (Size: 31k articles, Year: 2020) [[Data](https://www.kaggle.com/disisbig/gujarati-wikipedia-articles)]
4. Gujarati News Articles (Size: 6.5k articles, Year: 2020) [[Data](https://www.kaggle.com/disisbig/gujarati-news-dataset)]

### Transliteration
1. Dakshina (Size: 125k,Year: 2020, Source: Wikipedia)[[Data](https://github.com/google-research-datasets/dakshina), [Repo](https://github.com/google-research-datasets/dakshina), [Cite](https://www.aclweb.org/anthology/2020.lrec-1.294.bib)]

### Classification 
1. AI4Bharat-IndicNLP Article Topic Classification  (Size: 680 articles, Year : 2020, Source: News Articles, Classes: 3) [[Data](https://storage.googleapis.com/ai4bharat-public-indic-nlp-corpora/evaluations/classification/indicnlp-news-articles.tgz),[Paper](https://arxiv.org/abs/2005.00085),
[Cite](https://storage.googleapis.com/ai4bharat-public-indic-nlp-corpora/data/monolingual/indicnlp_v1/sentence/gu.txt.gz)]
2. INLTK Headline Classification Corpus  (Size: 6587 headlines, Year: 2020, Classes: 3) [[Data](https://github.com/ai4bharat-indicnlp/indicnlp_corpus#publicly-available-classification-datasets), [Repo](https://github.com/goru001/nlp-for-gujarati)]

### Annotation Literature
1. Part of Speech Tagset: Gujarati (Also contains grammatical features)(Year:2009) - [Document](https://www.ldcil.org/Download/Tagset/LDCIL/5Gujrati.pdf)

## Tools
