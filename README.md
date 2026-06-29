# reference
Useful books, papers, and lectures list

> If you are not familiar with Git, please read [HOWTO](HOWTO.md) to learn how to add content.

## Table of Contents

- [Template (Sample)](#template-sample)
- [Deep Learning](#deep-learning)
- [Statistical Learning](#statistical-learning)
- [Generative Models](#generative-models)
- [Reinforcement Learning & Multi-armed Bandits](#reinforcement-learning--multi-armed-bandits)
- [Conformal Prediction](#conformal-prediction)
- [Markov Chain Monte Carlo (MCMC)](#markov-chain-monte-carlo-mcmc)
- [Bayesian Nonparametric Modeling](#bayesian-nonparametric-modeling)
- [Uncertainty Quantification](#uncertainty-quantification)
- [Optimal Transport](#optimal-transport)
- [Information Theory](#information-theory)
- [Probability Theory](#probability-theory)
- [Mathematical Analysis and Measure Theory](#mathematical-analysis-and-measure-theory)
- [Python and Programming](#python-and-programming)

## Template (Sample)

> The following two entries serve as templates for organizing other resources.

* **Understanding Deep Learning** - Simon J.D. Prince, MIT Press, 2023
  * Link: [[Website]](https://udlbook.github.io/udlbook/) [[PDF]](https://udlbook.github.io/udlbook/) [[GitHub]](https://github.com/udlbook/udlbook)
  * Note: Comprehensive textbook covering deep learning fundamentals to advanced topics (Transformers, Diffusion Models). Balances theory and practice with clear visualizations.

* **Theoretical Foundations of Conformal Prediction** - Anastasios N. Angelopoulos, Rina Foygel Barber, Stephen Bates, Cambridge University Press (forthcoming), 24
  * Link: [[arXiv]](https://arxiv.org/abs/2411.11824) [[PDF]](https://arxiv.org/pdf/2411.11824)
  * Note: Research monograph on the theoretical foundations of conformal prediction and distribution-free inference. Covers permutation tests, exchangeability, and finite-sample guarantees for prediction sets.

## Deep Learning

### Book

* **Deep Learning** - Ian Goodfellow, Yoshua Bengio, Aaron Courville, MIT Press, 2016
  * Link: [[Website]](https://www.deeplearningbook.org/)
  * Note: Classic textbook covering mathematical foundations (linear algebra, probability, information theory) through CNNs, RNNs, and generative models.

* **Understanding Deep Learning** - Simon J.D. Prince, MIT Press, 2023
  * Link: [[Website]](https://udlbook.github.io/udlbook/) [[PDF]](https://udlbook.github.io/udlbook/) [[GitHub]](https://github.com/udlbook/udlbook)
  * Note: Comprehensive textbook covering deep learning fundamentals to advanced topics (Transformers, Diffusion Models). Balances theory and practice with clear visualizations.

### Paper

### Lecture

* **Learn PyTorch for Deep Learning: Zero to Mastery** - Daniel Bourke, 2023
  * Link: [[Website]](https://www.learnpytorch.io/)
  * Note: Pytorch Tutorial
 
* **CS336: Language Modeling from Scratch** - Stanford, Spring 2025
  * Link: [[Website]](https://cs336.stanford.edu/) [[Videos]](https://www.youtube.com/playlist?list=PLoROMvodv4rOY23Y0BoGoBGgQ1zmU_MT_)
  * Note: Hands-on course on large language models (LLM)

## Statistical Learning

### Book

* **Probabilistic Machine Learning: An Introduction** - Kevin Murphy, MIT Press, 2022
  * Link: [[Website]](https://probml.github.io/pml-book/book1.html) [[PDF]](https://github.com/probml/pml-book/releases/latest/download/book1.pdf)
  * Note: Mainly covers supervised learning algorithms from classical linear regression to modern deep learning models

* **Probabilistic Machine Learning: Advanced Topics** - Kevin Murphy, MIT Press, 2023
  * Link: [[Website]](https://probml.github.io/pml-book/book2.html) [[PDF]](https://github.com/probml/pml2-book/releases/latest/download/book2.pdf)
  * Note: Probably the most comprehensive machine learning book in existence

* **The Elements of Statistical Learning** - Trevor Hastie, Robert Tibshirani, Jerome Friedman, Springer, 2nd Edition, 2009
  * Link: [[Website]](https://hastie.su.domains/ElemStatLearn/) [[PDF]](https://hastie.su.domains/ElemStatLearn/printings/ESLII_print12_toc.pdf)
  * Note: Comprehensive treatment of statistical learning methods including regularization, kernel methods, trees, boosting, and neural networks.
 
* **Foundations of Machine Learning** - Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar, MIT Press, 2nd Edition, 2018.
  * Link: [[Website]](https://cs.nyu.edu/~mohri/mlbook/) [[PDF]](https://www.dropbox.com/s/38p0j6ds5q9c8oe/10290.pdf?dl=1)
  * Note: Covers PAC learning, rademacher complexity, support vector machines, boosting, on-line learning, algorithmic stability, dimensionality reduction, reinforcement learning, etc.
 
* **Learning Theory from First Principles** - Francis Bach, MIT Press, 2024.
  * Link: [[Website]](https://francisbach.com/my-book-is-out/) [[PDF]](https://www.di.ens.fr/~fbach/ltfp_book.pdf)
  * Note: Theoretical presentation of machine learning algorithms, with an emphasis on providing simple proofs with minimum prerequisites
 
* **Mathematical Analysis of Machine Learning Algorithms** - Tong Zhang, Cambridge University Press, 2023.
  * Link: [[Website]](https://tongzhang-ml.org/lt-book.html) [[PDF]](https://tongzhang-ml.org/lt-book/lt-book.pdf)
  * Note: Focuses on mathematical techniques used to analyze machine learning algorithms

### Paper

### Lecture

## Generative Models

### Book

* **Flow Matching Guide and Code** - Yaron Lipman, Marton Havasi, Peter Holderrieth et al., 2024
  * Link: [[arXiv]](https://arxiv.org/abs/2412.06264) [[GitHub]](https://github.com/facebookresearch/flow_matching)
  * Note: Introduces flow matching and its extensions such as non-Euclidean flow matching, discrete flow matching, and generator matching
 
* **The Principles of Diffusion Models** - Chieh-Hsin Lai, Yang Song, Dongjun Kim, Yuki Mitsufuji, Stefano Ermon, 2025
  * Link: [[Website]](https://the-principles-of-diffusion-models.github.io/) [[arXiv]](https://arxiv.org/abs/2510.21890)
  * Note: Introduces foundations of diffusion models through 3 complementary perspectives, while also presenting various algorithms for fast sampling
 
* **Foundations of Diffusion Models in General State Spaces: A Self-Contained Introduction** - Vincent Pauline, Tobias Höppe, Kirill Neklyudov et al., 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2512.05092)
  * Note: Introduces diffusion models on both continuous and discrete state spaces
 
* **Demystifying Variational Diffusion Models** - Fabio De Sousa Ribeiro, Ben Glocker, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2401.06281)
  * Note: Introduces diffusion models from a variational inference perspective

### Paper

* **Terminal Velocity Matching** - Linqi Zhou, Mathias Parger, Ayaan Haque, Jiaming Song, 2026
  * Link: [[arXiv]](https://arxiv.org/abs/2511.19797)
  * Note:
 
* **Transition Matching: Scalable and Flexible Generative Modeling** - Neta Shaul, Uriel Singer, Itai Gat, Yaron Lipman, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2506.23589)
  * Note: No official github repository as of February 2026

* **Mean Flows for One-step Generative Modeling** - Zhengyang Geng, Mingyang Deng, Xingjian Bai, J. Zico Kolter, Kaiming He, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2505.13447) [[GitHub]](https://github.com/Gsunshine/py-meanflow)
  * Note: One-step generative modeling by learning the average velocity field (Note that there is also another official github repository containing the original JAX code)
 
* **A Unified Approach to Analysis and Design of Denoising Markov Models** - Yinuo Ren, Grant M. Rotskoff, Lexing Ying, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2504.01938)
  * Note:
 
* **A friendly introduction to triangular transport** - Maximilian Ramgraber, Daniel Sharp, Mathieu Le Provost, Youssef Marzouk, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2503.21673)
  * Note: tutorial on triangular transport maps
 
* **Flow Matching: Markov Kernels, Stochastic Processes and Transport Plans** - Christian Wald, Gabriele Steidl, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2501.16839)
  * Note: Review paper
 
* **Generator Matching: Generative modeling with arbitrary Markov processes** - Peter Holderrieth, Marton Havasi, Jason Yim et al., 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2410.20587)
  * Note: No official github repository as of February 2026
 
* **Stochastic Interpolants: A Unifying Framework for Flows and Diffusions** - Michael S. Albergo, Nicholas M. Boffi, Eric Vanden-Eijnden, 2025
  * Link: [[Website]](https://interpolants.github.io/) [[arXiv]](https://arxiv.org/abs/2303.08797) [[GitHub]](https://github.com/malbergo/stochastic-interpolants)
  * Note: Unification of flow matching and diffusion models via the concept of stochastic interpolants

### Lecture

* **An Introduction to Flow Matching and Diffusion Models (MIT 6.S184)** - Peter Holderrieth, Ezra Erives, 2025
  * Link: [[Website]](https://diffusion.csail.mit.edu) [[arXiv]](https://arxiv.org/abs/2506.02070) [[GitHub]](https://github.com/eje24/iap-diffusion-labs)
  * Note: Highly recommended introduction to flow matching and its connection with diffusion models. Example code and associated video lectures are also available

* **A Practical Introduction to Diffusion Models (MIT 6.S183)** - Chenyang Yuan, Cole Becker, Artem Lukoianov et al., 2026
  * Link: [[Website]](https://www.practical-diffusion.org/)
  * Note: Introductory course on diffusion models. Example code and associated video lectures are also available
 
* **Diffusion & Flow Matching (CMU 10-799)** - Yutong (Kelly) He, 2026
  * Link: [[Website]](https://kellyyutonghe.github.io/10799S26/)
  * Note: Comprehensive course starting from diffusion models, flow matching and ending with fast sampling methods and discrete variants. Also has a very nice resource section.

* **Course on Diffusion Models for Generative AI (IFML)** - Sanjay Shakkottai, 2025
  * Link: [[Website]](https://ifml.institute/node/551)
  * Note: Focuses on the mathematical foundations of diffusion models, flow matching, and diffusion language models
 
* **Let us Flow Together** - Qiang Liu, 2024
  * Link: [[Website]](https://rectifiedflow.github.io/) [[PDF]](https://www.cs.utexas.edu/~lqiang/PDF/flow_book.pdf) [[GitHub]](https://github.com/lqiang67/rectified-flow)
  * Note: Introduces rectified flows
    
## Reinforcement Learning & Multi-armed Bandits

### Book

* **Reinforcement Learning from Human Feedback** - Nathan Lambert, 2026
  * Link: [[Website]](https://rlhfbook.com/) [[PDF]](https://rlhfbook.com/book.pdf) [[GitHub]](https://github.com/natolambert/rlhf-book)
  * Note: An introduction to RLHF and post-training focused on language models.

* **Multi-Agent Reinforcement Learning: Foundations and Modern Approaches** - Stefano V. Albrecht, Filippos Christianos, Lukas Schäfer, MIT Press, 2024
  * Link: [[Website]](https://www.marl-book.com/) [[PDF]](https://www.marl-book.com/download/marl-book.pdf) [[GitHub]](https://github.com/marl-book/codebase)
  * Note: Introduction to multi-agent reinforcement learning, an area of machine learning in which multiple decision-making agents learn to optimally interact in a shared environment.

* **Distributional Reinforcement Learning** - Marc G. Bellemare, Will Dabney, Mark Rowland, MIT Press, 2023
  * Link: [[Website]](https://www.distributional-rl.org/) [[PDF]](https://watermark02.silverchair.com/book_9780262374026.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAywwggMoBgkqhkiG9w0BBwagggMZMIIDFQIBADCCAw4GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMZxFKjh2hIjH9JyJCAgEQgIIC33nBaL_hE-DBhAtP9Rh7QdMrs2JFTCfBqWqRlYRC0ia437Xtd_MlwYGTTtqvcqAUEWLybBcYPpUI8UsOt07g6MSKpTm-XP9UJ9zReQLT296jJFg7XrOvFhH2VXVrlMxclsAgP6XD6yXdT8HOT7QtIN3jShHo9SwZbE5vob5C7CmrLxVDbE-dA9qtmmMEc26ZjDvqT5MvJ3WFurjKcVKvoLX19mdS9LIMzhm1lId5nINTKppoZaLa5qFn3qBARPMhWoDsIOHEeo9oIQDAK_3KZjv6m2hDvODHlKP5qczTBskFBYdFUBH3v1K_IPyADrcJbfYA3ptHFR6Ttx_LsSlaB_YcCIAyHAsdFToR_5gUmAEwXHWZFsp2FYvL_FYl1mK8DayK6sckO9Yn4UpceCrAjHCntrHVfZLisdVFzDek5SH-AvM7F5HQabHOEEcTUgDDWQan53yGUkhdhMyvKalI-Hx242Fgzy1BfonBKCJlZGnVYzjnwuw_py5-2AzxIsGajD3aI2NExfVqQxiAV9Y4SdAisal8EWsFf35X1_idz1OA5koorje6WRQHXEEWLmmGjbOktpLIE0kQ6OjEwyqCSN7NaWT-VNI2xDrWXunAOjXsX98P54R5mNtWUClUhqHcAP-AuRRgrYyOIm5zB91YiB0QqTXW__8MMcEL4cekb1uLQGO8xUhVjzGkAKl04WzDG4_gJQhg03f-fQliqdovoyVX0DXzXSjGBxJnXZgiLxbr59AKQfs5xDphLQGfTtvMG-DOAgGcFOjr1HFymR9ijUzcpFTpaYt3QzSpOcK50urxrtxwo3JcWUuU5WTpSJl9LrrCVjq1zA9TWMq5pNVGP8D41um9pbgE2L2VtQhYmWWeCEVjNUWWEdc2Jtdg-2GdwqHHdbWKVawWhz-bEDPfeTScY0nBG3pr1PMTROOKsi7SrbX5uuexU5-D5i-ZlaJxt2BpTy4T77uAo4J80XOKhQ) [[GitHub]](https://github.com/natolambert/rlhf-book)
  * Note: An introduction to distributional RL
 
* **Reinforcement Learning: An Overview** - Kevin Murphy, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2412.05265)
  * Note: Big-picture overview of the field of (deep) reinforcement learning

* **Reinforcement Learning: Theory and Algorithms** - Alekh Agarwal, Kianté Brantley, Nan Jiang, Sham M. Kakade, Wen Sun, 2026
  * Link: [[Website]](https://rltheorybook.github.io/) [[PDF]](https://rltheorybook.github.io/rltheorybook_ABJKS.pdf)
  * Note: Book on the theory of reinforcement learning
 
* **Reinforcement Learning: An Introduction** - Richard S. Sutton, Andrew G. Barto, MIT Press, 2nd Edition, 2020
  * Link: [[Website]](http://incompleteideas.net/book/the-book.html) [[PDF]](http://incompleteideas.net/book/RLbook2020.pdf) [[GitHub]](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
  * Note: Classical introduction to reinforcement learning
    
* **Bandit Algorithms** - Tor Lattimore and Csaba Szepesvári, Cambridge University Press, 2020
  * Link: [[Website]](https://banditalgs.com/about/) [[PDF]](https://tor-lattimore.com/downloads/book/book.pdf)
  * Note: Focuses on the mathematical analysis of multi-armed bandit algorithms
 
* **Bandit Convex Optimisation** - Tor Lattimore, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2402.06535) [[PDF]](https://arxiv.org/pdf/2402.06535)
  * Note: Comprehensive reference on zeroth-order convex optimization algorithms in the multi-armed bandit literature

### Paper

### Lecture

* **Deep Reinforcement Learning (Stanford CS 224R)** - Chelsea Finn, 2025
  * Link: [[Website]](https://cs224r.stanford.edu/) [[Video]](https://www.youtube.com/playlist?list=PLoROMvodv4rPwxE0ONYRa_itZFdaKCylL)
  * Note: Lecture material on reinforcement learning with deep neural networks

* **Introduction to Reinforcement Learning (Harvard CS/Stat 184(0))** - Alexander Cai, 2025
  * Link: [[Website]](https://rlbook.adzc.ai/) [[PDF]](https://rlbook.adzc.ai/An-Introduction-to-Reinforcement-Learning.pdf)
  * Note: Lecture notes introducing the foundations of reinforcement learning

* **Foundations of Reinforcement Learning and Interactive Decision Making (MIT 9.522)** - Dylan J. Foster, Alexander Rakhlin, 2023
  * Link: [[arXiv]](https://arxiv.org/abs/2312.16730)
  * Note: Lecture notes introducing the foundations of reinforcement learning and interactive decision making from a statistical perspective

## Conformal Prediction

### Book

* **Theoretical Foundations of Conformal Prediction** - Anastasios N. Angelopoulos, Rina Foygel Barber, Stephen Bates, Cambridge University Press (forthcoming), 2024
  * Link: [[arXiv]](https://arxiv.org/abs/2411.11824) [[PDF]](https://arxiv.org/pdf/2411.11824)
  * Note: Research monograph on the theoretical foundations of conformal prediction and distribution-free inference. Covers permutation tests, exchangeability, and finite-sample guarantees for prediction sets.

### Paper

* **Non-monotonicity in Conformal Risk Control** - Tareq Aldirawi, Yun Li, Wenge Guo, 2026
  * Link: [[arXiv]](https://arxiv.org/abs/2604.01502)
  * Note:

* **Conformal Risk Control for Non-Monotonic Losses** - Anastasios N. Angelopoulos, 2026
  * Link: [[arXiv]](https://arxiv.org/abs/2602.20151)
  * Note:

* **A Gentle Introduction to Conformal Prediction and Distribution-Free Uncertainty Quantification** - Anastasios N. Angelopoulos, Stephen Bates, 2021
  * Link: [[arXiv]](https://arxiv.org/abs/2107.07511)
  * Note: Accessible tutorial on conformal prediction basics, split conformal, and coverage guarantees.

* **Predictive Inference with the Jackknife+** - Rina Foygel Barber, Emmanuel J. Candès, Aaditya Ramdas, Ryan J. Tibshirani, Annals of Statistics, 2021
  * Link: [[arXiv]](https://arxiv.org/abs/1905.02928)
  * Note: Introduces Jackknife+ and CV+ methods for distribution-free predictive inference.

### Lecture

## Markov Chain Monte Carlo (MCMC)

### Book

### Paper

### Lecture

## Bayesian Nonparametric Modeling

### Book

* **Gaussian Processes and Reproducing Kernels: Connections and Equivalences** - Motonobu Kanagawa, Philipp Hennig, Dino Sejdinovic, Bharath K. Sriperumbudur, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2506.17366)
  * Note:

* **Bayesian Optimization** - Roman Garnett, Cambridge University Press, 2023
  * Link: [[Website]](https://bayesoptbook.com/) [[PDF]](https://bayesoptbook.com/book/bayesoptbook.pdf)
  * Note: Nice, comprehensive introduction to gaussian processes and bayesian optimization

* **Gaussian Processes for Machine Learning** - Carl Rasmussen, Christopher Williams, MIT Press, 2006
  * Link: [[Website]](https://gaussianprocess.org/gpml/chapters/) [[PDF]](https://gaussianprocess.org/gpml/chapters/RW.pdf)
  * Note: Reference for gaussian processes from a machine learning context.

### Paper

### Lecture

## Uncertainty Quantification

### Book

### Paper

* **Repro Samples Method for a Performance Guaranteed Inference in General and Irregular Inference Problems** - Minge Xie, Peng Wang, 2026
  * Link: [[arXiv]](https://arxiv.org/abs/2402.15004)
  * Note:
 
* **Proper scoring rules for estimation and forecast evaluation** - Kartik Waghmare, Johanna Ziegel, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2504.01781)
  * Note:
 
* **Repro Samples Method for Finite- and Large-Sample Inferences** - Min-ge Xie, Peng Wang, 2022
  * Link: [[arXiv]](https://arxiv.org/abs/2206.06421)
  * Note:

### Lecture

## Optimal Transport

### Book

* **An Introduction to Sliced Optimal Transport** - Khai Nguyen, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2508.12519)
  * Note: Introduction to sliced optimal transport

* **Statistical optimal transport** - Sinho Chewi, Jonathan Niles-Weed, Philippe Rigollet, 2024
  * Link: [[arXiv]](https://arxiv.org/abs/2407.18163)
  * Note: Textbook on optimal transport from a statistical perspective
 
* **Computational Optimal Transport** - Gabriel Peyré, Marco Cuturi, 2020
  * Link: [[arXiv]](https://arxiv.org/abs/1803.00567)
  * Note: Textbook on optimal transport from a computational/numerical perspective

* **Optimal Transport for Applied Mathematicians** - Filippo Santambrogio, Birkhäuser, 2015
  * Link: [[PDF]](https://math.univ-lyon1.fr/~santambrogio/OTAM-cvgmt.pdf)
  * Note: Textbook on optimal transport

### Paper

* **Statistical Properties of Rectified Flow** - Gonzalo Mena, Arun Kumar Kuchibhotla, Larry Wasserman, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2511.03193)
  * Note: Introduces statistical properties of the rectified flow estimator for the OT map

* **Statistical Inference for Optimal Transport Maps: Recent Advances and Perspectives** - Sivaraman Balakrishnan, Tudor Manole, Larry Wasserman, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2506.19025)
  * Note: Review on recent advances in estimating and developing limit theorems for the OT map

* **{ Euclidean, Metric, and Wasserstein } Gradient Flows: an overview** - Filippo Santambrogio, 2016
  * Link: [[arXiv]](https://arxiv.org/abs/1609.03890)
  * Note: Expository paper on the theory of gradient flows

### Lecture

* **Optimal Transport for Machine Learners** - Gabriel Peyré, 2025
  * Link: [[arXiv]](https://arxiv.org/abs/2505.06589)
  * Note: Notes on optimal transport and its applications to machine learning
  
## Information Theory

### Book

* **Information Theory: From Coding to Learning** - Yury Polyanskiy, Yihong Wu, Cambridge University Press, 2023
  * Link: [[PDF]](https://people.lids.mit.edu/yp/homepage/data/itbook-export.pdf)
  * Note: Modern textbook on information theory that also covers recent applications in statistical learning theory

* **Information Theory, Inference, and Learning Algorithms** - David MacKay, Cambridge University Press, 2003
  * Link: [[Website]](https://www.inference.org.uk/mackay/itila/) [[PDF]](https://www.inference.org.uk/itprnn/book.pdf)
  * Note: Textbook covering information theory and its connections to Bayesian inference

* **Elements of Information Theory** - Thomas Cover, Joy Thomas, John Wiley & Sons, Inc., 2nd Edition, 2006
  * Link: [[PDF]](http://staff.ustc.edu.cn/~mfy/InfoTheory/Complements/Elements%20of%20Information%20Theory%202nd.pdf)
  * Note: Standard textbook on information theory

### Paper

### Lecture

* **Statistics and Information Theory** - John Duchi, 2025
  * Link: [[PDF]](https://web.stanford.edu/class/ee377/lecture-notes.pdf)
  * Note: Comprehensive book on statistical applications of information theory

## Probability Theory

### Book

* **Probability: Theory and Examples** - Rick Durrett, Cambridge University Press, 5th Edition, 2019
  * Link: [[PDF]](https://services.math.duke.edu/~rtd/PTE/PTE5_011119.pdf)
  * Note: Standard graduate textbook on measure-theoretic probability covering laws of large numbers, CLT, martingales, and Markov chains.
 
* **High-Dimensional Probability** - Roman Vershynin, Cambridge University Press (forthcoming), 2nd Edition, 2025
  * Link: [[Website]](https://www.math.uci.edu/~rvershyn/papers/HDP-book/HDP-book.html#) [[PDF]](https://www.math.uci.edu/~rvershyn/papers/HDP-book/HDP-2.pdf) [[Associated Lectures]](https://www.math.uci.edu/~rvershyn/teaching/hdp/hdp.html)
  * Note: Graduate textbook on high-dimensional random objects. Covers concentration of measure, chaining, random matrices, etc.
 
* **Concentration inequalities: A non-asymptotic theory of independence** - Stéphane Boucheron, Gábor Lugosi, Pascal Massart, Oxford University Press, 2016
  * Link: [[Website]](https://stephane-v-boucheron.fr/publication/zb-math-06586491/) [[PDF]](http://home.ustc.edu.cn/~zyx240014/USTCProbability/files/Concentration_inequalities.pdf)
  * Note: Reference for concentration inequalities

### Paper


### Lecture

## Mathematical Analysis and Measure Theory

### Book

* **Measure, Integration & Real Analysis** - Sheldon Axler, Springer, 2020
  * Link: [[Website]](https://measure.axler.net/) [[PDF]](https://measure.axler.net/MIRA.pdf)
  * Note:
 
* **Basic/Advanced Real Analysis** - Anthony W. Knapp, Birkhäuser, 2017
  * Link: [[Website]](https://www.math.stonybrook.edu/~aknapp/download.html)
  * Note: 

* **Real and Complex Analysis** - Walter Rudin, McGraw-Hill, 3rd Edition, 1987
  * Note: Classic "Big Rudin" covering measure theory, integration, and functional analysis foundations.
    
* **Applied Analysis** - John Hunter, Bruno Nachtergaele, 2001
  * Link: [[Website]](https://www.math.ucdavis.edu/~hunter/book/pdfbook.html) [[PDF]](https://www.math.ucdavis.edu/~bxn/applied_analysis.pdf)
  * Note: Covers parts of mathematical analysis that are useful in applications including Hilbert/Banach space theory, spectral theory of bounded operators, Schwartz space & tempered distributions, Fourier transforms, etc.

### Paper

### Lecture

## Python and Programming

### Book

### Lecture

