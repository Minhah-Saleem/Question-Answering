# Question-Answering
Question answering using DistilBERT on SQuADv2
- Implementation of Baseline DistilBERT:
  - Reference: https://colab.research.google.com/github/huggingface/notebooks/blob/main/examples/question_answering.ipynb#scrollTo=_trMUv7zfVce
- Data Augmentation:
  - Using Back-Translation (BT) and Synonym Replacement (SR)
  - Paraphrasing the Questions only
    - Reference: Tell Me How to Ask Again: Question Data Augmentation with Controllable Rewriting in Continuous Space (Liu et al., EMNLP 2020)
      https://aclanthology.org/2020.emnlp-main.467
- Data Sampling:
  - Active Learning: Selects challenging examples for data augmentation based on F1 scores, prioritizing diversity and usefulness over uniform sampling.
    - Reference: An Exploration of Data Augmentation and Sampling Techniques for Domain-Agnostic Question Answering (Longpre et al., 2019)
      https://aclanthology.org/D19-5829

