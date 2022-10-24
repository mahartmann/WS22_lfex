# Learning from explanations

**Syllabus**\
**WS 22/23**

Instructor: Mareike Hartmann (mareikeh@lst.uni-saarland.de) \
Meetings: Wednesdays 10:15 - 11:45,  C7.3 Room 1.12 \
Office Hours: by appointment 

Training NLP models with access to human explanations, i.e. information about why an instance is assigned a specific label, can improve data efficiency and model performance on in- and out-of-domain data compared to learning from label-level supervision alone. Adding to these empirical findings, similarity with the process of human learning makes learning from explanations a promising way to establish a fruitful human-machine interaction. Several methods for integrating explanation information into the learning process have been proposed, which rely on different types of explanations, e.g. natural language statements or word-level annotations, and different mechanisms for integrating explanation information into the learning process. In this seminar, we will discuss how to improve NLP models by learning from human explanations, covering different methods for learning from human explanations. In addition, we will discuss recent works investigating in which conditions explanation information is beneficial, and how the nature of human explanations can be characterized.

**Prerequisites:** Background in deep learning and natural language processing is required.

**Topics and papers to be discussed:**

*Methods for learning from highlight explanations*:

 * Zaidan et al. (2007): [Using “Annotator Rationales” to Improve Machine Learning for Text Categorization](https://aclanthology.org/N07-1033/) 
 * Zhang et al. (2016):	[Rationale-augmented convolutional neural networks for text classification.](https://aclanthology.org/D16-1076/)
 * Selvaraju et al. (2019): [Taking a HINT: Leveraging Explanations to Make
Vision and Language Models More Grounded](https://openaccess.thecvf.com/content_ICCV_2019/papers/Selvaraju_Taking_a_HINT_Leveraging_Explanations_to_Make_Vision_and_Language_ICCV_2019_paper.pdf)
 * Liu and Avci (2019): [Incorporating Priors with Feature Attribution on Text Classification](https://aclanthology.org/P19-1631/)
 * Antognini et al. (2021): [Interacting with explanations through critiquing](https://www.ijcai.org/proceedings/2021/0072.pdf)
 * Pruthi et al. (2022): [Evaluating Explanations: How Much Do Explanations from the Teacher Aid Students?](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00465/110436/Evaluating-Explanations-How-Much-Do-Explanations)
 
*Methods for learning from natural language explanations*:

 * Hancock et al. (2018): [Training Classifiers with Natural Language Explanations](https://aclanthology.org/P18-1175/)
 * Srivastava et al. (2017): [Joint Concept Learning and Semantic Parsing from Natural Language Explanations](https://aclanthology.org/D17-1161/)
 * Rajani et al. (2019): [Explain yourself! leveraging language models for commonsense reasoning.](https://aclanthology.org/P19-1487.pdf) 
 * Camburu et al. (2018): [e-SNLI: Natural Language Inference with Natural Language Explanations](https://papers.nips.cc/paper/2018/hash/4c7a167bb329bd92580a99ce422d6fa6-Abstract.html)
 * Wang et al. (2020): [Learning from Explanations with Neural Execution Tree](https://openreview.net/pdf?id=rJlUt0EYwS)
 * Murty et al. (2020): [ExpBERT: Representation Engineering with Natural Language Explanations](https://aclanthology.org/2020.acl-main.190.pdf)
 * Menon et al. (2022): [CLUES: A Benchmark for Learning Classifiers using Natural Language Explanations](https://aclanthology.org/2022.acl-long.451/)

*Learning from semi-structured explanations*:

 * Ye et al. (2020): [Teaching Machine Comprehension with Compositional Explanations](https://aclanthology.org/2020.findings-emnlp.145.pdf)
 * Yao et al. (2021): [Refining language models with compositional explanations](https://proceedings.neurips.cc/paper/2021/file/4b26dc4663ccf960c8538d595d0a1d3a-Paper.pdf) 
 
 *Which conditions enable successful learning from explanations*: 
 
 * Hase and Bansal (2022): [When Can Models Learn From Explanations?
A Formal Framework for Understanding the Roles of Explanation Data](https://aclanthology.org/2022.lnls-1.4.pdf)
 * Carton et al. (2022): [What to Learn, and How: Toward Effective Learning from Rationales](https://aclanthology.org/2022.findings-acl.86/)
 
 *Characterizing explanations*:
 
  * Carton et al. (2020): [Evaluating and Characterizing Human Rationales](https://aclanthology.org/2020.emnlp-main.747/)
  * Tan (2022): [On the Diversity and Limits of Human Explanations](https://aclanthology.org/2022.naacl-main.158.pdf)
  * Jansen et al. (2016): [What’s in an Explanation? Characterizing Knowledge and Inference Requirements for Elementary Science Exams]() 
