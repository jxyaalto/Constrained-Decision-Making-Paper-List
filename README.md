# Constrained-Decision-Making-Paper-List

This paper collection of contrained decision making classifies the papers according to the types of constraints they deal with. In the same class, papers are sorted by time. In the future, more reasonable classification standards will be adopted.

Constrained Policy Optimization is closely related to safe exploration, which means providing certain degree of safety guarantee during exploration procedure. More about exploration in reinforcement learning can be found in [RL-Exploration-Paper-Lists](https://github.com/apexrl/RL-Exploration-Paper-Lists/blob/master/README.md).

## Reinforcement Learning Under Constraints

### Review / Survey / Blog

* <[Datasets and Benchmarks for Offline Safe Reinforcement Learning](https://arxiv.org/pdf/2306.09303.pdf)> by Zuxin Liu, Zijian Guo, Haohong Lin, Yihang Yao, Jiacheng Zhu, Zhepeng Cen, Hanjiang Hu, Wenhao Yu, Tingnan Zhang, Jie Tan, Ding Zhao, 2023.

* <[Trustworthy Reinforcement Learning Against Intrinsic Vulnerabilities: Robustness, Safety, and Generalizability](https://arxiv.org/pdf/2209.08025.pdf)> by Mengdi Xu, Zuxin Liu, Peide Huang, Wenhao Ding, Zhepeng Cen, Bo Li, and Ding Zhao. 2022.

* <[Constrained MDPs and the Reward Hypothesis](https://readingsml.blogspot.com/2020/03/constrained-mdps-and-reward-hypothesis.html)> by Csaba Szepesvári, 2020.

* <[Exploration-Exploitation in Constrained MDPs](https://arxiv.org/pdf/2003.02189.pdf)> by Yonathan Efroni, Shie Mannor and Matteo Pirotta, 2020.

* <[Safety Gym](https://openai.com/blog/safety-gym/)> by Joshua Achiam, Alex Ray and Dario Amodei, 2019.

* <[Benchmarking Safe Exploration in Deep Reinforcement Learning](https://pdfs.semanticscholar.org/4d0f/6a6ffcd6ab04732ff76420fd9f8a7bb649c3.pdf)> by Alex Ray, Joshua Achiam and Dario Amodei, 2019.

* <[A Comprehensive Survey on Safe Reinforcement Learning](https://pdfs.semanticscholar.org/c0f2/c4104ef6e36bb67022001179887e6600d24d.pdf)> by Javier Garc´ıa and Fernando Fern´andez, 2015.

### Constraints on expectations

This type of constraints includes the total expected cost until the state reaches some set M, the expected discounted cost, expected average cost, etc.

* <[Constraint-Conditioned Policy Optimization for Versatile Safe Reinforcement Learning](https://arxiv.org/pdf/2310.03718.pdf)> by Yihang Yao, Zuxin Liu, Zhepeng Cen, Jiacheng Zhu, Wenhao Yu, Tingnan Zhang, Ding Zhao, 2023.

* <[Constrained Decision Transformer for Offline Safe Reinforcement Learning](https://arxiv.org/pdf/2302.07351.pdf)> by Zuxin Liu, Zijian Guo, Yihang Yao, Zhepeng Cen, Wenhao Yu, Tingnan Zhang, Ding Zhao, 2023.

* <[Saute RL: Almost Surely Safe Reinforcement Learning Using State Augmentation](https://arxiv.org/pdf/2202.06558.pdf)> by Aivar Sootla, Alexander I. Cowen-Rivers, Taher Jafferjee, Ziyan Wang, David Mguni, Jun Wang, Haitham Bou-Ammar, 2022.

* <[Constrained Variational Policy Optimization for Safe Reinforcement Learning](https://arxiv.org/pdf/2201.11927.pdf)> by Zuxin Liu, Zhepeng Cen, Vladislav Isenbaev, Wei Liu, Zhiwei Steven Wu, Bo Li, Ding Zhao, 2022.

* <[CRPO: A New Approach for Safe Reinforcement Learning with Convergence Guarantee](http://proceedings.mlr.press/v139/xu21a/xu21a.pdf)> by Tengyu Xu, Yingbin Lang and Guanghui Lan, 2021.

* <[Accelerating Safe Reinforcement Learning with Constraint-mismatched Baseline Policies](http://proceedings.mlr.press/v139/yang21i/yang21i.pdf)> by Tsung-Yen Yang, Justinian Rosca, Karthik Narasimhan and Peter J. Ramadge, 2021.

* <[First Order Optimization in Policy Space for Constrained Deep Reinforcement Learning](https://arxiv.org/pdf/2002.06506)> by Yiming Zhang, Quan Vuong and Keith W. Ross, 2020.

* <[Responsive Safety in Reinforcement Learning by PID Lagrangian Methods](https://arxiv.org/pdf/2007.03964.pdf)> by Adam Stooke, Joshua Achiam and Pieter Abbeel, 2020.

* <[Safe Policy Learning for Continuous Control](https://openreview.net/pdf?id=HkxeThNFPH)> by Yinlam Chow, Ofir Nachum, Aleksandra Faust, Edgar Duenez-Guzman and Mohammad Ghavamzadeh, 2020.

* **[PCPO]** <[Projection-Based Constrained Policy Optimization](https://pdfs.semanticscholar.org/80ad/925b669e8d54dab4dd7c123e33a655612339.pdf)> by Tsung-Yen Yang, Justinian Rosca, Karthik Narasimhan and Peter J. Ramadge, 2020.

* **[RCPO]** <[Reward Constrained Policy Optimization](https://arxiv.org/pdf/1805.11074)> by Chen Tessler, Daniel J. Mankowitz and Shie Mannor, 2019.

* <[Value Constrained Model-free Continuous Control](https://arxiv.org/pdf/1902.04623)> by Steven Bohez, Abbas Abdolmaleki, Michael Neunert, Jonas Buchli, Nicolas Heess and Raia Hadsell, 2019.

* <[Convergent Policy Optimization for Safe Reinforcement Learning](http://papers.nips.cc/paper/8576-convergent-policy-optimization-for-safe-reinforcement-learning.pdf)> by Ming Yu, Zhuoran Yang, Mladen Kolar and Zhaoran Wang, 2019.

* <[Safe Q-Learning Method Based on Constrained Markov Decision Processes](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8895829)> by Yangyang Ge, Fei Zhu, Xinghong Ling and Quan Liu, 2019.

* <[Batch Policy Learning under Constraints](https://arxiv.org/pdf/1903.08738)> by Hoang M. Le, Cameron Voloshin and Yisong Yue, 2019.

* <[Constrained Cross-Entropy Method for Safe Reinforcement Learning]()> by Min Wen and Ufuk Topcu, 2018.

* <[A Lyapunov-based Approach to Safe Reinforcement Learning](http://papers.nips.cc/paper/8032-a-lyapunov-based-approach-to-safe-reinforcement-learning.pdf)> by Yinlam Chow, Ofir Nachum and Edgar Duenez-Guzman, 2018.

* **[CPO]** <[Constrained Policy Optimization](https://dl.acm.org/ft_gateway.cfm?id=3305384&type=pdf)> by Joshua Achiam, David Held, Aviv Tamar and Pieter Abbeel, 2017.

* **[CMDP]** <[Constrained Markov Decision Process](http://www-sop.inria.fr/members/Eitan.Altman/PAPERS/h.pdf)> by Eitan ALTMAN, 1999.
  
  This book establishes the framework of CMDPs and solve the optimization problem with known model by linear programming. But it does not give the solution for optimial policy in high dimensional control.

### Hard constraints

* <[Constrained Episodic Reinforcement Learning in Concave-convex and Knapsack Settings](https://arxiv.org/pdf/2006.05051.pdf)> by Kianté Brantley, Miroslav Dudik, Thodoris Lykouris, Sobhan Miryoosefi, Max Simchowitz, Aleksandrs Slivkins and Wen Sun, 2020.

* <[Safe Exploration in Continuous Action Spaces](https://arxiv.org/pdf/1801.08757)> by Gal Dalal, Krishnamurthy Dvijotham, Matej Vecerik, Todd Hester, Cosmin Paduraru and Yuval Tassa, 2018.

### Chance constraints

* <[Chance Constrained Policy Optimization for Process Control and Optimization](https://arxiv.org/pdf/2008.00030)> by Panagiotis Petsagkourakis, Ilya Orson Sandoval, Eric Bradford, Federico Galvanin, Dongda Zhang and Ehecatl Antonio del Rio-Chanona, 2020.

* <[Risk-Constrained Reinforcement Learning with Percentile Risk Criteria](http://www.jmlr.org/papers/volume18/15-636/15-636.pdf)> by Yinlam Chow, Mohammad Ghavamzadeh, Lucas Janson and Marco Pavone, 2015.

## Inverse Learning Of Constraints

* <[Inverse Constrained Reinforcement Learning](https://arxiv.org/pdf/2011.09999.pdf)> by Usman Anwar, Shehryar Malik, Alireza Aghasi and Ali Ahmed, 2021.

* <[Learning Parametric Constraints in High Dimensions from Demonstrations](http://proceedings.mlr.press/v100/chou20a/chou20a.pdf)> by Glen Chou, Necmiye Ozay and Dmitry Berenson, 2020.

* <[Approaches to Safety in Inverse Reinforcement Learning](https://escholarship.org/content/qt6j34r5tp/qt6j34r5tp.pdf)> by Dexter R.R. Scobee, 2020.

* <[Counter-example Guided Learning of Bounds on Environment Behavior](https://arxiv.org/pdf/2001.07233)> by Yuxiao Chen, Sumanth Dathathri, Tung Phan-Minh and Richard M. Murray, 2020.

* <[Inferring Task Goals and Constraints using Bayesian Nonparametric Inverse Reinforcement Learning](http://proceedings.mlr.press/v100/park20a/park20a.pdf)> by Daehyung Park, Michael Noseworthy, Rohan Paul, Subhro Roy and Nicholas Roy, 2020.

* <[Maximum Likelihood Constraint Inference for Inverse Reinforcement Learning](https://arxiv.org/pdf/1909.05477)> by Dexter R.R. Scobee and S. Shankar Sastry, 2019.

* <[Learning Constraints from Demonstrations](https://arxiv.org/pdf/1812.07084)> by Glen Chou, Dmitry Berenson and Necmiye Ozay, 2018.

* <[Interpretable Multi-Objective Reinforcement Learning through Policy Orchestration](https://arxiv.org/pdf/1809.08343)> by Ritesh Noothigattu, Djallel Bouneffouf, Nicholas Mattei, Rachita Chandra, Piyush Madan, Kush Varshney, Murray Campbell, Moninder Singh and Francesca Rossi, 2018.

* <[Modeling Supervisor Safe Sets for Improving Collaboration in Human-robot Teams](https://arxiv.org/pdf/1805.03328)> by David L. McPherson, Dexter R.R. Scobee, Joseph Menke, Allen Y. Yang and S. Shankar Sastry, 2018.

* <[Learning Safe Policies with Expert Guidance](https://papers.nips.cc/paper/8124-learning-safe-policies-with-expert-guidance.pdf)> by Jessie Huang, Fa Wu, Doina Precup and Yang Cai, 2018.

* <[Inferring Geometric Constraints in Human Demonstrations](https://arxiv.org/pdf/1810.00140)> by Guru Subramani, Michael Zinn and Michael Gleicher, 2018.

* <[Learning Task Specifications from Demonstrations](https://papers.nips.cc/paper/7782-learning-task-specifications-from-demonstrations.pdf)> by Marcell Vazquez-Chanlatte, Susmit Jha, Ashish Tiwari, Mark K. Ho and Sanjit A. Seshia, 2018.

* <[C-LEARN: Learning Geometric Constraints from Demonstrations for Multi-step Manipulation in Shared Autonomy](https://dspace.mit.edu/bitstream/handle/1721.1/116016/ICRA17_DArpino_CLEARN.pdf?sequence=1&isAllowed=y)> by Claudia P´erez-D’Arpino and Julie A. Shah, 2017.

## Imitation Learning Under Extra Constraints (Shaping Reward)

* <[Deep Inverse Q-learning with Constraints](https://arxiv.org/pdf/2008.01712)> by Gabriel Kalweit, Maria Huegle, Moritz Werling and Joschka Boedecker, 2020.

* <[Simulating Emergent Properties of Human Driving Behavior Using Multi-agent Reward Augmented Imitation Learning](https://arxiv.org/pdf/1903.05766)> by Raunak P. Bhattacharyya, Derek J. Phillips, Changliu Liu, Jayesh K. Gupta, Katherine Driggs-Campbell and Mykel J. Kochenderfer, 2019.

* <[Infogail: Interpretable Imitation Learning from Visual Demonstrations](http://papers.nips.cc/paper/6971-infogail-interpretable-imitation-learning-from-visual-demonstrations.pdf)> by Yunzhu Li, Jiaming Song and Stefano Ermon, 2017.

* <[Imitation Learning with Demonstrations and Shaping Rewards](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/download/8643/8826)> by Kshitij Judah, Alan Fern, Prasad Tadepalli and Robby Goetschalckx, 2014.

* <[Imitation Learning with a Value-based Prior](https://arxiv.org/pdf/1206.5290)> by Umar Syed and Robert E. Schapire, 2012.

* <[Reinforcement Learning from Simultaneous Human and MDP Reward](http://www.cs.utexas.edu/users/pstone/Papers/bib2html-links/AAMAS12-knox.pdf)> by W. Bradley Knox and Peter Stone, 2012.
