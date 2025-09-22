# Papers Related to UAVs Scheduling

## [Description](#description)
UAVs: Unmanned Aerial Vehicles

This repository is an up-to-date list of significant papers related to UAV scheduling. It covers the integration of scheduling with four other domains : three-dimensional path planning, multi-agent systems, multimodal learning and large language model.

Contributed by Peng Liang, Beibei Liu, and Jingwei Wang.

## [Table of Content](#content)

<table>
<tr><td colspan="2"><a href="#review-articles">1. Review Articles</a></td></tr> 
<tr><td colspan="2"><a href="#three-dimensional-path-planning">2. 3D path planning</a></td></tr>
<tr>
    <td>&ensp;<a href="#basic-models">2.1 Basic Models</a></td>
    <td>&ensp;<a href="#graph-types">2.2 Graph Types</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#pooling-methods">2.3 Pooling Methods</a></td>
    <td>&ensp;<a href="#analysis">2.4 Analysis</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#efficiency">2.5 Efficiency</a></td>
    <td>&ensp;<a href="#explainability">2.6 Explainability</a></td>
</tr>
<tr><td colspan="2"><a href="#applications">3. Applications</a></td></tr> 
<tr>
    <td>&ensp;<a href="#smart-cities">3.1 Smart cities</a></td>
    <td>&ensp;<a href="#agriculture">3.2 Agriculture</a></td>
</tr> 
<tr>
    <td>&ensp;<a href="#knowledge-graph">3.3 Delivery</a></td>
    <td>&ensp;<a href="#recommender-systems">3.4 Recommender Systems</a></td>
</tr>


</table>

