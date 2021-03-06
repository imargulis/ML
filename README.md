# ML Resources 

This repo contains references to various resources covering topics in machine learning.
By no means this is an exhaustive list. In order to keep it up-to-date I'll try to 
review it once in while.

## Misc:

### A survey on Automatic Differentiation:
https://arxiv.org/pdf/1502.05767.pdf

## Table of Contents
- [Intro Machine Learning](#machine-learning)
- [Deep Learning](#deep-learning)
- [Generative Model](#generative-model)
- [Reinforcement Learning](#reinforcement-learning)
- [Probabilistic Graphical Model](#graphical-model)
- [Optimization](#optimization)
- [Statistics](#statistics)
- [Topics in Machine Learning](#topics-in-machine-learning)
- [Math Background](#math-backgrounds)
- [Blogs and Podcasts](#blogs)


## Intro to Machine Learning
There are many ML resources, which position themselves as introductory<br/>
Below is the list of textbooks and courses I came across.

### Textbooks
- Machine Learning: A Probabilistic Perspective (Murphy) 
- Pattern Recognition and Machine Learning (Bishop) 
- The Elements of Statistical Learning (Hastie et al.)
- Pattern Classification (Duda et al.)
- Bayesian Reasoning and Machine Learning (Barber)
- Learning from Data (Abu-Mostafa) :sparkles:
- Foundations of Machine Learning (Mohri et al.)
- An Introduction to Computational Learning Theory (Kearns & Vazirani) 

### Courses (with videos)
- [Understanding Machine Learning: An introductory course in Machine Learning by Shai Shalev-Shwartz. 
   The course is in Hebrew and is based on the book with the same title.](http://www.cs.huji.ac.il/~shais/IML2014.html)
- [Caltech Learning from Data](https://work.caltech.edu/telecourse.html) :sparkles:   
- [Stanford CS229 Machine Learning](http://cs229.stanford.edu) :sparkles:
- [CMU 10701 Mahine Learning](http://www.cs.cmu.edu/~tom/10701_sp11/)
- [CMU 10702 Statistical Machine Learning](http://www.stat.cmu.edu/~larry/=sml/)
- [Oxford Machine Learning](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)

### Other courses
- [CMU 15859 Machine Learning Theory](http://www.cs.cmu.edu/~avrim/ML14/)
- [Berkeley CS281b/Stat241b Statistical Learning Theory](https://www.stat.berkeley.edu/~bartlett/courses/2014spring-cs281bstat241b/)
- [MIT 9.520 Statistical Learning Theory and Applications](http://www.mit.edu/~9.520/fall15/)
- [Statistical Learning Theory](http://www.shivani-agarwal.net/Teaching/E0370/Aug-2011/index.html)

## Deep Learning
Goodfellow et al. is the new classic. <br/>
For vision and NLP, Stanford lectures would be helpful.

### Textbook
- Deep Learning (Goodfellow et al.) :sparkles:

### Courses (with videos)
- [Stanford CS231n Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu) :sparkles:
- [Stanfrod CS224d Deep Learning for Natural Language Processing](http://web.stanford.edu/class/cs224n/)

### Courses (Practice)
- [TensorFlow for Deep Learning Research](http://cs20si.stanford.edu )
- [Deep Learning book](http://www.deeplearningbook.org/lecture_slides.html) :sparkles:
- [Stanfrod CS224s Spoken Language Processing](http://web.stanford.edu/class/cs224s/)
- [Oxford Deep Natural Language Processing](https://github.com/oxford-cs-deepnlp-2017/lectures)
- [CMU 11747 Neural Networks for NLP](http://phontron.com/class/nn4nlp2017/index.html)
- [Stanford Stat385 Theories of Deep Learning](https://stats385.github.io/)

### Tutorials
- [ICML 2017 Sequence-To-Sequence Modeling with Neural Networks](https://sites.google.com/view/seq2seq-icml17)


## Generative Model
I seperated generative model as an independent topic, <br/>
since I think it is big and important area.

### Lecture
- [Toronto CSC2541 Differentiable Inference and Generative Models](https://www.cs.toronto.edu/~duvenaud/courses/csc2541/index.html)
- [Toronto CSC2547 Learning Discrete Latent Structure](https://duvenaud.github.io/learn-discrete/)
- [Toronto CSC2541 Scalable and Flexible Models of Uncertainty](https://csc2541-f17.github.io/)


## Reinforcement Learning
For classic (non-deep) RL, Sutton & Barto is the classic. <br/>
For deep RL, lectures from Berkeley/CMU looks good.

### Textbook
- Reinforcement Learning: An Introduction (Sutton & Barto) :sparkles:

### Courses
- [UCL Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html) 
- [Berkeley CS294 Deep Reinforcement Leanring](http://rll.berkeley.edu/deeprlcourse/) 
- [CMU 10703 Deep Reinforcement Learing and Control](https://katefvision.github.io/)

### Tutorial
- [ICML 2017 Deep Reinforcement Learning, Decision Making, and Control](https://sites.google.com/view/icml17deeprl)


## Probabilistic Graphical Model

### Textbooks
- Probabilistic Graphical Models: Principles and Techniques (Koller & Friedman)
- Graphical Models, Exponential Families, and Variational Inference (Wainwright & Jordan) :sparkles:

### Courses
- [Stanford CS228 Probabilistic Graphical Models](http://cs.stanford.edu/~ermon/cs228/index.html)
- [CMU 10708 Probabilistic Graphical Models](http://www.cs.cmu.edu/~epxing/Class/10708/) :sparkles:


## Optimization
Boyd & Vandenberghe is the classic, but I think it's too boring. <br/>
Reading chapter 2-5 would be enough.

Bertsekas more concentrates on convex analysis. <br/>
Nocedal & Wright more concentrates on optimization.

### Textbook
- Convex Optimization (Boyd & Vandenberghe) :sparkles:
- Convex Optimization Theory (Bertsekas)
- Numerical Optimization (Nocedal & Wright)

### Lecture
- [Stanford EE364a Convex Optimization I](http://stanford.edu/class/ee364a/) :sparkles:
- [Stanford EE364b Convex Optimization II](http://stanford.edu/class/ee364a/)
- [MIT 6.253 Convex Analysis and Optimization](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-253-convex-analysis-and-optimization-spring-2012/index.htm)

### Tutorial
- [ICML 2017 Recent Advances in Stochastic Convex and Non-Convex Optimization](http://people.csail.mit.edu/zeyuan/topics/icml-2017)


## Online Learning Theory

For online learning, Cesa-Bianchi & Lugosi is the classic. <br/>
For multi-armed bandit, Bubeck & Cesa-Bianchi provides a good survey.


### Textbook (Online Learning)
- Prediction, Learning, and Games (Cesa-Bianchi & Lugosi)
- Regret Analysis of Stochastic and Nonstochastic Multi-armed Bandit Problems (Bubeck & Cesa-Bianchi)

### Tutorial
- [ICML 2017 Real World Interactive Learning](http://hunch.net/~rwil/)


## Topics related to Machine Learning
Miscellaneous topics directrly related to machine learning. <br/>

### Probability and Statistics
#### Books (General)
- Probability: Theory and Examples (Durrett)
- Theoretical Statistics (Keener)
- Stochastic Processes (Bass)
- Probability and Statistics Cookbook (Vallentin)

#### Books (Statistical Inference)
- All of Statistics (Wasserman)
- Computer Age Statistical Inference (Efron & Hastie) :sparkles:
- Time Series Analysis and Its Applications: With R Examples (Shumway & Stoffer)

#### Books (Nonparametrics)
- All of Nonparametric Statistics (Wasserman)
- Introduction to Nonparametric Estimation (Tsybakov)
- Gaussian Process and Machine Learning (Rasmussen & Williams) :sparkles:
- Bayesian Nonparametrics (Ghosh & Ramamoorthi) :sparkles:

#### Books (High Dimensions and Asymptotics)
- High-Dimensional Statistics: A Non-Asymptotic Viewpoint (Wainwright) :sparkles:
- Statistics for High-Dimensional Data (Bühlmann & van de Geer)
- Asymptotic Statistics (van der Vaart)
- Empirical Processes in M-Estimation (van der Vaart)

#### Courses 

### Lecture
- [Berkeley Stat281b Statistical Learning Theory](https://people.eecs.berkeley.edu/~bartlett/courses/281b-sp08/)
- [Berkeley Stat210a Theoretical Statistics I](https://www.stat.berkeley.edu/~wfithian/courses/stat210a/)
- [Berkeley Stat210b Theoretical Statistics II](https://www.stat.berkeley.edu/~bartlett/courses/2013spring-stat210b/)
- [Berkeley Stat210b Theoretical Statistics II](https://people.eecs.berkeley.edu/~jordan/courses/210B-spring17/)
- [Stanford Stat300a Theory of Statistics](https://web.stanford.edu/~lmackey/stats300a/)
- [Stanford CS369m Algorithms for Massive Data Set Analysis](http://cs.stanford.edu/people/mmahoney/cs369m/)
- [CMU 36755 Advanced Statistical Theory I](http://www.stat.cmu.edu/~arinaldo/36755/F16/)
- [MIT 18.S997 High-Dimensional Statistics](https://ocw.mit.edu/courses/mathematics/18-s997-high-dimensional-statistics-spring-2015/)
- [UCLA Theoretical Statistics](http://www.stat.ucla.edu/~arash.amini/teaching/stat200c/notes/)

### Linear Algebra
#### Books
- Linear Algebra (Hoffman & Kunze)
- Matrix Analysis (Horn & Johnson)
- Matrix Computations (Golub & Van Loan)
- The Matrix Cookbook (Petersen & Pedersen)
#### Courses

### Large Deviations
#### Books
- Concentration Inequalities and Martingale Inequalities (Chung & Lu)
- An Introduction to Matrix Concentration Inequalities (Tropp)

#### Courses

### Information Theory
#### Books
- Elements of Information Theory (Cover & Thomas)
- Information Theory, Inference, and Learning Algorithms (MacKay)

#### Courses
- [Information Theory: 2-semesters course](http://j.ee.washington.edu/~bilmes/classes/ee514a_fall_2013/#lectures)

### Network Science
- Networks, Crowds, and Markets (Easley & Kleinberg)
- Social and Economic Networks (Jackson)

### Random Processes 
- Markov Chains (Norris)
- Markov Chains and Mixing Times (Levin et al.)

### Game Theory
- Algorithmic Game Theory (Nisan et al.)
- Multiagent Systems (Shoham & Leyton-Brown)

### Combinatorics
- The Probabilistic Method (Alon & Spencer)
- A First Course in Combinatorial Optimization (Lee)

### Algorithm
- Introduction to Algorithms (Cormen et al.)
- Randomized Algorithms (Motwani & Raghavan)
- Approximation Algorithms (Vazirani)

### Geometric View
- Topological Data Analysis (Wasserman)
- Methods of Information Geometry (Amari & Nagaoka)
- Algebraic Geometry and Statistical Learning Theory (Watanabe)

### Some Lectures
- [MIT 18.409 Algorithmic Aspects of Machine Learning](http://people.csail.mit.edu/moitra/409.html)
- [MIT 18.409 An Algorithmist's Toolkit](http://stellar.mit.edu/S/course/18/fa09/18.409/)

### Tutorial
- [ICML 2017 Interpretable Machine Learning](http://people.csail.mit.edu/beenkim/icml_tutorial.html)
- [ICML 2017 Robustness Meets Algorithms (and Vice-Versa)](http://people.csail.mit.edu/moitra/robusttutorial.html)


## Blogs and Podcasts

- [Distill](http://distill.pub/)
- [Wild ML](http://www.wildml.com/)
- [Medium ML](https://medium.com/mlreview)

### Research Group

- [DeepMind Blog](https://deepmind.com/blog/?category=research)
- [OpenAI Blog](https://blog.openai.com/)
- [FAIR Blog](https://research.fb.com/blog/)
- [BAIR Blog](http://bair.berkeley.edu/blog/)
- [Columbia ML Seminar](https://casmls.github.io/)
- [Mathematical Coffees](https://mathematical-coffees.github.io/)
- [Lunit Tech Blog (Korean)](https://blog.lunit.io/category/paper-review/)

### Persoanal Blogs

- [Andrej Karpathy](http://karpathy.github.io/)
- [Christopher Olah](http://colah.github.io/)
- [inFERENCe](http://www.inference.vc/)
- [Off the convex path](http://www.offconvex.org/)
- [Math ∩ Programming](https://jeremykun.com/)
- [Sebastian Ruder](http://ruder.io/#open)
- [Dustin Tran](http://dustintran.com/blog/)
- [Ruotian Luo](http://ruotianluo.github.io/)
- [Yingzhen Li](http://www.yingzhenli.net/home/blog/)
- [Hunch.net](http://hunch.net/)
- [I’m a bandit](https://blogs.princeton.edu/imabandit/)
- [Bandit Algorithms](http://banditalgs.com/)
- [Sebastian Raschka](https://sebastianraschka.com/blog/index.html)

### Podcasts
- [The Talking Machines](http://www.thetalkingmachines.com/)
- [This week in Machine Learning&AI](https://twimlai.com/shows/)
- [Data Skeptic](http://dataskeptic.com/)
