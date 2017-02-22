---
title: Learning Class-relevant Features and Class-irrelevant Features via a Hybrid
  third-order RBM
abstract: Restricted Boltzmann Machines are commonly used in unsupervised learning
  to extract features from training data. Since these features are learned for regenerating
  training data a classifier based on them has to be trained. If only a few of the
  learned features are discriminative other non-discriminative features will distract
  the classifier during the training process and thus waste computing resources for
  testing. In this paper, we present a hybrid third-order Restricted Boltzmann Machine
  in which class-relevant features (for recognizing) and class-irrelevant features
  (for generating only) are learned simultaneously. As the classification task uses
  only the class-relevant features, the test itself becomes very fast. We show that
  class-irrelevant features help class-relevant features to focus on the recognition
  task and introduce useful regularization effects to reduce the norms of class-relevant
  features. Thus there is no need to use weight-decay for the parameters of this model.
  Experiments on the MNIST, NORB and Caltech101 Silhouettes datasets show very promising
  results. [pdf]
pdf: "./luo11a/luo11a.pdf"
layout: inproceedings
key: luo11a
month: 0
firstpage: 470
lastpage: 478
origpdf: http://jmlr.org/proceedings/papers/v15/luo11a/luo11a.pdf
sections: 
authors:
- given: Heng
  family: Luo
- given: Ruimin
  family: Shen
- given: Changyong
  family: Niu
- given: Carsten
  family: Ullrich
---