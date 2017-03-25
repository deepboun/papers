# Papers 
List of papers that we will or did discuss during the sessions.

## Upcoming

| Date        | Title           | Presenter  |
| ------------- |:-------------:| -----:|
| 30/03/2017 | Neural Multi-Source Morphological Reinflection | Onur Gungor |
| TBA | A Convolutional Neural Network for Modelling Sentences | Çağıl Sönmez |

## Past

| Date        | Title           | Presenter  |
| ------------- |:-------------:| -----:|
| [23/03/2017](README.md#26012017scroll-collaborative-deep-learning-for-recommender-systems)      | Skip-Thought Vectors | Arda Çelebi |
| [16/03/2017](README.md#26012017scroll-collaborative-deep-learning-for-recommender-systems)      | Understanding Deep Learning Requires Rethinking Generalization | Miraç Göksu Öztürk |
| [09/03/2017](README.md#26012017scroll-collaborative-deep-learning-for-recommender-systems)      | Learning to learn by gradient descent by gradient descent | Arda Celebi |
| [03/02/2017](README.md#26012017scroll-collaborative-deep-learning-for-recommender-systems)      | Hierarchical Attention Networks for Document Classification | Çağıl Sönmez |
| [02/02/2017](README.md#26012017scroll-collaborative-deep-learning-for-recommender-systems)      | Understanding Neural Networks through Representation Erasure | Onur Gungor |
| [26/01/2017](README.md#26012017scroll-collaborative-deep-learning-for-recommender-systems)      | Collaborative Deep Learning For Recommender Systems | Mine Öğretir |
| [19/01/2017](README.md#19012017scroll-relation-extraction-perspective-from-convolutional-neural-networks) | Relation Extraction: Perspective from Convolutional Neural Networks | Çağıl Sönmez |

## Detailed List of Papers Upcoming

### (30/03/2017):scroll: **[Neural Multi-Source Morphological Reinflection](https://arxiv.org/pdf/1612.06027.pdf)**

  **Citation:** Katharina Kann, Ryan Cotterell and Hinrich Schütze. Neural Multi-Source Morphological Reinflection. EACL. 2017.

  **From Abstract:** We explore the task of multi-source morphological reinflection, which generalizes the standard, single-source version. The input consists of (i) a target tag and (ii) multiple pairs of source form and source tag for a lemma. The motivation is that it is beneficial to have access to more than one source form since different source forms can provide complementary information, e.g., different stems. 

  **Presenter:** Onur Gungor

  **Link:** https://arxiv.org/pdf/1612.06027.pdf
  
  **More info:** [Implementation](http://cistern.cis.lmu.de/med/)

### (TBA):scroll: **[A Convolutional Neural Network for Modelling Sentences](http://aclanthology.info/papers/a-convolutional-neural-network-for-modelling-sentences)**

  **Citation:** Nal Kalchbrenner, Edward Grefenstette and Phil Blunsom. 2014. A Convolutional Neural Network for Modelling Sentences. In Proceedings of ACL 2014.

  **One sentence from Abstract:** We describe a convolutional architecture dubbed the Dynamic Convolutional Neural Network (DCNN) that we adopt for the semantic modelling of sentences. The network uses Dynamic k-Max Pooling, a global pooling operation over linear sequences. The network handles input sentences of varying length and induces a feature graph over the sentence that is capable of explicitly capturing short and long-range relations. 

  **Presenter:** Çağıl Sönmez

  **Link:** http://aclanthology.info/papers/a-convolutional-neural-network-for-modelling-sentences
  
  **More info:** [Code](http://phd.nal.co/DCNN) [Theano implementation](https://github.com/FredericGodin/DynamicCNN) [A Sentiment Analysis tool written in Theono+Tornado](https://github.com/xiaohan2012/twitter-sent-dnn)

## Detailed List of Papers Past

### (19/01/2017):scroll: **[Relation Extraction: Perspective from Convolutional Neural Networks](http://aclanthology.info/papers/relation-extraction-perspective-from-convolutional-neural-networks)**

  **Citation:** Thien Huu Nguyen and Ralph Grishman. 2015a. Relation extraction: Perspective from convolutional neural networks. In The NAACL Workshop on Vector Space Modeling for NLP (VSM).

  **From Abstract:** In this work, we depart from these traditional approaches with complicated feature engineering by introducing a convolutional neural network for relation extraction that automatically learns features from sentences and minimizes the dependence on external toolkits and resources. Our model takes advantages of multiple window sizes for filters and pre-trained word embeddings as an initializer on a non-static architecture to improve the performance. We emphasize the relation extraction problem with an unbalanced corpus.

  **Link:** http://aclanthology.info/papers/relation-extraction-perspective-from-convolutional-neural-networks
  
  **More info:** [Implementation](https://github.com/hadyelsahar/CNN-RelationExtraction) 
  
### (26/01/2017):scroll: **[Collaborative Deep Learning For Recommender Systems](http://dl.acm.org/citation.cfm?id=2783273)**

  **Citation:** H. Wang, N. Wang, and D. Yeung. Collaborative deep learning for recommender systems. In KDD, 2015.

  **From Abstract:** We generalize recent advances in deep learning from i.i.d. input to non-i.i.d. (CF-based) input and propose in this paper a hierarchical Bayesian model called collaborative deep learning (CDL), which jointly performs deep representation learning for the content information and collaborative filtering for the ratings (feedback) matrix.

  **Link:** http://dl.acm.org/citation.cfm?id=2783273
  
  **More info:** [Related Material](http://www.wanghao.in/publication.html) 
  
### (02/02/2017) :scroll: **[Understanding Neural Networks through Representation Erasure](https://arxiv.org/abs/1612.08220)**

  **Citation** : Li, J., Monroe, W., & Jurafsky, D. (2016). Understanding Neural Networks through Representation Erasure. arXiv preprint arXiv:1612.08220.

  **From Abstract:** : In this paper, we propose a general methodology to analyze and interpret decisions from a neural model by observing the effects on the model of erasing various parts of the representation, such as input word-vector dimensions, intermediate hidden units, or input words.

  **Link** : https://arxiv.org/abs/1612.08220
  
### (02/03/2017) :scroll: **[Hierarchical Attention Networks for Document Classification](http://aclanthology.info/papers/hierarchical-attention-networks-for-document-classification)**

  **Citation** : Yang Zichao, Yang Diyi, Dyer Chris, He Xiaodong, Smola Alex, Hovy Eduard. Hierarchical Attention Networks for Document Classification in Proceedings of the 2016 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies:1480-1489 ACL 2016.

  **From Abstract:** : We propose a hierarchical attention network for document classification. Our model has two distinctive characteristics: (i) it has a hierarchical structure that mirrors the hierarchical structure of documents; (ii) it has two levels of attention mechanisms applied at the wordand sentence-level, enabling it to attend differentially to more and less important content when constructing the document representation. Experiments conducted on six large scale text classification tasks demonstrate that the proposed architecture outperform previous methods by a substantial margin. Visualization of the attention layers illustrates that the model selects qualitatively informative words and sentences.

  **Link** : http://aclanthology.info/papers/hierarchical-attention-networks-for-document-classification

### (09/03/2017):scroll: **Learning to learn by gradient descent by gradient descent(https://arxiv.org/abs/1606.04474)**

  **Citation** : Learning to learn by gradient descent by gradient descent by Marcin Andrychowicz, Misha Denil, Sergio Gomez, Matthew W. Hoffman, David Pfau, Tom Schaul, Brendan Shillingford, Nando de Freitas; NIPS 2016

  **From Abstract:** : Optimization algorithms are still designed by hand. In this paper we show how the design of an optimization algorithm can be cast as a learning problem, allowing the algorithm to learn to exploit structure in the problems of interest in an automatic way.

  **Link** : https://arxiv.org/abs/1606.04474
  
  **More info** :[Implementation](https://github.com/deepmind/learning-to-learn)
  
### (16/03/2017):scroll: **Understanding Deep Learning Requires Rethinking Generalization(https://arxiv.org/abs/1611.03530)**

  **Citation** : Chiyuan Zhang, Samy Bengio, Moritz Hardt, Benjamin Recht, Oriol Vinyals. ICLR 2017.

  **From Abstract:** : Our experiments establish that state-of-the-art convolutional networks for image classification trained with stochastic gradient methods easily fit a random labeling of the training data. This phenomenon is qualitatively unaffected by explicit regularization, and occurs even if we replace the true images by completely unstructured random noise. We corroborate these experimental findings with a theoretical construction showing that simple depth two neural networks already have perfect finite sample expressivity as soon as the number of parameters exceeds the number of data points as it usually does in practice.

  **Link** : https://arxiv.org/abs/1611.03530
  
 ### (16/03/2017):scroll: **Skip-Thought Vectors(https://arxiv.org/abs/1506.06726)**

  **Citation** : Ryan Kiros, Yukun Zhu, Ruslan Salakhutdinov, Richard S. Zemel, Antonio Torralba, Raquel Urtasun, Sanja Fidler. NIPS 2015.

  **From Abstract:** : We describe an approach for unsupervised learning of a generic, distributed sentence encoder. Using the continuity of text from books, we train an encoder-decoder model that tries to reconstruct the surrounding sentences of an encoded passage. Sentences that share semantic and syntactic properties are thus mapped to similar vector representations. We next introduce a simple vocabulary expansion method to encode words that were not seen as part of training, allowing us to expand our vocabulary to a million words.

  **Link** : https://arxiv.org/abs/1506.06726
  
  **More info**:[Implementation](https://github.com/tensorflow/models/tree/master/skip_thoughts)
  
