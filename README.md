# Binary classification with only positive examples

## What is positive-unlabeled classification?
Basically dealing with cases when we have only partially labeled data, one vs rest kind of use cases. For instance, in the land cover data, urban vs non-urban where the non-urban areas are too diverse than the labeled data. This can also be framed more like an outlier analysis problem. One way is to recognize the negative samples from the unlabeled data and then feed them to classical binary classification models. These methods generally yeild poor results. The other way is to treat unlabeled data as negative samples and use some kind of decayed weight. Re-weighting the unlabeled data strategy has its limitations.

## Thoughts
From an application perspective - automatic label identification such as automatically tagging photos by providing a collection of photos being of the same class.
Discriminative PU learning approaches have their limitations, more recently GANs

## Recent papers 
### arXiv archive
- Nov 2017, [A generative adversarial framework for positive-unlabeled classification](https://arxiv.org/pdf/1711.08054.pdf)
- May 2017, [Semi-Supervised AUC Optimization based on Positive-Unlabeled Learning](https://arxiv.org/pdf/1705.01708.pdf)
- Apr 2017, [Risk Minimization Framework for Multiple Instance Learning from Positive and Unlabeled Bags (https://arxiv.org/pdf/1704.06767.pdf)
- Mar 2017, [Positive-Unlabeled Learning with Non-Negative Risk Estimator](https://arxiv.org/pdf/1703.00593.pdf)
- Feb 2017, [Recovering True Classifier Performance in Positive-Unlabeled Learning](https://arxiv.org/pdf/1702.00518.pdf)
- Aug 2016, [Efficient Training for Positive Unlabeled Learning](https://arxiv.org/pdf/1608.06807.pdf)
- Feb 2016, [Active Learning from Positive and Unlabeled Data](https://arxiv.org/pdf/1602.07495.pdf)
- Feb 2014, [A Robust Ensemble Approach to Learn From Positive and Unlabeled Data Using SVM Base Models] (https://arxiv.org/pdf/1402.3144.pdf)

### ICML archive
- Aug 2017, [Semi-Supervised Classification Based on Classification from Positive and Unlabeled Data](http://proceedings.mlr.press/v70/sakai17a/sakai17a.pdf)

### ICLR archive


Criteria:
1. Is it exciting to the team? Not exactly
2. Can it be framed as a strong capability (rather than an algorithm) Yes
3. Is it a subject that is more possible now than in two years, and likely to be more possible/transformative still in a couple of years. That usually means some or all of the following things are true:
  * There is excitement (ideally including concrete breakthroughs) in the research community - Yes, quite a few papers
  * Economic constraints (e.g. hardware) have lessened/disappeared
  * There has there been a commoditization of tooling
  * Data is available (especially to FFL!)
4. Is it useful to our existing clients? definitely
5. It is appealing to potential clients? yes
6. It it possible to build a prototype? will have to find out how this works

http://search.arxiv.org:8081/?query=positive+unlabeled+learning&in=cs&qid=1518036631666bas_nCnN_-1123160627&startat=0