## [Review articles](#content)
1. **Swarm intelligence algorithms for multiple unmanned aerial vehicles collaboration: a comprehensive review**

   Artificial Intelligence Review, 2023. [paper](https://doi.org/10.1007/s10462-022-10281-7)

    *Jun Tang, Haibin Duan & Songyang Lao* 

1. **Towards the Unmanned Aerial Vehicles (UAVs): A Comprehensive Review**

   Drones, 2022. [paper](https://doi.org/10.3390/drones6060147)

   *Mohsan SAH, Khan MA, Noor F, Ullah I, Alsharif MH*
    
## [Three-dimensional path planning](#content)   

### [Basic Models](#content)
1. **Supervised Neural Networks for the Classification of Structures.** IEEE TNN 1997. [paper](https://ieeexplore.ieee.org/abstract/document/572108)

    *Alessandro Sperduti and Antonina Starita.*

1. **Graphical-Based Learning Environments for Pattern Recognition.** SSPR/SPR 2004. [paper](https://link.springer.com/content/pdf/10.1007%2F978-3-540-27868-9_4.pdf)

    *Franco Scarselli, Ah Chung Tsoi, Marco Gori, Markus Hagenbuchner.*

1. **A new model for learning in graph domains.** IJCNN 2005. [paper](https://www.researchgate.net/profile/Franco_Scarselli/publication/4202380_A_new_model_for_earning_in_raph_domains/links/0c9605188cd580504f000000.pdf)

    *Marco Gori, Gabriele Monfardini, Franco Scarselli.*

1. **Graph Neural Networks for Ranking Web Pages.** WI 2005. [paper](https://www.researchgate.net/profile/Franco_Scarselli/publication/221158677_Graph_Neural_Networks_for_Ranking_Web_Pages/links/0c9605188cd5090ede000000/Graph-Neural-Networks-for-Ranking-Web-Pages.pdf)

    *Franco Scarselli, Sweah Liang Yong, Marco Gori, Markus Hagenbuchner, Ah Chung Tsoi, Marco Maggini.*

1. **Automatic Generation of Complementary Descriptors with Molecular Graph Networks.** J.Chem.Inf.Model. 2005. [paper](https://pubs.acs.org/doi/10.1021/ci049613b)

    *Christian Merkwirth and Thomas Lengauer.*

1. **Neural Network for Graphs: A Contextual Constructive Approach.** IEEE TNN 2009. [paper](https://ieeexplore.ieee.org/abstract/document/4773279)

    *Alessio Micheli.*
    
1. **Spectral Networks and Locally Connected Networks on Graphs.** ICLR 2014. [paper](https://arxiv.org/pdf/1312.6203.pdf)

    *Joan Bruna, Wojciech Zaremba, Arthur Szlam, Yann LeCun.*
    
1. **Deep Convolutional Networks on Graph-Structured Data.** arxiv 2015. [paper](https://arxiv.org/pdf/1506.05163.pdf)

    *Mikael Henaff, Joan Bruna, Yann LeCun.*
    
1. **Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering.** NIPS 2016. [paper](http://papers.nips.cc/paper/6081-convolutional-neural-networks-on-graphs-with-fast-localized-spectral-filtering.pdf)

    *Michaël Defferrard, Xavier Bresson, Pierre Vandergheynst.*

1. **Diffusion-Convolutional Neural Networks.** NIPS 2016. [paper](https://arxiv.org/pdf/1511.02136.pdf)

    *James Atwood, Don Towsley.*
    
1. **Gated Graph Sequence Neural Networks.** ICLR 2016. [paper](https://arxiv.org/pdf/1511.05493.pdf)

    *Yujia Li, Daniel Tarlow, Marc Brockschmidt, Richard Zemel.*
    
1. **Learning Convolutional Neural Networks for Graphs.** ICML 2016. [paper](http://proceedings.mlr.press/v48/niepert16.pdf)

    *Mathias Niepert, Mohamed Ahmed, Konstantin Kutzkov.* 
    
1. **Semantic Object Parsing with Graph LSTM.** ECCV 2016. [paper](https://link.springer.com/content/pdf/10.1007%2F978-3-319-46448-0_8.pdf)

    *Xiaodan Liang, Xiaohui Shen, Jiashi Feng, Liang Lin, Shuicheng Yan.*
    
1. **Semi-Supervised Classification with Graph Convolutional Networks.** ICLR 2017. [paper](https://arxiv.org/pdf/1609.02907.pdf)

    *Thomas N. Kipf, Max Welling.*
    
1. **Inductive Representation Learning on Large Graphs.** NIPS 2017. [paper](https://arxiv.org/pdf/1706.02216.pdf)

    *William L. Hamilton, Rex Ying, Jure Leskovec.*
    
1. **Geometric deep learning on graphs and manifolds using mixture model cnns.** CVPR 2017. [paper](https://arxiv.org/pdf/1611.08402.pdf)

    *Federico Monti, Davide Boscaini, Jonathan Masci, Emanuele Rodolà, Jan Svoboda, Michael M. Bronstein.*
    
1. **Graph Attention Networks.** ICLR 2018. [paper](https://mila.quebec/wp-content/uploads/2018/07/d1ac95b60310f43bb5a0b8024522fbe08fb2a482.pdf)

    *Petar Velickovic, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Lio, Yoshua Bengio.*

1. **Covariant Compositional Networks For Learning Graphs.** ICLR 2018. [paper](https://arxiv.org/pdf/1801.02144.pdf)

    *Risi Kondor, Hy Truong Son, Horace Pan, Brandon Anderson, Shubhendu Trivedi.*

1. **Graph Partition Neural Networks for Semi-Supervised Classification.** ICLR 2018. [paper](https://arxiv.org/pdf/1803.06272.pdf)

    *Renjie Liao, Marc Brockschmidt, Daniel Tarlow, Alexander L. Gaunt, Raquel Urtasun, Richard Zemel.*
    
1. **Inference in Probabilistic Graphical Models by Graph Neural Networks.** ICLR Workshop 2018. [paper](https://arxiv.org/pdf/1803.07710.pdf)

    *KiJung Yoon, Renjie Liao, Yuwen Xiong, Lisa Zhang, Ethan Fetaya, Raquel Urtasun, Richard Zemel, Xaq Pitkow.*

1. **Structure-Aware Convolutional Neural Networks.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7287-structure-aware-convolutional-neural-networks.pdf)

    *Jianlong Chang, Jie Gu, Lingfeng Wang, Gaofeng Meng, Shiming Xiang, Chunhong Pan.*
    

<details><summary> more </summary> 

21. **Bayesian Semi-supervised Learning with Graph Gaussian Processes.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1809.04379)

    *Yin Cheng Ng, Nicolò Colombo, Ricardo Silva.*

22. **Adaptive Graph Convolutional Neural Networks.** AAAI 2018. [paper](https://arxiv.org/pdf/1801.03226.pdf)

    *Ruoyu Li, Sheng Wang, Feiyun Zhu, Junzhou Huang.*  

1. **Dual Graph Convolutional Networks for Graph-Based Semi-Supervised Classification.** WWW 2018. [paper](http://delivery.acm.org/10.1145/3190000/3186116/p499-zhuang.pdf?ip=123.134.247.159&id=3186116&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1564108433_6b20d1fe2ab710632bc8434ad3a00bc8)

    *Chenyi Zhuang, Qiang Ma.*

1. **Learning Steady-States of Iterative Algorithms over Graphs.** ICML 2018. [paper](http://proceedings.mlr.press/v80/dai18a/dai18a.pdf)

    *Hanjun Dai, Zornitsa Kozareva, Bo Dai, Alex Smola, Le Song.*

1. **Graph Capsule Convolutional Neural Networks.** ICML 2018 Workshop. [paper](https://arxiv.org/pdf/1805.08090.pdf)

    *Saurabh Verma, Zhi-Li Zhang.*
    
1. **Capsule Graph Neural Network.** ICLR 2019. [paper](https://openreview.net/pdf?id=Byl8BnRcYm)

    *Zhang Xinyi, Lihui Chen.*
    
1. **Graph Wavelet Neural Network.** ICLR 2019. [paper](https://openreview.net/pdf?id=H1ewdiR5tQ)

    *Bingbing Xu, Huawei Shen, Qi Cao, Yunqi Qiu, Xueqi Cheng.*

1. **Deep Graph Infomax.** ICLR 2019. [paper](https://openreview.net/pdf?id=rklz9iAcKQ)

    *Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm.*
    
1. **Predict then Propagate: Graph Neural Networks meet Personalized PageRank.** ICLR 2019. [paper](https://openreview.net/pdf?id=H1gL-2A9Ym)

    *Johannes Klicpera, Aleksandar Bojchevski, Stephan Günnemann.*

1. **LanczosNet: Multi-Scale Deep Graph Convolutional Networks.** ICLR 2019. [paper](https://openreview.net/pdf?id=BkedznAqKQ)

    *Renjie Liao, Zhizhen Zhao, Raquel Urtasun, Richard Zemel.*

1. **Invariant and Equivariant Graph Networks.** ICLR 2019. [paper](https://openreview.net/pdf?id=Syx72jC9tm)

    *Haggai Maron, Heli Ben-Hamu, Nadav Shamir, Yaron Lipman.*

1. **GMNN: Graph Markov Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1905.06214)

    *Meng Qu, Yoshua Bengio, Jian Tang.*
    
1. **Position-aware Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1906.04817)

    *Jiaxuan You, Rex Ying, Jure Leskovec.*

1. **Disentangled Graph Convolutional Networks.** ICML 2019. [paper](http://proceedings.mlr.press/v97/ma19a/ma19a.pdf)

    *Jianxin Ma, Peng Cui, Kun Kuang, Xin Wang, Wenwu Zhu.*
    
1. **Stochastic Blockmodels meet Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1905.05738)

    *Nikhil Mehta, Lawrence Carin, Piyush Rai.*

1. **Learning Discrete Structures for Graph Neural Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1903.11960)

    *Luca Franceschi, Mathias Niepert, Massimiliano Pontil, Xiao He.*

1. **MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing.** ICML 2019. [paper](https://arxiv.org/pdf/1905.00067)

    *Sami Abu-El-Haija, Bryan Perozzi, Amol Kapoor, Nazanin Alipourfard, Kristina Lerman, Hrayr Harutyunyan, Greg Ver Steeg, Aram Galstyan.*

1. **DEMO-Net: Degree-specific Graph Neural Networks for Node and Graph Classification.** KDD 2019. [paper](https://arxiv.org/pdf/1906.02319.pdf)

    *Jun Wu, Jingrui He, Jiejun Xu.*

1. **Graph Representation Learning via Hard and Channel-Wise Attention Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1907.04652)

    *Hongyang Gao, Shuiwang Ji.*
    
1. **Graph Learning-Convolutional Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1811.09971.pdf)

    *Bo Jiang, Ziyan Zhang, Doudou Lin, Jin Tang.*

1. **Data Representation and Learning with Graph Diffusion-Embedding Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Jiang_Data_Representation_and_Learning_With_Graph_Diffusion-Embedding_Networks_CVPR_2019_paper.pdf)

    *Bo Jiang, Doudou Lin, Jin Tang, Bin Luo.*
    
1. **Label Efficient Semi-Supervised Learning via Graph Filtering.** CVPR 2019. [paper](https://arxiv.org/pdf/1901.09993.pdf)

    *Qimai Li, Xiao-Ming Wu, Han Liu, Xiaotong Zhang, Zhichao Guan.*
    
1. **SPAGAN: Shortest Path Graph Attention Network.** IJCAI 2019. [paper](https://cse.buffalo.edu/~jsyuan/papers/2019/SPAGAN_Shortest_Path_Graph_Attention_Network.pdf)

    *Yiding Yang, Xinchao Wang, Mingli Song, Junsong Yuan, Dacheng Tao.*
    
1. **Topology Optimization based Graph Convolutional Network.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_to.pdf)

    *Liang Yang, Zesheng Kang, Xiaochun Cao, Di Jin, Bo Yang, Yuanfang Guo.*
    
1. **Hierarchical Graph Convolutional Networks for Semi-supervised Node Classification.** IJCAI 2019. [paper](https://arxiv.org/pdf/1902.06667.pdf)

    *Fenyu Hu, Yanqiao Zhu, Shu Wu, Liang Wang, Tieniu Tan.*
    
1. **Masked Graph Convolutional Network.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_mask.pdf)

    *Liang Yang, Fan Wu, Yingkui Wang, Junhua Gu, Yuanfang Guo.*
    
1. **Dual Self-Paced Graph Convolutional Network: Towards Reducing Attribute Distortions Induced by Topology.** IJCAI 2019. [paper](https://yangliang.github.io/pdf/ijcai19_paced.pdf)

    *Liang Yang, Zhiyang Chen, Junhua Gu, Yuanfang Guo.* 

1. **Bayesian graph convolutional neural networks for semi-supervised classification.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.11103.pdf)

    *Yingxue Zhang, Soumyasundar Pal, Mark Coates, Deniz Üstebay.*
    
1. **GeniePath: Graph Neural Networks with Adaptive Receptive Paths.** AAAI 2019. [paper](https://arxiv.org/pdf/1802.00910.pdf)

    *Ziqi Liu, Chaochao Chen, Longfei Li, Jun Zhou, Xiaolong Li, Le Song, Yuan Qi.*
    
1. **Gaussian-Induced Convolution for Graphs.** AAAI 2019. [paper](https://arxiv.org/pdf/1811.04393.pdf)

    *Jiatao Jiang, Zhen Cui, Chunyan Xu, Jian Yang.*
    
1. **Fisher-Bures Adversary Graph Convolutional Networks.** UAI 2019. [paper](https://arxiv.org/pdf/1903.04154.pdf)

    *Ke Sun, Piotr Koniusz, Zhen Wang.*
    
1. **N-GCN: Multi-scale Graph Convolution for Semi-supervised Node Classification.** UAI 2019. [paper](https://arxiv.org/pdf/1802.08888.pdf)

    *Sami Abu-El-Haija, Amol Kapoor, Bryan Perozzi, Joonseok Lee.*
    
1. **Confidence-based Graph Convolutional Networks for Semi-Supervised Learning.** AISTATS 2019. [paper](https://arxiv.org/pdf/1901.08255.pdf)

    *Shikhar Vashishth, Prateek Yadav, Manik Bhandari, Partha Talukdar.*
    
1. **Lovasz Convolutional Networks.** AISTATS 2019. [paper](https://arxiv.org/pdf/1805.11365.pdf)

    *Prateek Yadav, Madhav Nimishakavi, Naganand Yadati, Shikhar Vashishth, Arun Rajkumar, Partha Talukdar.* 

1. **Provably Powerful Graph Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-1275)

    *Haggai Maron, Heli Ben-Hamu, Hadar Serviansky, Yaron Lipman.*

1. **Graph Agreement Models for Semi-Supervised Learning.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-4699)

	*Otilia Stretcu, Krishnamurthy Viswanathan, Dana Movshovitz-Attias, Emmanouil Platanios. Sujith Ravi, Andrew Tomkins.*

1. **Graph-Based Semi-Supervised Learning with Non-ignorable Non-response.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-3795)

	*Fan Zhou, Tengfei Li, Haibo Zhou, Hongtu Zhu, Ye Jieping.*

1. **A Flexible Generative Framework for Graph-based Semi-supervised Learning.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-1831)

	*Jiaqi Ma, Weijing Tang, Ji Zhu, Qiaozhu Mei.*

1. **Semi-Implicit Graph Variational Auto-Encoders.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-5716)

	*Arman Hasanzadeh, Ehsan Hajiramezanali, Krishna Narayanan, Nick Duffield, Mingyuan Zhou, Xiaoning Qian.*

1. **Hyperbolic Graph Neural Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-4472)

	*Qi Liu, Maximilian Nickel, Douwe Kiela.*

1. **Hyperbolic Graph Convolutional Neural Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-2699)

	*Ines Chami, Zhitao Ying, Christopher Ré, Jure Leskovec.*

1. **Graph Neural Tangent Kernel: Fusing Graph Neural Networks with Graph Kernels.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-3077)

	*Simon Du, Kangcheng Hou, Russ Salakhutdinov, Barnabas Poczos, Ruosong Wang, Keyulu Xu.*

1. **SNEQ: Semi-supervised Attributed Network Embedding with Attention-based Quantisation.** AAAI 2020. [paper](http://users.monash.edu/~yli/assets/pdf/sneq-aaai-20.pdf)

	*Tao He, Lianli Gao, Jingkuan Song, Xin Wang, Kejie Huang, Yuan-­‐Fang Li.*

1. **Going Deep: Graph Convolutional Ladder-Shape Networks.** AAAI 2020. [paper](https://shiruipan.github.io/publication/aaai-2020-hu/)

	*Ruiqi Hu, Shirui Pan, Guodong Long, Qinghua Lu, Liming Zhu, Jing Jiang.*

1. **Co-GCN for Multi-View Semi-Supervised Learning.** AAAI 2020. [paper]()

	*Shu Li, Wen-­‐Tao Li, Wei Wang.*

1. **Graph Representation Learning via Ladder Gamma Variational Autoencoders.** AAAI 2020. [paper]()

	*Arindam Sarkar, Nikhil Mehta, Piyush Rai.*

1. **GSSNN: Graph Smoothing Splines Neural Networks.** AAAI 2020. [paper](https://shiruipan.github.io/publication/aaai-2020-zhu/)

	*Shichao Zhu, Lewei Zhou, Shirui Pan, Chuan Zhou, Guiying Yan, Bin Wang.*

1. **Effective Decoding in Graph Auto-Encoder using Triadic Closure.** AAAI 2020. [paper](https://arxiv.org/abs/1911.11322)

	*Han Shi, Haozheng Fan, James T. Kwok.*

1. **An Attention-based Graph Neural Network for Heterogeneous Structural Learning.** AAAI 2020. [paper](https://arxiv.org/abs/1912.10832)

	*Huiting Hong, Hantao Guo, Yucheng Lin, Xiaoqing Yang, Zang Li, Jieping Ye.*

1. **Fast and Deep Graph Neural Networks.** AAAI 2020. [paper](https://arxiv.org/abs/1911.08941)

	*Claudio Gallicchio, Alessio Micheli.*

1. **Hypergraph Label Propagation Network.** AAAI 2020. [paper]()

	*Yubo Zhang, Nan Wang, Yufeng Chen, Changqing Zou, Hai Wan, Xibin Zhao, Yue Gao.*

1. **Learning Signed Network Embedding via Graph Attention.** AAAI 2020. [paper]()

	*Yu Li, Yuan Tian, Jiawei Zhang, Yi Chang.*

1. **GraLSP: Graph Neural Networks with Local Structural Patterns.** AAAI 2020. [paper](https://arxiv.org/abs/1911.07675)

	*Yilun Jin, Guojie Song, Chuan Shi.*

1. **ASAP: Adaptive Structure Aware Pooling for Learning Hierarchical Graph Representations.** AAAI 2020. [paper](https://arxiv.org/abs/1911.07979)

	*Ekagra Ranjan, Soumya Sanyal, Partha Pratim Talukdar.*

1. **Multi‐Stage Self­‐Supervised Learning for Graph Convolutional Networks on Graphs with Few Labeled Nodes.** AAAI 2020. [paper](https://zhouchenlin.github.io/Publications/2020-AAAI-M3S.pdf)

	*Ke Sun, Zhouchen Lin, Zhanxing Zhu.*

1. **Collaborative Graph Convolutional Networks: Unsupervised Learning Meets Semi-­‐Supervised Learning.** AAAI 2020. [paper]()

	*Binyuan Hui,  Pengfei Zhu, Qinghua, Hu.*

1. **A Multi­‐Scale Approach for Graph Link Prediction.** AAAI 2020. [paper]()

	*Lei Cai, Shuiwang Ji.*

1. **Adaptive Structural Fingerprints for Graph Attention Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=BJxWx0NYPr)

	*Kai Zhang, Yaokang Zhu, Jun Wang, Jie Zhang.*

1. **Strategies for Pre-training Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=HJlWWJSFDH)

	*Weihua Hu, Bowen Liu, Joseph Gomes, Marinka Zitnik, Percy Liang, Vijay Pande, Jure Leskovec.*

1. **DropEdge: Towards Deep Graph Convolutional Networks on Node Classification.** ICLR 2020. [paper](https://openreview.net/pdf?id=Hkx1qkrKPr)

	*Yu Rong, Wenbing Huang, Tingyang Xu, Junzhou Huang.*

1. **Directional Message Passing for Molecular Graphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=B1eWbxStPH)

	*Johannes Klicpera, Janek Groß, Stephan Günnemann.*

1. **DeepSphere: a graph-based spherical CNN.** ICLR 2020. [paper](https://openreview.net/pdf?id=B1e3OlStPB)

	*Michaël Defferrard, Martino Milani, Frédérick Gusset, Nathanaël Perraudin.*

1. **Geom-GCN: Geometric Graph Convolutional Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=S1e2agrFvS)

	*Hongbin Pei, Bingzhe Wei, Kevin Chen-Chuan Chang, Yu Lei, Bo Yang.*

1. **Curvature Graph Network.** ICLR 2020. [paper](https://openreview.net/pdf?id=BylEqnVFDB)

	*Ze Ye, Kin Sum Liu, Tengfei Ma, Jie Gao, Chao Chen.*

1. **Measuring and Improving the Use of Graph Information in Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=rkeIIkHKvS)

	*Yifan Hou, Jian Zhang, James Cheng, Kaili Ma, Richard T. B. Ma, Hongzhi Chen, Ming-Chang Yang.*

1. **Memory-Based Graph Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=r1laNeBYPB)

	*Amir Hosein Khasahmadi, Kaveh Hassani, Parsa Moradi, Leo Lee, Quaid Morris.*

1. **Pruned Graph Scattering Transforms.** ICLR 2020. [paper](https://openreview.net/pdf?id=rJeg7TEYwB)

	*Vassilis N. Ioannidis, Siheng Chen, Georgios B. Giannakis.*

1. **Neural Execution of Graph Algorithms.** ICLR 2020. [paper](https://openreview.net/pdf?id=SkgKO0EtvS)

	*Petar Veličković, Rex Ying, Matilde Padovano, Raia Hadsell, Charles Blundell.*

1. **GraphSAINT: Graph Sampling Based Inductive Learning Method.** ICLR 2020. [paper](https://openreview.net/pdf?id=BJe8pkHFwS)

	*Hanqing Zeng, Hongkuan Zhou, Ajitesh Srivastava, Rajgopal Kannan, Viktor Prasanna.*

1. **Graph inference learning for semi-supervised classification.** ICLR 2020. [paper](https://openreview.net/pdf?id=r1evOhEKvH)

	*Chunyan Xu, Zhen Cui, Xiaobin Hong, Tong Zhang, Jian Yang, Wei Liu.*

1. **SGAS: Sequential Greedy Architecture Search.** CVPR 2020. [paper](https://arxiv.org/abs/1912.00195)

	*Guohao Li, Guocheng Qian, Itzel C. Delgadillo, Matthias Müller, Ali Thabet, Bernard Ghanem.*

1. **Adaptive Propagation Graph Convolutional Network.** IEEE TNNLS 2020. [paper](https://ieeexplore.ieee.org/document/9206045)

	*Indro Spinelli, Simone Scardapane, Aurelio Uncini.*

     </details>

### [Graph Types](#content)
1. **DyRep: Learning Representations over Dynamic Graphs.** ICLR 2019. [paper](https://openreview.net/pdf?id=HyePrhR5KX)

    *Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha.*

1. **Hypergraph Neural Networks.** AAAI 2019. [paper](https://arxiv.org/pdf/1809.09401.pdf)

    *Yifan Feng, Haoxuan You, Zizhao Zhang, Rongrong Ji, Yue Gao.*

1. **Heterogeneous Graph Attention Network.** WWW 2019. [paper](https://arxiv.org/pdf/1903.07293.pdf)

    *Xiao Wang, Houye Ji, Chuan Shi, Bai Wang, Peng Cui, P. Yu, Yanfang Ye.*
    
1. **Representation Learning for Attributed Multiplex Heterogeneous Network.** KDD 2019. [paper](https://arxiv.org/pdf/1905.01669.pdf)

    *Yukuo Cen, Xu Zou, Jianwei Zhang, Hongxia Yang, Jingren Zhou, Jie Tang.*
    
1. **ActiveHNE: Active Heterogeneous Network Embedding.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.05659.pdf)
   
    *Xia Chen, Guoxian Yu, Jun Wang, Carlotta Domeniconi, Zhao Li, Xiangliang Zhang.*
    
1. **GCN-LASE: Towards Adequately Incorporating Link Attributes in Graph Convolutional Networks.** IJCAI 2019. [paper](https://arxiv.org/pdf/1902.09817.pdf)

    *Ziyao Li, Liang Zhang, Guojie Song.*
    
1. **Dynamic Hypergraph Neural Networks.** IJCAI 2019. [paper](https://www.ijcai.org/proceedings/2019/0366.pdf)

    *Jianwen Jiang, Yuxuan Wei, Yifan Feng, Jingxuan Cao, Yue Gao.*
    
1. **Exploiting Interaction Links for Node Classification with Deep Graph Neural Networks.** IJCAI 2019. [paper](https://www.ijcai.org/proceedings/2019/0447.pdf)

    *Hogun Park, Jennifer Neville.*
    
1. **Exploiting Edge Features in Graph Neural Networks.** CVPR 2019. [paper](https://arxiv.org/pdf/1809.02709.pdf)

    *Liyu Gong, Qiang Cheng.*  

1. **HyperGCN: A New Method For Training Graph Convolutional Networks on Hypergraphs.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-850)

	*Naganand Yadati, Madhav Nimishakavi, Prateek Yadav, Vikram Nitin, Anand Louis, Partha Talukdar.*

1. **Graph Transformer Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-6458)

	*Seongjun Yun, Minbyul Jeong, Raehyun Kim, Jaewoo Kang, Hyunwoo Kim.*

1. **Recurrent Space-time Graph Neural Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-6993)

	*Andrei Nicolicioiu, Iulia Duta, Marius Leordeanu.*

1. **EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs.** AAAI 2020. [paper](https://arxiv.org/abs/1902.10191)

	*Aldo Pareja, Giacomo Domeniconi, Jie Chen, Tengfei Ma, Toyotaro Suzumura, Hiroki Kanezashi, Tim Kaler, Tao B. Schardl, Charles E. Leiserson.*

1. **Spatial-Temporal Synchronous Graph Convolutional Networks: A New Framework for Spatial-Temporal Network Data Forecasting.** AAAI 2020. [paper](https://github.com/Davidham3/STSGCN/blob/master/paper/AAAI2020-STSGCN.pdf)

	*Chao Song, Youfang Lin, Shengnan Guo, Huaiyu Wan.*

1. **Type-aware Anchor Link Prediction across Heterogeneous Networks based on Graph Attention Network.** AAAI 2020. [paper]()

	*Xiaoxue Li, Yanmin Shang, Yanan Cao, Yangxi Li, Jianlong Tan, Yanbing Liu.*    

1. **Composition-based Multi-Relational Graph Convolutional Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=BylA_C4tPr)

	*Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Partha Talukdar.*

1. **Inductive representation learning on temporal graphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=rJeW1yHYwH)

	*da Xu, chuanwei ruan, evren korpeoglu, sushant kumar, kannan achan.*

1. **Hyper-SAGNN: a self-attention based graph neural network for hypergraphs.** ICLR 2020. [paper](https://openreview.net/pdf?id=ryeHuJBtPH)

	*Ruochi Zhang, Yuesong Zou, Jian Ma.*

1. **Digraph Inception Convolutional Networks.** NeurIPS 2020. [paper](https://proceedings.neurips.cc//paper/2020/file/cffb6e2288a630c2a787a64ccc67097c-Paper.pdf)

	*Zekun Tong, Yuxuan Liang, Changsheng Sun, Xinke Li, David S. Rosenblum, Andrew Lim.*

1. **Subgraph Neural Networks.** NeurIPS 2020. [paper](https://papers.nips.cc/paper/2020/hash/5bca8566db79f3788be9efd96c9ed70d-Abstract.html)

    *Emily Alsentzer, Samuel Finlayson, Michelle Li, Marinka Zitnik.*
    
1. **Dynamic Graph Convolutional Networks Using the Tensor M-Product.** SDM 2021. [paper](https://doi.org/10.1137/1.9781611976700.82)

    *Osman Asif Malik, Shashanka Ubaru, Lior Horesh, Misha E. Kilmer, Haim Avron*

### [Pooling Methods](#content)
1. **An End-to-End Deep Learning Architecture for Graph Classification.** AAAI 2018. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17146/16755)

    *Muhan Zhang, Zhicheng Cui, Marion Neumann, Yixin Chen.*

1. **Hierarchical Graph Representation Learning with Differentiable Pooling.** NeurIPS 2018. [paper](https://papers.nips.cc/paper/7729-hierarchical-graph-representation-learning-with-differentiable-pooling.pdf)

    *Zhitao Ying, Jiaxuan You, Christopher Morris, Xiang Ren, Will Hamilton, Jure Leskovec.*

1. **Self-Attention Graph Pooling.** ICML 2019. [paper](https://arxiv.org/pdf/1904.08082)

    *Junhyun Lee, Inyeop Lee, Jaewoo Kang.*

1. **Graph U-Nets.** ICML 2019. [paper](http://proceedings.mlr.press/v97/gao19a/gao19a.pdf)

    *Hongyang Gao, Shuiwang Ji.*
    
1. **Graph Convolutional Networks with EigenPooling.** KDD 2019. [paper](https://arxiv.org/pdf/1904.13107.pdf)

    *Yao Ma, Suhang Wang, Charu C. Aggarwal, Jiliang Tang.*
    
1. **Relational Pooling for Graph Representations.** ICML 2019. [paper](https://arxiv.org/pdf/1903.02541)

    *Ryan L. Murphy, Balasubramaniam Srinivasan, Vinayak Rao, Bruno Ribeiro.*

1. **Break the Ceiling: Stronger Multi-scale Deep Graph Convolutional Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-5861)

	*Sitao Luan, Mingde Zhao, Xiao-Wen Chang, Doina Precup.*

1. **Diffusion Improves Graph Learning.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/9490-diffusion-improves-graph-learning)

	*Johannes Klicpera, Stefan Weißenberger, Stephan Günnemann.*

1. **Hierarchical Graph Pooling with Structure Learning.** AAAI 2020. [paper](https://arxiv.org/abs/1911.05954)

	*Zhen Zhang, Jiajun Bu, Martin Ester, Jianfeng Zhang, Chengwei Yao, Zhi Yu, Can Wang.*

1. **StructPool: Structured Graph Pooling via Conditional Random Fields.** ICLR 2020. [paper](https://openreview.net/pdf?id=BJxg_hVtwH)

	*Hao Yuan, Shuiwang Ji.*

1. **Spectral Clustering with Graph Neural Networks for Graph Pooling.** ICML 2020. [paper](https://arxiv.org/abs/1907.00481)

	*Filippo Maria Bianchi, Daniele Grattarola, Cesare Alippi.*

1. **Accurate Learning of Graph Representations with Graph Multiset Pooling.** ICLR 2021. [paper](https://openreview.net/pdf?id=JHcqXGaqiGn)

	*Jinheon Baek, Minki Kang, Sung Ju Hwang.*

### [Analysis](#content)
1. **A Comparison between Recursive Neural Networks and Graph Neural Networks.** IJCNN 2006. [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1716174)

    *Vincenzo Di Massa, Gabriele Monfardini, Lorenzo Sarti, Franco Scarselli, Marco Maggini, Marco Gori.*
    
1. **Neural networks for relational learning: an experimental comparison.** Machine Learning 2011. [paper](https://link.springer.com/content/pdf/10.1007%2Fs10994-010-5196-5.pdf)

    *Werner Uwents, Gabriele Monfardini, Hendrik Blockeel, Marco Gori, Franco Scarselli.*
    
1. **Mean-field theory of graph neural networks in graph partitioning.** NeurIPS 2018. [paper](http://papers.nips.cc/paper/7689-mean-field-theory-of-graph-neural-networks-in-graph-partitioning.pdf)

    *Tatsuro Kawamoto, Masashi Tsubaki, Tomoyuki Obuchi.*

1. **Representation Learning on Graphs with Jumping Knowledge Networks.** ICML 2018. [paper](https://arxiv.org/pdf/1806.03536.pdf)

    *Keyulu Xu, Chengtao Li, Yonglong Tian, Tomohiro Sonobe, Ken-ichi Kawarabayashi, Stefanie Jegelka.* 
    
1. **Deeper Insights into Graph Convolutional Networks for Semi-Supervised Learning.** AAAI 2018. [paper](https://arxiv.org/pdf/1801.07606.pdf)
   
    *Qimai Li, Zhichao Han, Xiao-Ming Wu.*

1. **How Powerful are Graph Neural Networks?** ICLR 2019. [paper](https://openreview.net/pdf?id=ryGs6iA5Km)

    *Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka.*

1. **Stability and Generalization of Graph Convolutional Neural Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1905.01004.pdf)

    *Saurabh Verma, Zhi-Li Zhang.*

1. **Simplifying Graph Convolutional Networks.** ICML 2019. [paper](https://arxiv.org/pdf/1902.07153)

    *Felix Wu, Tianyi Zhang, Amauri Holanda de Souza Jr., Christopher Fifty, Tao Yu, Kilian Q. Weinberger.*

1. **Explainability Methods for Graph Convolutional Neural Networks.** CVPR 2019. [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pope_Explainability_Methods_for_Graph_Convolutional_Neural_Networks_CVPR_2019_paper.pdf)

    *Phillip E. Pope, Soheil Kolouri, Mohammad Rostami, Charles E. Martin, Heiko Hoffmann.*

1. **Can GCNs Go as Deep as CNNs?** ICCV 2019. [paper](https://arxiv.org/pdf/1904.03751.pdf)

    *Guohao Li, Matthias Müller, Ali Thabet, Bernard Ghanem.*

1. **Weisfeiler and Leman Go Neural: Higher-order Graph Neural Networks.** AAAI 2019. [paper](https://arxiv.org/pdf/1810.02244.pdf)    

    *Christopher Morris, Martin Ritzert, Matthias Fey, William L. Hamilton, Jan Eric Lenssen, Gaurav Rattan, Martin Grohe.*

1. **Understanding Attention and Generalization in Graph Neural Networks.** NeurIPS 2019. [paper](https://arxiv.org/pdf/1905.02850.pdf)

    *Boris Knyazev, Graham W. Taylor, Mohamed R. Amer.*

1. **GNNExplainer: Generating Explanations for Graph Neural Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-4956)

	*Zhitao Ying, Dylan Bourgeois, Jiaxuan You, Marinka Zitnik, Jure Leskovec.*

1. **Universal Invariant and Equivariant Graph Neural Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-3832)

	*Nicolas Keriven, Gabriel Peyré.*

1. **On the equivalence between graph isomorphism testing and function approximation with GNNs.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-9347)

	*Zhengdao Chen, Soledad Villar, Lei Chen, Joan Bruna.*

1. **Understanding the Representation Power of Graph Neural Networks in Learning Graph Topology.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-8876)

	*Nima Dehmamy, Albert-Laszlo Barabasi, Rose Yu.*

1. **Graph Neural Networks Exponentially Lose Expressive Power for Node Classification.** ICLR 2020. [paper](https://openreview.net/pdf?id=S1ldO2EFPr)

	*Kenta Oono, Taiji Suzuki.*

1. **What graph neural networks cannot learn: depth vs width.** ICLR 2020. [paper](https://openreview.net/pdf?id=B1l2bp4YwS)

	*Andreas Loukas.*

1. **The Logical Expressiveness of Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=r1lZ7AEKvB)

	*Pablo Barceló, Egor V. Kostylev, Mikael Monet, Jorge Pérez, Juan Reutter, Juan Pablo Silva.*

1. **On the Equivalence between Positional Node Embeddings and Structural Graph Representations.** ICLR 2020. [paper](https://openreview.net/pdf?id=SJxzFySKwH)

	*Balasubramaniam Srinivasan, Bruno Ribeiro.*
	
1. **Can Graph Neural Networks Count Substructures?** NeurIPS 2020. [paper](https://arxiv.org/pdf/2002.04025.pdf)

	*Zhengdao Chen, Lei Chen, Soledad Villar, Joan Bruna.*

### [Efficiency](#content)
1. **Stochastic Training of Graph Convolutional Networks with Variance Reduction.** ICML 2018. [paper](http://www.scipaper.net/uploadfile/2018/0716/20180716100330880.pdf)
   
    *Jianfei Chen, Jun Zhu, Le Song.*
    
1. **FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling.** ICLR 2018. [paper](https://arxiv.org/pdf/1801.10247.pdf)

    *Jie Chen, Tengfei Ma, Cao Xiao.*
    
1. **Adaptive Sampling Towards Fast Graph Representation Learning.** NeurIPS 2018. [paper](https://arxiv.org/pdf/1809.05343.pdf)

    *Wenbing Huang, Tong Zhang, Yu Rong, Junzhou Huang.*
    
1. **Large-Scale Learnable Graph Convolutional Networks.** KDD 2018. [paper](https://arxiv.org/pdf/1808.03965.pdf)

    *Hongyang Gao, Zhengyang Wang, Shuiwang Ji.*
    
1. **Cluster-GCN: An Efficient Algorithm for Training Deep and Large Graph Convolutional Networks.** KDD 2019. [paper](https://arxiv.org/pdf/1905.07953.pdf)

    *Wei-Lin Chiang, Xuanqing Liu, Si Si, Yang Li, Samy Bengio, Cho-Jui Hsieh.*
    
1. **A Degeneracy Framework for Scalable Graph Autoencoders.** IJCAI 2019. [paper](https://arxiv.org/pdf/1902.08813.pdf)

    *Guillaume Salha, Romain Hennequin, Viet Anh Tran, Michalis Vazirgiannis.*

1. **Layer-Dependent Importance Sampling for Training Deep and Large Graph Convolutional Networks.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-6006)

	*Difan Zou, Ziniu Hu, Yewen Wang, Song Jiang, Yizhou Sun, Quanquan Gu.*

1. **GraphSAINT: Graph Sampling Based Inductive Learning Method.** ICLR 2020. [paper](https://arxiv.org/pdf/1907.04931.pdf) [code](https://github.com/GraphSAINT/GraphSAINT)

    *Hanqing Zeng, Hongkuan Zhou, Ajitesh Srivastava, Rajgopal Kannan, Viktor Prasanna.*

1. **Scalable Graph Convolutional Network Based Link Prediction on a Distributed Graph Database Server.** IEEE CLOUD 2020. [paper](https://github.com/miyurud/miyurud.github.io/blob/master/papers/2020/IEEE_CLOUD_2020_JasmineGraph-web.pdf) [code](https://github.com/miyurud/jasminegraph)

    *Anuradha Karunarathna, Dinika Senarath, Shalika Madhushanki, Chinthaka Weerakkody, Miyuru Dayarathna, Sanath Jayasena, Toyotaro Suzumura.*


1. **Memory Efficient Graph Convolutional Networkbased Distributed Link Prediction.** IEEE Big Data 2020. [paper](https://raw.githubusercontent.com/miyurud/miyurud.github.io/master/papers/2020/IEEE_BigData_Workshop_2020_JasmineGraph_web.pdf) [code](https://github.com/miyurud/jasminegraph)

    *Damitha Senevirathne, Isuru Wijesiri, Suchitha Dehigaspitiya, Miyuru Dayarathna, Sanath Jayasena, and Toyotaro Suzumura.*


### [Explainability](#content)

1. **Explainability Techniques for Graph Convolutional Networks.** ICML 2019. [paper](https://arxiv.org/abs/1905.13686)

    *Federico Baldassarre, Hossein Azizpour.*

1. **GNNExplainer: Generating Explanations for Graph Neural Networks.** NeurIPS 2019. [paper](https://arxiv.org/abs/1903.03894)

	*Rex Ying, Dylan Bourgeois, Jiaxuan You, Marinka Zitnik, Jure Leskovec.*

1. **GCN-LRP Explanation: Exploring Latent Attention of Graph Convolutional Networks.** IJCNN 2020. [paper](https://ieeexplore.ieee.org/document/9207639)

    *Jinlong Hu, Tenghui Li, Shoubin Dong.*

1. **Parameterized Explainer for Graph Neural Network.** NeurIPS 2020. [paper](https://arxiv.org/abs/2011.04573)

	*Dongsheng Luo, Wei Cheng, Dongkuan Xu, Wenchao Yu, Bo Zong, Haifeng Chen, Xiang Zhang.*

1. **XGNN: Towards Model-Level Explanations of Graph Neural Networks.** KDD 2020. [paper](https://arxiv.org/abs/2006.02587)

	*Hao Yuan, Jiliang Tang, Xia Hu, Shuiwang Ji.*

1. **Contrastive Graph Neural Network Explanation.** ICML 2020. [paper](https://arxiv.org/abs/2010.13663)

	*Lukas Faber, Amin K. Moghaddam, Roger Wattenhofer.*

1. **Interpreting Graph Neural Networks for NLP With Differentiable Edge Maskin.** ICLR 2021. [paper](https://arxiv.org/abs/2010.00577)

	*Michael Sejr Schlichtkrull, Nicola De Cao, Ivan Titov.*

1. **On Explainability of Graph Neural Networks via Subgraph Explorations.** ICML 2021. [paper](https://arxiv.org/abs/2102.05152)

	*Hao Yuan, Haiyang Yu, Jie Wang, Kang Li, Shuiwang Ji.*

1. **Generative Causal Explanations for Graph Neural Networks.** ICML 2021. [paper](https://arxiv.org/abs/2104.06643)

	*Wanyu Lin, Hao Lan, Baochun Li.*

1. **GraphSVX: Shapley Value Explanations for Graph Neural Networks.** ECML PKDD 2021. [paper](https://arxiv.org/abs/2104.10482)

	*Alexandre Duval, Fragkiskos D. Malliaros.*


## [Applications](#content)

### [Smart cities](#content)

1. **Discovering objects and their relations from entangled scene representations.** ICLR Workshop 2017. [paper](https://arxiv.org/pdf/1702.05068.pdf)

    *David Raposo, Adam Santoro, David Barrett, Razvan Pascanu, Timothy Lillicrap, Peter Battaglia.*  

1. **A simple neural network module for relational reasoning.** NIPS 2017. [paper](https://arxiv.org/pdf/1706.01427.pdf)

    *Adam Santoro, David Raposo, David G.T. Barrett, Mateusz Malinowski, Razvan Pascanu, Peter Battaglia, Timothy Lillicrap.*  

1. **Interaction Networks for Learning about Objects, Relations and Physics.** NIPS 2016. [paper](https://arxiv.org/pdf/1612.00222.pdf)

    *Peter Battaglia, Razvan Pascanu, Matthew Lai, Danilo Rezende, Koray Kavukcuoglu.* 
    
1. **Visual Interaction Networks: Learning a Physics Simulator from Video.** NIPS 2017. [paper](http://papers.nips.cc/paper/7040-visual-interaction-networks-learning-a-physics-simulator-from-video.pdf)

    *Nicholas Watters, Andrea Tacchetti, Théophane Weber, Razvan Pascanu, Peter Battaglia, Daniel Zoran.* 

1. **Graph networks as learnable physics engines for inference and control.** ICML 2018. [paper](https://arxiv.org/pdf/1806.01242.pdf)

    *Alvaro Sanchez-Gonzalez, Nicolas Heess, Jost Tobias Springenberg, Josh Merel, Martin Riedmiller, Raia Hadsell, Peter Battaglia.* 

1. **Learning Multiagent Communication with Backpropagation.** NIPS 2016. [paper](https://arxiv.org/pdf/1605.07736.pdf)

    *Sainbayar Sukhbaatar, Arthur Szlam, Rob Fergus.* 

1. **VAIN: Attentional Multi-agent Predictive Modeling.** NIPS 2017 [paper](https://arxiv.org/pdf/1706.06122.pdf)

    *Yedid Hoshen.* 

1. **Neural Relational Inference for Interacting Systems.** ICML 2018. [paper](https://arxiv.org/pdf/1802.04687.pdf)

    *Thomas Kipf, Ethan Fetaya, Kuan-Chieh Wang, Max Welling, Richard Zemel.* 

1. **Graph Element Networks: adaptive, structured computation and memory.** ICML 2019. [paper](https://arxiv.org/pdf/1904.09019)

    *Ferran Alet, Adarsh K. Jeewajee, Maria Bauza, Alberto Rodriguez, Tomas Lozano-Perez, Leslie Pack Kaelbling.*

1. **Physics-aware Difference Graph Networks for Sparsely-Observed Dynamics.** ICLR 2020. [paper](https://openreview.net/pdf?id=r1gelyrtwH)

	*Sungyong Seo, Chuizheng Meng, Yan Liu.*

### [Agriculture](#content)

1. **Convolutional networks on graphs for learning molecular fingerprints.** NIPS 2015. [paper](https://arxiv.org/pdf/1509.09292.pdf)

    *David Duvenaud, Dougal Maclaurin, Jorge Aguilera-Iparraguirre, Rafael Gómez-Bombarelli, Timothy Hirzel, Alán Aspuru-Guzik, Ryan P. Adams.* 

### [Knowledge Graph](#content)
1. **Modeling Relational Data with Graph Convolutional Networks.** ESWC 2018. [paper](https://arxiv.org/pdf/1703.06103.pdf)

    *Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling.*

1. **Efficient Probabilistic Logic Reasoning with Graph Neural Networks.** ICLR 2020. [paper](https://openreview.net/pdf?id=rJg76kStwH)

	*Yuyu Zhang, Xinshi Chen, Yuan Yang, Arun Ramamurthy, Bo Li, Yuan Qi, Le Song.*

### [Recommender Systems](#content)

1. **Graph Convolutional Neural Networks for Web-Scale Recommender Systems.** KDD 2018. [paper](https://arxiv.org/abs/1806.01973)

    *Rex Ying, Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, Jure Leskovec.*

1. **Geometric Matrix Completion with Recurrent Multi-Graph Neural Networks.** NIPS 2017. [paper](https://arxiv.org/abs/1704.06803)

    *Federico Monti, Michael M. Bronstein, Xavier Bresson.*

