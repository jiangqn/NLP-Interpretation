# NLP-Interpretation
A paper list for interpreting neural networks in natural language processing.

## Review

- **[arXiv-16]**: The mythos of model interpretability. [[paper]](https://arxiv.org/pdf/1606.03490.pdf) [[book]](https://dl.acm.org/doi/pdf/10.1145/3236386.3241340)

- **[arXiv-17]**: Towards A Rigorous Science of Interpretable Machine Learning. [[paper]](https://arxiv.org/pdf/1702.08608.pdf)

- **[TACL-19]**: Analysis Methods in Neural Language Processing: A Survey. [[paper]](https://www.aclweb.org/anthology/Q19-1004.pdf) [[appendix]](https://boknilev.github.io/nlp-analysis-methods/)
> This survey reviews methods of analyzing, understanding and interpreting neural network models in NLP. Existing works can be categorized as the following 6 categories: (i) Probing task methods for exploiting what kind of linguistic information is captured in neural networks. (ii) Visualization. (iii) The compilation of challenge sets, or test suites for fine-grained evaluation. (iv) The generation and use of adversarial examples to probe weaknesses of neural networks. (v) Explaining model predictions. (vi) Other methods.

- **[ACL-20 Tutorial]**: Interpretability and Analysis in Neural NLP. [[slides]](https://sebastiangehrmann.com/assets/files/acl_2020_interpretability_tutorial.pdf)

- **[EMNLP-20 Tutorial]**: Interpreting Predictions of NLP Models. [[slides]](https://github.com/Eric-Wallace/interpretability-tutorial-emnlp2020/blob/master/tutorial_slides.pdf)

- **[ZJU]**: 模型可解释性关键技术、应用及其安全性研究综述. [[paper]](https://nesa.zju.edu.cn/download/%E6%A8%A1%E5%9E%8B%E5%8F%AF%E8%A7%A3%E9%87%8A%E6%80%A7%E5%85%B3%E9%94%AE%E6%8A%80%E6%9C%AF%E3%80%81%E5%BA%94%E7%94%A8%E5%8F%8A%E5%85%B6%E5%AE%89%E5%85%A8%E6%80%A7%E7%A0%94%E7%A9%B6%E7%BB%BC%E8%BF%B0.pdf)

## Workshop

- **[EMNLP-18]**: BlackboxNLP 2018: Analyzing and interpreting neural networks for NLP. [[workshop]](https://www.aclweb.org/anthology/events/emnlp-2018/#w18-54) 

- **[ACL-19]**: BlackboxNLP 2019: Analyzing and interpreting neural networks for NLP. [[workshop]](https://www.aclweb.org/anthology/events/acl-2019/#w19-48)

## Paper

### Probing Task Method

- **[arXiv-21]**: Probing Classifiers: Promises, Shortcomings, and Alternatives. [[paper]](https://arxiv.org/pdf/2102.12452.pdf)

- **[ACL-16]**: Does String-Based Neural MT Learn Source Syntax? [[paper]](https://www.aclweb.org/anthology/D16-1159.pdf)

> This paper exploited: (i) Does the encoder learn syntactic information about the source sentence? (ii) What kind of syntactic information is learned, and how much? They predicted syntactic labels and extracted syntactic trees using encoder intermediate representations to examine whether encoder capture syntactic information. Experimental results showed that: (i) Encoder captures both global and local syntactic information of the source sentence, and different information tends to be stored at different layers. (ii) Much syntactic  information is learned, while various types of syntactic information are still missing.

- **[EMNLP-16]**: Analyzing linguistic knowledge in sequential model of sentence. [[paper]](https://www.aclweb.org/anthology/D16-1079.pdf)

- **[ICLR-17]**: Fine-grained analysis of sentence embeddings using auxiliary prediction tasks. [[paper]](https://openreview.net/pdf?id=BJh6Ztuxl)

- **[ACL-17]**: What do Neural Machine Translation Models Learn about Morphology? [[paper]](https://www.aclweb.org/anthology/P17-1080.pdf)

- **[EACL-17]**: How Grammatical is Character-level Neural Machine Translation? Assessing MT Quality with Contrastive Translation Pairs. [[paper]](https://www.aclweb.org/anthology/E17-2060.pdf)

- **[IJCNLP-17]**: Evaluating Layers of Representation in Neural Machine Translation on Part-of-Speech and Semantic Tagging Tasks. [[paper]](https://www.aclweb.org/anthology/I17-1001.pdf)

- **[Machine Translation-17]**: The representational geometry of word meanings acquired by neural machine translation models. [[paper]](https://link.springer.com/article/10.1007%2Fs10590-017-9194-2)

- **[ACL-18]**: What you can cram into a single vector: Probing sentence embeddings for linguistic properties. [[paper]](https://www.aclweb.org/anthology/P18-1198.pdf)

- **[ACL-18]**: LSTMs Can Learn Syntax-Sensitive Dependencies Well, But Modeling Structure Makes Them Better. [[paper]](https://www.aclweb.org/anthology/P18-1132.pdf)

- **[ACL-18]**: Are BLEU and Meaning Representation in Opposition? [[paper]](https://www.aclweb.org/anthology/P18-1126.pdf)

- **[ACL-18]**: Deep RNNs Encode Soft Hierarchical Syntax. [[paper]](https://www.aclweb.org/anthology/P18-2003.pdf)

- **[EMNLP-18]**: Dissecting Contextual Word Embeddings: Architecture and Representation. [[paper]](https://arxiv.org/pdf/1808.08949.pdf)

- **[EMNLP-18-workshop]**: An Analysis of Encoder Representations in Transformer-Based Machine Translation. [[paper]](https://www.aclweb.org/anthology/W18-5431.pdf)

- **[EMNLP-18-workshop]**: Under the Hood: Using Diagnostic Classifiers to Investigate and Improve how Language Models Track Agreement Information. [[paper]](https://www.aclweb.org/anthology/W18-5426.pdf)

- **[ICLR-19]**: What do you learn from context? Probing for sentence structure in contextualized word representations. [[paper]](https://arxiv.org/pdf/1905.06316.pdf)

- **[NAACL-19]**: A Structural Probe for Finding Syntax in Word Representations. [[paper]](https://www.aclweb.org/anthology/N19-1419.pdf)

- **[ACL-19]**: BERT Rediscovers the Classical NLP Pipeline. [[paper]](https://www.aclweb.org/anthology/P19-1452.pdf)

- **[ACL-19]**: What does BERT learn about the structure of language? [[paper]](https://www.aclweb.org/anthology/P19-1356.pdf)

- **[ACL-19]**: Assessing the Ability of Self-Attention Networks to Learn Word Order. [[paper]](https://www.aclweb.org/anthology/P19-1354.pdf)

- **[ACL-19-workshop]**: Open Sesame: Getting Inside BERT’s Linguistic Knowledge. [[paper]](https://www.aclweb.org/anthology/W19-4825.pdf)

- **[CIKM-19]**: How Does BERT Answer Questions? A Layer-Wise Analysis of Transformer Representations. [[paper]](https://arxiv.org/pdf/1909.04925.pdf)

- **[EMNLP-19]**: Designing and Interpreting Probes with Control Tasks. [[paper]](https://www.aclweb.org/anthology/D19-1275.pdf)

- **[EMNLP-19]**: Encoders Help You Disambiguate Word Sensesin Neural Machine Translation. [[paper]](https://www.aclweb.org/anthology/D19-1149.pdf)

- **[EMNLP-19]**: Revealing the Dark Secrets of BERT. [[paper]](https://www.aclweb.org/anthology/D19-1445.pdf)

- **[RANLP-19]**: Understanding Neural Machine Translation by Simplification:The Case of Encoder-free Models. [[paper]](https://www.aclweb.org/anthology/R19-1136.pdf)

- **[arXiv-20]**: What's so special about BERT's layers? A closer look at the NLP pipeline in monolingual and multilingual models. [[paper]](https://arxiv.org/pdf/2004.06499.pdf)

- **[arXiv-20]**: Telling BERT's full story: from Local Attention to Global Aggregation. [[paper]](https://arxiv.org/pdf/2004.05916.pdf)
  
- **[ACL-20]**: Interpretability Analysis for Named Entity Recognition to Understand System Predictions and How They Can Improve. [[paper]](https://arxiv.org/pdf/2004.04564.pdf)

- **[ACL-20]**: Probing Linguistic Features of Sentence-Level Representations in Neural Relation Extraction. [[paper]](https://arxiv.org/pdf/2004.08134.pdf)

- **[ACL-20]**: What is Learned in Visually Grounded Neural Syntax Acquisition. [[paper]](https://arxiv.org/pdf/2005.01678.pdf)

- **[arXiv-20]**: Probing Text Models for Common Ground with Visual Representations. [[paper]](https://arxiv.org/pdf/2005.00619.pdf)

- **[ACL-20]**: Spying on your neighbors: Fine-grained probing of contextual embeddings for information about surrounding words. [[paper]](https://arxiv.org/pdf/2005.01810.pdf)

- **[ACL-20]**: A Tale of a Probe and a Parser. [[paper]](https://arxiv.org/pdf/2005.01641.pdf)

- **[arXiv-20]**: Can BERT Reason? Logically Equivalent Probes for Evaluating the Inference Capabilities of Language Models. [[paper]](https://arxiv.org/pdf/2005.00782.pdf)

- **[ACL-20]**: Probing the Probing Paradigm: Does Probing Accuracy Entail Task Relevance? [[paper]](https://arxiv.org/pdf/2005.00719.pdf)

- **[ACL-20]**: Intermediate-Task Transfer Learning with Pretrained Models for Natural Language Understanding: When and Why Does It Work? [[paper]](https://arxiv.org/pdf/2005.00628.pdf)

- **[arXiv-20]**: Assessing the Bilingual Knowledge Learned by Neural Machine Translation Models. [[paper]](https://arxiv.org/pdf/2004.13270.pdf)

- **[arXiv-20]**: Quantifying the Contextualization of Word Representationswith Semantic Class Probing. [[paper]](https://arxiv.org/pdf/2004.12198.pdf)

### Visualization Method

- **[ICLR-16]**: Visualizing and Understanding Recurrent Networks. [[paper]](https://arxiv.org/pdf/1506.02078.pdf)

- **[NAACL-16]**: Visualizing and Understanding Neural Models in NLP. [[paper]](https://www.aclweb.org/anthology/N16-1082.pdf)

- **[arXiv-16]**: Representation of linguistic form and function in recurrent neural networks. [[paper]](https://arxiv.org/pdf/1602.08952.pdf)

- **[ACL-17]**: Visualizing and Understanding Neural Machine Translation. [[paper]](https://www.aclweb.org/anthology/P17-1106.pdf)

- **[IJCNLP-17]**: What does Attention in Neural Machine TranslationPay Attention to? [[paper]](https://www.aclweb.org/anthology/I17-1004.pdf)

- **[IJCAI-18]**: Visualisation and "Diagnostic Classi ers" Reveal how Recurrent and Recursive Neural Networks Process Hierarchical Structure. [[paper]](https://www.ijcai.org/Proceedings/2018/0796.pdf)

- **[IEEE-VIS-18]**: Seq2Seq-Vis: A Visual Debugging Tool for Sequence-to-Sequence Models. [[paper]](https://arxiv.org/pdf/1804.09299.pdf)

- **[EMNLP-18-workshop]**: Extracting Syntactic Trees from Transformer Encoder Self-Attentions.[[paper]](https://www.aclweb.org/anthology/W18-5444.pdf)

- **[ACL-19-workshop]**: From Balustrades to Pierre Vinken:Looking for Syntax in Transformer Self-Attention. [[paper]](https://www.aclweb.org/anthology/W19-4827.pdf)

- **[ACL-19-workshop]**: What does BERT look at? An Analysis of BERT’s Attention. [[paper]](https://www.aclweb.org/anthology/W19-4828.pdf)

- **[arXiv-20]**: Amnesic Probing: Behavioral Explanation with Amnesic Counterfactuals. [[paper]](https://arxiv.org/pdf/2006.00995.pdf)

### Attribution

- **[ICML-17]**: Understanding Black-box Predictions via Influence Functions. [[paper]](https://arxiv.org/pdf/1703.04730.pdf)

- **[ICML-17]**: Axiomatic Attribution for Deep Networks. [[paper]](https://arxiv.org/pdf/1703.01365.pdf)

- **[EMNLP-17]**: A causal framework for explaining the predictions of black-box sequence-to-sequence models. [[paper]](https://www.aclweb.org/anthology/D17-1042.pdf)

- **[NIPS-18]**: Sanity Checks for Saliency Maps. [[paper]](https://arxiv.org/pdf/1810.03292.pdf)

- **[EMNLP-19]**: Towards Understanding Neural Machine Translation with Word Importance. [[paper]](https://arxiv.org/pdf/1909.00326.pdf)

> (i) Word importance estimation aims to indentify most important words to translation performance in original input. (ii) The paper proposed a gradient-based method which outperforms erasion-based method and attention-based method. (iii) Additional analysis shows that words of certain syntactic categories have higher importance while the categories vary across language.

- **[arXiv-20]**: Aligning Faithful Interpretations with their Social Attribution. [[paper]](https://arxiv.org/pdf/2006.01067.pdf)

- **[arXiv-20]**:  CausaLM: Causal model explanation through counterfactual language models. [[paper]](https://arxiv.org/pdf/2005.13407.pdf)

### Attention Interpretability

- **[WMT-18]**: An Analysis of Attention Mechanisms: The Case of Word Sense Disambiguation in Neural Machine Translation. [[paper]](https://www.aclweb.org/anthology/W18-6304.pdf)

- **[SIGIR-19-workshop]**: Do Transformer Attention Heads Provide Transparency in Abstractive Summarization? [[paper]](https://arxiv.org/pdf/1907.00570.pdf)

- **[ACL-19]**: Analyzing Multi-Head Self-Attention: Specialized Heads Do the Heavy Lifting, the Rest Can Be Pruned. [[paper]](https://arxiv.org/pdf/1905.09418.pdf)

- **[NAACL-19]**: Attention is not Explanation. [[paper]](https://www.aclweb.org/anthology/N19-1357.pdf)

- **[arXiv-19]**: Attention Interpretability Across NLP Tasks. [[paper]](https://arxiv.org/pdf/1909.11218.pdf)

- **[ACL-19]**: Is Attention Interpretable? [[paper]](https://www.aclweb.org/anthology/P19-1282.pdf)

- **[EMNLP-19]**: Attention is not not Explanation. [[paper]](https://www.aclweb.org/anthology/D19-1002.pdf)

- **[ACL-20]**: Towards Transparent and Explainable Attention Models. [[paper]](https://arxiv.org/pdf/2004.14243.pdf)

### Representation Similarity Analysis

- **[ICLR-16]**: Convergent Learning: Do different neural networks learn the same representations? [[paper]](https://arxiv.org/pdf/1511.07543v3.pdf)

- **[NIPS-17]**: SVCCA: Singular Vector Canonical Correlation Analysis for Deep Learning Dynamics and Interpretability. [[paper]](https://arxiv.org/pdf/1706.05806.pdf)

- **[NIPS-18]**: Insights on representational similarity in neuralnetworks with canonical correlation. [[paper]](https://papers.nips.cc/paper/7815-insights-on-representational-similarity-in-neural-networks-with-canonical-correlation.pdf)

- **[ICML-19]**: Similarity of Neural Network Representations Revisited. [[paper]](https://arxiv.org/pdf/1905.00414.pdf)

- **[NAACL-19]**: Understanding Learning Dynamics Of Language Models with SVCCA. [[paper]](https://www.aclweb.org/anthology/N19-1329.pdf)

- **[EMNLP-19]**: The Bottom-up Evolution of Representations in the Transformer: A Study with Machine Translation and Language Modeling Objectives. [[paper]](https://www.aclweb.org/anthology/D19-1448.pdf)

- **[ACL-20]**: Similarity Analysis of Contextual Word Representation Models. [[paper]](https://arxiv.org/pdf/2005.01172.pdf)

### Explanation Evaluating

- **[NAACL-18]**: Comparing Automatic and Human Evaluation of Local Explanations for Text Classification. [[paper]](https://www.aclweb.org/anthology/N18-1097.pdf)

- **[ACL-19-workshop]**: Evaluating Recurrent Neural Network Explanations. [[paper]](https://www.aclweb.org/anthology/W19-4813.pdf)

- **[ACL-20]**: Evaluating Explainable AI: Which Algorithmic Explanations Help Users Predict Model Behavior? [[paper]](https://arxiv.org/pdf/2005.01831.pdf)

- **[ACL-20]**: Evaluating Explanation Methods for Neural Machine Translation. [[paper]](https://arxiv.org/pdf/2005.01672.pdf)

- **[ACL-20]**: Towards Faithfully Interpretable NLP Systems: How should we define and evaluate faithfulness? [[paper]](https://arxiv.org/pdf/2004.03685.pdf)

### Information-Theory based Interpretation

- **[HUJJ-99]**: The Information Bottleneck Method. [[paper]](https://www.cs.huji.ac.il/labs/learning/Papers/allerton.pdf)

- **[ITW-15]**: Deep Learning and the Information Bottleneck Principle. [[paper]](https://arxiv.org/pdf/1503.02406.pdf)

- **[arXiv-17]**: Opening the black box of Deep Neural Networks via Information. [[paper]](https://arxiv.org/pdf/1703.00810.pdf)

- **[ACL-20]**: Information-Theoretic Probing for Linguistic Structure. [[paper]](https://arxiv.org/pdf/2004.03061.pdf)

- **[arXiv-20]**: Information-Theoretic Probing with Minimum Description Length. [[paper]](https://arxiv.org/pdf/2003.12298.pdf) [[blog]](https://lena-voita.github.io/posts/mdl_probes.html)

- **[ACL-20]**: It’s Easier to Translateout ofEnglish thanintoit:Measuring Neural Translation Difficulty by Cross-Mutual Information. [[paper]](https://arxiv.org/pdf/2005.02354.pdf)

### Natural Language Explanations

- **[ACL-20]**: ExpBERT: Representation Engineering with Natural Language Explanations. [[paper]](https://arxiv.org/pdf/2005.01932.pdf)

### Optimization and Generalization of Deep Learning

- **[ICLR-17]**: Understanding deep learning requires rethinking generalization. [[paper]](https://arxiv.org/pdf/1611.03530.pdf)

- **[arXiv-18]**: Reconciling modern machine learning practice and the bias-variance trade-off. [[paper]](https://arxiv.org/pdf/1812.11118.pdf)

- **[ICLR-19]**: The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks. [[paper]](https://arxiv.org/pdf/1803.03635.pdf)

- **[arXiv-20]**: When BERT Plays the Lottery, All Tickets Are Winning. [[paper]](https://arxiv.org/pdf/2005.00561.pdf)

### Individual Neurons Analysis

- **[AAAI-19]**: What Is One Grain of Sand in the Desert? Analyzing Individual Neurons in Deep NLP Models. [[paper]](https://arxiv.org/pdf/1812.09355.pdf)

- **[ICLR-19]**: How Important Is a Neuron? [[paper]](https://arxiv.org/pdf/1805.12233.pdf)

- **[ICLR-19]**: Identifying and Controlling Important Neurons in Neural Machine Translation. [[paper]](https://arxiv.org/pdf/1811.01157.pdf)

### Difficulty of Interpreting

- **[blog]**: The Problem of Faithfulness in (Neural Network) NLP Interpretations. [[blog]](https://medium.com/@alonjacovi/the-problem-of-faithfulness-in-neural-network-nlp-interpretations-ee98d7027cbd)

- **[arXiv-17]**: The (Un)reliability of saliency methods. [[paper]](https://arxiv.org/pdf/1711.00867.pdf)

- **[ICML-18-workshop]**: On the Robustness of Interpretability Methods. [[paper]](https://arxiv.org/pdf/1806.08049.pdf)

- **[EMNLP-18]**: Pathologies of Neural Models Make Interpretations Difficult. [[paper]](https://arxiv.org/pdf/1804.07781.pdf)

- **[NIPS-18]**: Towards Robust Interpretability with Self-Explaining Neural Networks. [[paper]](https://arxiv.org/pdf/1806.07538)

- **[AAAI-19]**: Interpretation of Neural Networks is Fragile. [[paper]](https://arxiv.org/pdf/1710.10547.pdf)

### Adversarial Examples for Probing the weaknesses of Neural Networks

- **[ICLR-19]**: Adversarial Examples Are Not Bugs, They Are Features. [[paper]](https://arxiv.org/pdf/1905.02175.pdf)

- **[arXiv-19]**: What does BERT Learn from Multiple-Choice Reading Comprehension Datasets? [[paper]](https://arxiv.org/pdf/1910.12391.pdf)

### Local Interpretable Model-agnostic Explanations (LIME)

- **[NAACL-16]**: "Why Should I Trust You?": Explaining the Predictions of Any Classifier. [[paper]](https://www.aclweb.org/anthology/N16-3020.pdf)

### Interpreting with Nearest Neighbors

- **[EMNLP-18-workshop]**: Interpreting Neural Networks with Nearest Neighbors. [[paper]](https://www.aclweb.org/anthology/W18-5416.pdf)

### Other

- **[ACL-16-workshop]**: Explaining Predictions of Non-Linear Classifiers in NLP. [[paper]](https://arxiv.org/pdf/1606.07298)

- **[EAMT-18]**: An analysis of source context dependency in neural machine translation. [[paper]](https://rua.ua.es/dspace/bitstream/10045/76048/1/EAMT2018-Proceedings_21.pdf)

- **[EMNLP-18]**: Interpreting Recurrent and Attention-Based Neural Models: a Case Study on Natural Language Inference. [[paper]](https://www.aclweb.org/anthology/D18-1537.pdf)

- **[NeurIPS-19]**: Are Sixteen Heads Really Better than One? [[paper]](https://arxiv.org/pdf/1905.10650.pdf)

- **[ACL-19]**: Interpretable Neural Predictions with Differentiable Binary Variables. [[paper]](https://www.aclweb.org/anthology/P19-1284.pdf)

- **[arXiv-20]**: Lost in Embedding Space: Explaining Cross-Lingual Task Performance with Eigenvalue Divergence. [[paper]](https://arxiv.org/pdf/2001.11136.pdf)
> This paper proposed a language similarity (distance) measure (called EVD) based on isomorphism between monolingual embedding spaces, which shows strong correlation with performance of BLI and downstream cross-lingual tasks (machine translation, cross-lingual dependency parsing and POS tagging). Additional analysis shows that isomorphism-based language distances and typologically driven language distances capture different aspects of language characters. The combination of EVD and typologically driven language distances has stronger correlation with cross-lingual task performance.

- **[arXiv-20]**: Toward Interpretability of Dual-Encoder Models for Dialogue Response Suggestions. [[paper]](https://arxiv.org/pdf/2003.04998.pdf)

- **[arXiv-20]**: A Primer in BERTology: What we know about how BERT works. [[paper]](https://arxiv.org/pdf/2002.12327.pdf)
> This paper is an overview of studies about what BERT learned and how BERT works. (i) **BERT embedding:** BERT’s contextualized embeddings form distinct and clear clusters corresponding to word senses, which confirms that the basic distributional hypothesis holds for these representations. Later BERT layers produce more context-specific representations. (ii) **What knowledge does BERT have:** BERT encodes syntactic knowledge, semantic knowledge and world knowledge partially. But the encoding of that knowledge does not indicate that it actually relies on that knowledge. (iii) **Localizing linguistic knowledge:** Most self-attention heads do not directly encode any non-trivial linguistic information. Some BERT heads seem to specialize in certain types of syntactic relations.  Lower layers have the most linear word order information. syntactic information is the most prominent in the middle BERT layers. The final layers of BERT are the most task-specific. Semantics is spread across the entire model. (iv) **Training BERT:** Lots of improvements of pre-training objectives, model architecture choices and fine-tuning have been made, see more details in the paper. (v) **How big should BERT be:** BERT is over-parametrized and can be compressed. (vi) **Multilingual BERT:**  mBERT seems to naturally learn high-quality cross-lingual word alignments and can retrieve parallel sentences. mBERT is simply trained on a multilingual corpus, with no language IDs, but it encodes language identities, and adding the IDs in pre-training was not beneficial.  (vii) **Limitations and Directions for further research:** A linguistic pattern is not observed by our probing classifier does not guarantee that it is not there, and the observation of a pattern does not tell us how it is used.  A more complex probe might be able to recover more information, but it becomes less clear whether this is due to the probed model or the probing classifier. BERT does not form good representations for numbers and fails to generalize away from training data. BERT performs bad at verbal reasoning and can not reason with its world knowledge.

- **[ACL-20]**: Generating Fact Checking Explanations. [[paper]](https://arxiv.org/pdf/2004.05773.pdf)

- **[arXiv-20]**: Do sequence-to-sequence VAEs learn global features of sentences? [[paper]](https://arxiv.org/pdf/2004.07683.pdf)

- **[ACL-20]**: Influence Paths for Characterizing Subject-Verb Number Agreement in LSTM Language Models. [[paper]](https://arxiv.org/pdf/2005.01190.pdf)

- **[ACL-20]**: How Does Selective Mechanism Improve Self-Attention Networks? [[paper]](https://arxiv.org/pdf/2005.00979.pdf)

- **[ACL-20]**: Contextualizing Hate Speech Classifiers with Post-hoc Explanation. [[paper]](https://arxiv.org/pdf/2005.02439.pdf)

- **[arXiv-20]**: What-if I ask you to explain: Explaining the effects of perturbations in procedural text. [[paper]](https://arxiv.org/pdf/2005.01526.pdf)

- **[arXiv-20]**: Teaching Machine Comprehension with Compositional Explanations. [[paper]](https://arxiv.org/pdf/2005.00806.pdf)

- **[ACL-20]**: Obtaining Faithful Interpretations from Compositional Neural Networks. [[paper]](https://arxiv.org/pdf/2005.00724.pdf)

- **[ACL-20]**: ESPRIT: Explaining Solutions to Physical Reasoning Tasks. [[paper]](https://arxiv.org/pdf/2005.00730.pdf)

- **[ICLR-20]**: Understanding and Improving Information Transfer in Multi-Task Learning. [[paper]](https://arxiv.org/pdf/2005.00944.pdf)

- **[arXiv-20]**: Causal Mediation Analysis for Interpreting Neural NLP: The Case of Gender Bias. [[paper]](https://arxiv.org/pdf/2004.12265.pdf)

### Weak Related Papers

- **[ACL-20]**: What are the Goals of Distributional Semantics? [[paper]](https://arxiv.org/pdf/2005.02982.pdf)

- **[ACL-20]**: Generalized Entropy Regularization or:There’s Nothing Special about Label Smoothing. [[paper]](https://arxiv.org/pdf/2005.00820.pdf)
