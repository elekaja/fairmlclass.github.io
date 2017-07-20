---
layout: default
---

# CS 294: Fairness in Machine Learning 

UC Berkeley, Fall 2017  
Time: Monday and Friday 2:30PM - 3:59PM  
Location: Soda 405  
Instructor: Moritz Hardt

Grading policy: 50% in class participation, 50% project

Undergraduate enrollment policy: With permission from the instructor only. Email
transcript, and description of any relevant prior projects or research experience.

## Summary

This is an intensive graduate seminar on fairness in machine learning. The focus
is on understanding and mitigating *discrimination based on sensitive
characteristics*, such as, gender, race, religion, physical ability, and sexual
orientation. Recent years have shown that unintended discrimination arises
naturally and frequently in the use of machine learning.

We will work systematically towards a technical understanding of this problem
mindful of its social and legal context.

# Outline (preliminary)

Last updated: July 19, 2017

## Sources of unfairness

[Big Data: A Report on Algorithmic Systems, Opportunity, and Civil Rights](https://obamawhitehouse.archives.gov/sites/default/files/microsites/ostp/2016_0504_data_discrimination.pdf)  
The White House. 2016.

[Big Data’s Disparate Impact](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2477899)  
Solon Barocas, Andrew Selbst. 2014.

Blog post: [How big data is unfair](https://medium.com/@mrtz/how-big-data-is-unfair-9aa544d739de)  
Moritz Hardt. 2014

[Semantics derived automatically from language corpora contain human-like
biases](http://science.sciencemag.org/content/356/6334/183)  
Aylin Caliskan, Joanna J. Bryson, Arvind Narayanan

## The quest for statistical fairness measures

[Sex Bias in Graduate Admissions: Data from Berkeley](http://science.sciencemag.org/content/187/4175/398)  
P. J. Bickel, E. A. Hammel, J. W. O'Connell. 1975.

Simpson’s paradox  
Pearl (Chapter 6)  
[Tech report](http://bayes.cs.ucla.edu/R264.pdf)

Blog post: [Approaching fairness in machine learning](http://blog.mrtz.org/2016/09/06/approaching-fairness.html)  
Moritz Hardt. 2016.

[Equality of Opportunity in Supervised
Learning](https://arxiv.org/abs/1610.02413)  
Moritz Hardt, Eric Price, Nathan Srebro. 2016.

### COMPAS and criminal justice

[Machine Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)  
Julia Angwin, Jeff Larson, Surya Mattu and Lauren Kirchner, ProPublica  
Code review:  
[github.com/probublica/compas-analysis](https://github.com/propublica/compas-analysis)  
[github.com/adebayoj/fairml](https://github.com/adebayoj/fairml)

[COMPAS Risk Scales: Demonstrating Accuracy Equity and Predictive
Parity](https://www.documentcloud.org/documents/2998391-ProPublica-Commentary-Final-070616.html)  
Northpointe Inc.

[Fairness in Criminal Justice Risk Assessments: The State of the
Art](https://arxiv.org/abs/1703.09207)  
Richard Berk, Hoda Heidari, Shahin Jabbari, Michael Kearns, Aaron Roth. 2017.

[Courts and Predictive
Algorithms](http://www.datacivilrights.org/pubs/2015-1027/Courts_and_Predictive_Algorithms.pdf)  
Angèle Christin, Alex Rosenblat, and danah boyd. 2015.  
[Discussion
paper](http://www.datacivilrights.org/pubs/2015-1027/WDN-Courts_and_Predictive_Algorithms.pdf)

## Trade-offs and impossibility results

### Classification, Calibration, Precision, Recall

[Probabilistic Outputs for Support Vector Machines and Comparisons to
Regularized Likelihood Methods](http://citeseer.ist.psu.edu/viewdoc/summary?doi=10.1.1.41.1639)  
John C. Platt. 1999.

[Inherent Trade-Offs in the Fair Determination of Risk Scores](https://arxiv.org/abs/1609.05807)  
Jon Kleinberg, Sendhil Mullainathan, Manish Raghavan. 2016.

[Fair prediction with disparate impact: A study of bias in recidivism prediction
instruments](https://arxiv.org/abs/1610.07524)  
Alexandra Chouldechova. 2016.

[Attacking discrimination with smarter machine learning](https://research.google.com/bigpicture/attacking-discrimination-in-ml/)  
An interactive visualization by Martin Wattenberg, Fernanda Viégas, and Moritz
Hardt. 2016.

### Inherent limitations of observational measures

[Equality of Opportunity in Supervised
Learning](https://arxiv.org/abs/1610.02413)  
Moritz Hardt, Eric Price, Nathan Srebro. 2016.

## Beyond observational measures

### Causal reasoning

Background reading:  
Pearl (Chapter 1--3)  
Pearl (Section 4.5.3)

[On causal interpretation of race in regressions adjusting for confounding and
mediating variables](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4125322/)  
Tyler J. VanderWeele and Whitney R. Robinson. 2014.

[Counterfactual Fairness](https://arxiv.org/abs/1703.06856)  
Matt J. Kusner, Joshua R. Loftus, Chris Russell, Ricardo Silva. 2017.

[Avoiding Discrimination through Causal
Reasoning](https://arxiv.org/abs/1706.02744)  
Niki Kilbertus, Mateo Rojas-Carulla, Giambattista Parascandolo, Moritz Hardt,
Dominik Janzing, Bernhard Schölkopf. 2017.

### Similarity modeling, matching 

[Fairness Through Awareness](https://arxiv.org/abs/1104.3913)  
Cynthia Dwork, Moritz Hardt, Toniann Pitassi, Omer Reingold, Rich Zemel. 2012.

[On the (im)possibility of fairness](https://arxiv.org/abs/1609.07236)  
Sorelle A. Friedler, Carlos Scheidegger, Suresh Venkatasubramanian. 2016.

[Why propensity scores should not be
used](https://gking.harvard.edu/files/gking/files/psnot.pdf)  
Gary King, Richard Nielson. 2016.

## Measurement

Blog post: [What's the most important thing in Statistics that's not in the
textbooks](http://andrewgelman.com/2015/04/28/whats-important-thing-statistics-thats-not-textbooks/)  
Andrew Gelman. 2015.

[Statistics and the Theory of
Measurement](http://www.lps.uci.edu/~johnsonk/CLASSES/MeasurementTheory/Hand1996.StatisticsAndTheTheoryOfMeasurement.pdf)  
David J. Hand. 1996.

## Legal and policy perspectives

[Big Data’s Disparate
Impact](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2477899)  
Solon Barocas, Andrew Selbst. 2014.

[It’s Not Privacy, and It’s Not
Fair](https://www.stanfordlawreview.org/online/privacy-and-big-data-its-not-privacy-and-its-not-fair)  
Cynthia Dwork, Deirdre K. Mulligan. 2013.


[The Trouble with Algorithmic
Decisions](http://journals.sagepub.com/doi/abs/10.1177/0162243915605575)  
Tal Zarsky. 2016.

## Background reading

[Causality](http://bayes.cs.ucla.edu/BOOK-2K/)  
Judea Pearl

[Counterfactuals and Causal
Inference](http://www.cambridge.org/catalogue/catalogue.asp?isbn=9781107065079)  
Morgan and Winship

[Equity](http://press.princeton.edu/titles/5379.html)  
Peyton Young. 1995.

[Weapons of Math Destruction](https://weaponsofmathdestructionbook.com/)  
Cathy O’Neil. 
