---
title: Lightweight Implementations of Probabilistic Programming Languages Via Transformational
  Compilation
abstract: 'We describe a general method of transforming arbitrary programming languages
  into probabilistic programming languages with straightforward MCMC inference engines.  Random
  choices in the program are ``"named"'''' with information about their position in
  an execution trace; these names are used in conjunction with a database of randomness
  to implement MCMC inference in the space of execution traces.  We encode naming
  information using lightweight source-to-source compilers.  Our method enables us
  to reuse existing infrastructure (compilers, interpreters, etc.) with minimal additional
  code, implying fast models with low development overhead.  We illustrate the technique
  on two languages, one functional and one imperative: Bher, a compiled version of
  the Church language which eliminates interpretive overhead of the original MIT-Church
  implementation, and Stochastic Matlab, a new open-source language. [pdf]'
pdf: "./wingate11a/wingate11a.pdf"
layout: inproceedings
key: wingate11a
month: 0
firstpage: 770
lastpage: 778
origpdf: http://jmlr.org/proceedings/papers/v15/wingate11a/wingate11a.pdf
sections: 
authors:
- given: David
  family: Wingate
- given: Andreas
  family: Stuhlmueller
- given: Noah
  family: Goodman
---