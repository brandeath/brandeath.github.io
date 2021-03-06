---
layout: page
permalink: /resources/
title: Publications of Deep Learning in NLP
tags: [papers]
image:
  feature: bg_friend.jpg
---


This page is to collect the publications and related resources of Deep Learning in NLP.

It is inspired by the great resource on [*CSE 599 - Advanced in NLP*](http://homes.cs.washington.edu/~yejin/cse599.html).

Feel free to pull request on [Github](https://github.com/niangaotuantuan/Publications-of-Deep-Learning-in-NLP).



###Survey

#### Bengio et al's survey on representation learning
+ Yoshua Bengio, Aaron Courville and Pascal Vincent. "Representation Learning: A Review and New Perspectives." [pdf](http://arxiv.org/pdf/1206.5538v3.pdf) TPAMI 35:8(1798-1828)

#### Bengio, LeCun Yann, Yoshua Bengio and Geoffrey Hinton's survey on *Nature*
+ Yann LeCun, Yoshua Bengio	 and Geoffrey Hinton. "Deep Learning"
[pdf](http://download.csdn.net/detail/happytofly/8758755) Nature 521, 436–444

### Embeddings & Language Models

#### Skip-gram embeddings

+ Tomas Mikolov, Kai Chen, Greg Corrado, and Jeffrey Dean. "Efficient Estimation of Word Representations in Vector Space." [pdf](http://arxiv.org/pdf/1301.3781.pdf) ICLR, 2013. 
+ Tomas Mikolov, Ilya Sutskever, Kai Chen, Greg Corrado, and Jeffrey Dean. "Distributed Representations of Words and Phrases and their Compositionality." [pdf] (http://arxiv.org/pdf/1310.4546.pdf) NIPS, 2013. 
+ [king-man+woman=queen] Tomas Mikolov, Wen-tau Yih, and Geoffrey Zweig. "Linguistic Regularities in Continuous Space Word Representations." [pdf](http://research.microsoft.com/pubs/189726/rvecs.pdf) NAACL, 2013. 
+ [technical note] Yoav Goldberg and Omer Levy "word2vec explained: deriving Mikolov et al.'s negative-sampling word-embedding method" [pdf](http://www.cs.bgu.ac.il/~yoavg/publications/negative-sampling.pdf) Tech-report 2013 
+ [buzz-busting] Omer Levy and Yoav Goldberg "Linguistic Regularities in Sparse and Explicit Word Representations" [pdf](http://www.cs.bgu.ac.il/~yoavg/publications/conll2014analogies.pdf) **CoNLL-2014 Best Paper Award** 
+ [lessons learned] Omer Levy, Yoav Goldberg, Ido Dagan "Improving Distributional Similarity with Lessons Learned from Word Embeddings" [pdf](https://levyomer.files.wordpress.com/2015/03/improving-distributional-similarity-tacl-2015.pdf), TACL 2015
+ [syntax-word order] Wang Liang, Chris Dyer, Alan Black, Isabel Trancoso. "Two/Too Simple Adaptations of Word2Vec for Syntax Problems" [pdf](http://www.cs.cmu.edu/~lingwang/papers/naacl2015.pdf) NAACL 2015 (Short)

#### Embedding enhancement: Syntax, Retrofitting, etc
+ [dependency embeddings] Omer Levy and Yoav Goldberg "Dependency Based Word Embeddings" [pdf](http://www.cs.bgu.ac.il/~yoavg/publications/acl2014syntemb.pdf) ACL 2014 (Short) 
+ [dependency embeddings] Mohit Bansal, Kevin Gimpel and Karen Livescu. "Tailoring Continuous Word Representations for Dependency Parsing" [pdf](http://www.aclweb.org/anthology/P14-2131.pdf) ACL 2014 (Short)
+ [retrofitting with lexical knowledge] Manaal Faruqui, Jesse Dodge, Sujay Kumar Jauhar, Chris Dyer, Eduard Hovy and Noah A. Smith. "Retrofitting Word Vectors to Semantic Lexicons" [pdf](http://arxiv.org/pdf/1411.4166v4.pdf), NAACL 2015 
+ [contrastive estimation] Mnih and Kavukcuoglu, "Learning Word Embeddings Efficiently with Noise-Contrastive Estimation." [pdf](https://www.cs.toronto.edu/~amnih/papers/wordreps.pdf) NIPS 2013 
+ [embedding documents] Quoc V Le, Tomas Mikolov. "Distributed representations of sentences and documents" [pdf](http://jmlr.csail.mit.edu/proceedings/papers/v32/le14.pdf) ICML 2014 
+ [synonymy relations] Mo Yu, Mark Dredze. "Improving Lexical Embeddings with Semantic Knowledge" [pdf](http://www.cs.jhu.edu/~mdredze/publications/2014_acl_embeddings.pdf) ACL 2014 (Short)
+ [embedding relations] Asli Celikyilmaz, Dilek Hakkani-Tur, Panupong Pasupat, Ruhi Sarikaya. "Enriching Word Embeddings Using Knowledge Graph for Semantic Tagging in Conversational Dialog Systems" [pdf](http://research.microsoft.com/pubs/238362/Celikyilmaz.pdf) AAAI 2015 (Short)
+ [multimodal] Angeliki Lazaridou, Nghia The Pham and Marco Baroni. "Combining Language and Vision with a Multimodal Skip-gram Model" [pdf](http://arxiv.org/pdf/1501.02598v3.pdf) NAACL 2015
+ [syntax-word order] Wang Liang, Chris Dyer, Alan Black, Isabel Trancoso. "Two/Too Simple Adaptations of Word2Vec for Syntax Problems" [pdf](http://www.cs.cmu.edu/~lingwang/papers/naacl2015.pdf) NAACL 2015 (Short)

#### Embedding enhancement: Word order, Morphological, etc
+ [syntax-word order] Wang Liang, Chris Dyer, Alan Black, Isabel Trancoso. "Two/Too Simple Adaptations of Word2Vec for Syntax Problems" [pdf](http://www.cs.cmu.edu/~lingwang/papers/naacl2015.pdf) NAACL 2015 (Short)
+ [word order] Rie Johnson and Tong Zhang. Effective use of word order for text categorization with convolutional neural networks. [pdf](http://aclweb.org/anthology/N/N15/N15-1011.pdf) NAACL 2015
+ [word order] Radu Soricut and Franz Och. "Unsupervised Morphology Induction Using Word Embeddings" [pdf](http://aclweb.org/anthology/N/N15/N15-1186.pdf) **NAACL 2015 Best Paper Awards**
+ [morphology] Minh-Thang Luong Richard Socher Christopher D. Manning. "Better Word Representations with Recursive Neural Networks for Morphology" [pdf](http://nlp.stanford.edu/~lmthang/data/papers/conll13_morpho.pdf) CoNLL 2013
+ [morpheme] Siyu Qiu, Qing Cui, Jiang Bian, Bin Gao, Tie-Yan Liu. "Co-learning of Word Representations and Morpheme Representations" [pdf](http://www.aclweb.org/anthology/C14-1015) COLING 2014 
+ [morphological] Ryan Cotterell and Hinrich Schütze. "Morphological Word-Embeddings" [pdf](http://www.aclweb.org/anthology/N/N15/N15-1140.pdf) NAACL 2015 (Short)
+ [regularization] Dani Yogatama, Manaal Faruqui, Chris Dyer, Noah Smith. "Learning Word Representations with Hierarchical Sparse Coding" [pdf](http://arxiv.org/pdf/1406.2035.pdf) ICML 2015


#### Embeddings as matrix factorization
+ [approximate interpretation] Levy and Goldberg, "Neural Word Embedding as Implicit Matrix Factorization." [pdf](https://levyomer.files.wordpress.com/2014/09/neural-word-embeddings-as-implicit-matrix-factorization.pdf) NIPS 2014 
+ Omer Levy, Steffen Remus, Chris Biemann, and Ido Dagan. "Do Supervised Distributional Methods Really Learn Lexical Inference Relations?" [pdf](https://levyomer.files.wordpress.com/2015/03/do-supervised-distributional-models-naacl-2015.pdf) NAACL 2015 (Short)
+ Tim Rocktaschel, Sameer Singh and Sebastian Riedel. "Injecting Logical Background Knowledge into Embeddings for Relation Extraction" [pdf](http://rockt.github.io/pdf/rocktaschel2015injecting.pdf) NAACL 2015
+ [exact interpretation] Yitan Li, Linli Xu, Fei Tian, Liang Jiang, Xiaowei Zhong and Enhong Chen. "Word Embedding Revisited: A New Representation Learning and Explicit Matrix Factorization Perspective" [pdf](http://home.ustc.edu.cn/~etali/papers/EMF-IJCAI2015.pdf) IJCAI 2015

#### Classic(!)
+ Brown et al., "Class-Based n-Gram Models of Natural Language." [pdf] Computational Linguistics 1992


### Example Notes, Mini-Tutorials, Technical Reports

+ Yoav Goldberg. "A note on Latent Semantic Analysis" [pdf] Tech-report 
+ Yoav Goldberg and Omer Levy "word2vec explained: deriving Mikolov et al.'s negative-sampling word-embedding method" [pdf] Tech-report 2013
