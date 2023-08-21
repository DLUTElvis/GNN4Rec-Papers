# Must-read Papers on GNN-based-Recommender System
GNN: Graph Neural Network.

Contributed by Zihan Liao (AIDA, East China Normal University).
## [Content](#content)
<table>
<tr><td colspan="1"><a href="#survey123">1. Survey</a></td></tr>
<tr><td colspan="1"><a href="#general-recommendation">2. General Recommendation</a></td></tr>
<tr>
    <td>&emsp;<a href="#user-item-bipartite-graph-models">2.1 User-Item Bipartite Graph Models</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Social-Graph-Enhanced-Models">2.2 Social Graph Enhanced Models</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Knowledge-Graph-Enhanced-Models">2.3 Knowledge Graph Enhanced Models</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Others">2.4 Others</a></td>
</tr>
<tr><td colspan="1"><a href="#Sequential-Recommendation">3. Sequential Recommendation</a></td></tr> 
<tr>
    <td>&emsp;<a href="#RNN-based-Models">3.1 RNN-based Models</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#Attention-based-Models">3.2 Attention-based Models</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Dynamic-GNN-based-Models">3.3 Dynamic GNN-based Models</a></td>
</tr>
<tr><td colspan="1"><a href="#Related-Technology">4. Related Technology</a></td></tr>
<tr>
    <td>&emsp;<a href="#Matrix-Completion">4.1 Matrix Completion</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Random-Walk">4.2 Random Walk</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Self-Supervised-Learning">4.3 Self-Supervised Learning</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Knowledge-Distillation">4.4 Knowledge Distillation</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#Hypergraph">4.5 Hypergraph</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Variational-Inference">4.6 Variational Inference</a></td>
</tr>
<tr><td colspan="1"><a href="#Application-Scenarios">5. Application-Scenarios</a></td></tr>
<tr>
    <td>&emsp;<a href="#Social-Recommendation">5.1 Social Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Package-Recommendation">5.2 Package Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Attack-in-Recommendation">5.3 Attack in Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Diversified-Recommendation">5.4 Diversified Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Hashtag-Recommendation">5.5 Hashtag Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#CTR-Prediction">5.6 CTR Prediction</a></td>
</tr>
</table>

## [Survey](#content)
1. **Graph Neural Networks in Recommender Systems: A Survey.** arXiv, 2020. [paper](https://arxiv.org/pdf/2011.02260.pdf)

    *Shiwen Wu, Wentao Zhang, Fei Sun, Bin Cui.* 

## [General Recommendation](#content)
### [User-Item Bipartite Graph Models](#content)
1. **Self-supervised Graph Learning for Recommendation.** SIGIR, 2021. [paper](https://arxiv.org/pdf/2010.10783.pdf) [code](https://github.com/wujcan/SGL)
   
    *Jiancan Wu, Xiang Wang, Fuli Feng, Xiangnan He, Liang Chen, Jianxun Lian, Xing Xie.*
1. **DGCN: Diversified Recommendation with Graph Convolutional Networks.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449835) [code](https://github.com/tsinghua-fib-lab/DGCN)
   
    *Yu Zheng, Chen Gao, Liang Chen, Depeng Jin, Yong Li.*
1. **Graph Embedding for Recommendation against Attribute Inference Attacks.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449813)
   
    *Shijie Zhang, Hongzhi Yin, Tong Chen, Zi Huang, Lizhen Cui, Xiangliang Zhang.*
1. **HGCF: Hyperbolic Graph Convolution Networks for Collaborative Filtering.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3450101) [code](https://github.com/layer6ai-labs/HGCF)
   
    *Jianing Sun, Zhaoyue Cheng, Saba Zuberi, Felipe Pérez, Maksims Volkovs.*
1. **Multi-Component Graph Convolutional Collaborative Filtering.** AAAI, 2020. [paper](https://arxiv.org/pdf/1911.10699.pdf) [code](https://github.com/RuijiaW/Multi-Component-Graph-Convolutional-Collaborative-Filtering)
   
    *Xiao Wang, Ruijia Wang, Chuan Shi, Guojie Song, Qingyong Li.*
1. **Revisiting Graph Based Collaborative Filtering: A Linear Residual Graph Convolutional Network Approach.** AAAI, 2020. [paper](https://arxiv.org/pdf/2001.10167.pdf) [code](https://github.com/newlei/LR-GCCF)
   
    *Lei Chen, Le Wu, Richang Hong, Kun Zhang, Meng Wang.*
1. **GraphSAIL: Graph Structure Aware Incremental Learning for Recommender Systems.** CIKM, 2020. [paper](https://dl.acm.org/doi/10.1145/3340531.3412754)
   
    *Yishi Xu, Yingxue Zhang, Wei Guo, Huifeng Guo, Ruiming Tang, Mark Coates.*
1. **Inductive Matrix Completion Based on Graph Neural Networks.** ICLR, 2020. [paper](https://openreview.net/pdf?id=ByxxgCEYDS) [code](https://github.com/muhanzhang/IGMC)
   
    *Muhan Zhang, Yixin Chen.*   
1. **MultiSage: Empowering GCN with Contextualized Multi-Embeddings on Web-Scale Multipartite Networks.** KDD, 2020. [paper](https://dl.acm.org/doi/pdf/10.1145/3394486.3403293)
   
    *Carl Yang, Aditya Pal, Andrew Zhai, Nikil Pancha, Jiawei Han, Charles Rosenberg, Jure Leskovec.*
1. **Graph Convolutional Network for Recommendation with Low-pass Collaborative Filters.** KDD, 2020. [paper](http://proceedings.mlr.press/v119/yu20e/yu20e.pdf) [code](https://github.com/Wenhui-Yu/LCFN)
   
    *Wenhui Yu, Zheng Qin.*
1. **An Efficient Neighborhood-based Interaction Model for Recommendation on Heterogeneous Graph.** KDD, 2020. [paper](https://arxiv.org/pdf/2007.00216.pdf) [code](https://github.com/Jinjiarui/GraphHINGE)
   
    *Jiarui Jin, Jiarui Qin, Yuchen Fang, Kounianhua Du, Weinan Zhang, Yong Yu, Zheng Zhang, Alexander J. Smola.*
1. **M2GRL: A Multi-task Multi-view Graph Representation Learning Framework for Web-scale Recommender Systems.** KDD, 2020. [paper](https://arxiv.org/pdf/2005.10110.pdf) [code](https://github.com/99731/M2GRL)
   
    *Menghan Wang, Yujie Lin, Guli Lin, Keping Yang, Xiao-Ming Wu.*   
1. **Knowing your FATE: Friendship, Action and Temporal Explanations for User Engagement Prediction on Social Apps.** KDD, 2020. [paper](https://arxiv.org/pdf/2006.06427.pdf) [code](https://github.com/tangxianfeng/FATE)
   
    *Xianfeng Tang, Yozen Liu, Neil Shah, Xiaolin Shi, Prasenjit Mitra, Suhang Wang.*   
1. **LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation.** SIGIR, 2020. [paper](https://arxiv.org/pdf/2002.02126.pdf) [code](https://github.com/gusye1234/LightGCN-PyTorch)
   
    *Xiangnan He, Kuan Deng, Xiang Wang, Yan Li, Yong-Dong Zhang, Meng Wang*   
1. **Distilling Structured Knowledge into Embeddings for Explainable and Accurate Recommendation.** WSDM, 2020. [paper](https://arxiv.org/pdf/1912.08422.pdf) [code](https://github.com/yuan-pku/Distilling-Structured-Knowledge-into-Embeddings-for-Explainable-and-Accurate-Recommendation)
   
    *Yuan Zhang, Xiaoran Xu, Hanning Zhou, Yan Zhang*
1. **Reviews Meet Graphs: Enhancing User and Item Representations for Recommendation with Hierarchical Attentive Graph Neural Network.**  EMNLP/IJCNLP, 2019. [paper](https://www.aclweb.org/anthology/D19-1494.pdf) [code](https://github.com/wuch15/Reviews-Meet-Graphs)
   
    *Chuhan Wu, Fangzhao Wu, Tao Qi, Suyu Ge, Yongfeng Huang, Xing Xie.*   
1. **Binarized Collaborative Filtering with Distilling Graph Convolutional Networks.** IJCAI, 2019. [paper](https://arxiv.org/pdf/1906.01829.pdf)
   
    *Haoyu Wang, Defu Lian, Yong Ge.*
1. **MMGCN: Multi-modal Graph Convolution Network for Personalized Recommendation of Micro-video.** MM, 2019. [paper](https://dl.acm.org/doi/10.1145/3343031.3351034) [code](https://github.com/weiyinwei/MMGCN)
   
    *Yinwei Wei, Xiang Wang, Liqiang Nie, Xiangnan He, Richang Hong, Tat-Seng Chua.*   
1. **A Novel Enhanced Collaborative Autoencoder with Knowledge Distillation for Top-N Recommender Systems.** Neurocomputing, 2018. [paper](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231219X00028/1-s2.0-S0925231218314796/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLWVhc3QtMSJGMEQCIEGV1IltJuE%2BhMTQAgAlosfKyaDcOa4M5hhQT4607SZuAiAczFBjT3gwe1A0EQDrmidJzoHSethdVEl6CeQDgo256ir6AwhEEAQaDDA1OTAwMzU0Njg2NSIMZpH7TCXoshgzyPLgKtcDTH4YW7iAIrdETcwihze38XMovq13rE8vNwbp%2F04fmpxHb%2BSwTcVMQzb9dhWq1DpoTpDjQbVE2z%2BAUka%2BuNAt66iPzTa22Fz5dq2VIDA9AD%2B04rdtT0g1OnCnlwfMrRyxVg4aI%2BCT1Pd435UboLpqH4vo%2B7keWtfPgKOxavZuC3LHgkbGU1bFKLsbEolQ35Kt2sLKBdgU0Qt5IqhNiK6KDYApINpG11ZbPZIBsvVhBAHmhY2hxl44IkiYcJevyMb4dj91NMPh2mPQC9DZwWQTgQbRU7tGAI%2Fy%2Bc%2FtGMldY%2B2UzLyVMjDxIkL%2F2UE%2BzceButbRGeoKPhZP5Dpw2RIserhiMeNEI7H6e%2F%2BiearfZIppYnmtVhHh2VNFWP3NVhIsZIDltN9OHv6H4VYRr85HGFPvZE%2Bde%2BWCPyi0J%2FD6EnGuCzv%2BrfKpM2SRyj7pY4he2OF9pwZWI0pOzhDHAkKjQ5rLR4x24iLBQCoebaa9hj3N6B7mRimvtDa3pdyQDNXzaOboDskdxwwtPKainx2kN2UTDbk%2BBzxW8PaCJWPpIl3rYj5t9gj4PXNzchm0JvYzjHrOC%2F09tn5F6E9q5LRMaGrRGqCBrGpk69zB%2BVZbZ9OH0Hhc5sm6MI64p4YGOqYBP4EUiEGJEV8KfvcNEY%2BP%2BW92k3WEkmcCH1BKFObvh1%2FVRGWLx3I2SphHYBQ8rIFyxSG3Yc%2FYhdiKqyQ0xacVIbXicFN7QchG4NbpeL89ek9Mc22i5QYgU1MsUHU5tgkP2PzNze%2Bi0oa6tfFoMgcvBknV9q8fFo1SLeBXov3wXGSOQL4zxqKCwykmAalYFd9PY4NSt4qmAAdXy3W3VCop6cHQSTlPbA%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210616T121406Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYZ6V457ES%2F20210616%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=10fe665e9eb6b3319cf11a7b4c6038bf7b6b876047dbcf47d61cbd24844d4462&hash=ce0778d9adcc3fe785827129bb2638658d41a9a6fa95bb9781d294b13816aeec&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231218314796&tid=spdf-e334f52d-e13a-417f-bb97-c3083af2be97&sid=ef52e556377a9044b36ad1713923edc30933gxrqa&type=client)
   
    *Yiteng Pan, Fazhi He, Haiping Yu.*
### [Social Graph Enhanced Models](#content)
1. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449844) [code](https://github.com/Coder-Yu/RecQ)
   
    *Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang.*
1. **DiffNet++: A Neural Influence and Interest Diffusion Network for Social Recommendation.** TKDE, 2020. [paper](https://arxiv.org/pdf/2002.00844.pdf) [code](https://github.com/PeiJieSun/diffnet)
   
    *Le Wu, Junwei Li, Peijie Sun, Richang Hong, Yong Ge, Meng Wang.*
1. **Modelling High-Order Social Relations for Item Recommendation.** TKDE, 2020. [paper](https://arxiv.org/pdf/2003.10149.pdf)
   
    *Yang Liu, Liang Chen, Xiangnan He, Jiaying Peng, Zibin Zheng, Jie Tang.*
1. **paper2repo: GitHub Repository Recommendation for Academic Papers.** WWW, 2020. [paper](https://arxiv.org/pdf/2004.06059.pdf) [code](https://github.com/hrukalive/WWW2020_paper2repo)
   
    *Huajie Shao, Dachun Sun, Jiahao Wu, Zecheng Zhang, Aston Zhang, Shuochao Yao, Shengzhong Liu, Tianshi Wang, Chao Zhang, Tarek F. Abdelzaher.*
1. **Graph Enhanced Representation Learning for News Recommendation.** WWW, 2020. [paper](https://arxiv.org/pdf/2003.14292.pdf)
   
    *Suyu Ge, Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang.*
1. **Multi-Graph Convolution Collaborative Filtering.** ICDM, 2019. [paper](https://arxiv.org/pdf/2001.00267.pdf)
   
    *Jianing Sun, Yingxue Zhang, Chen Ma, Mark Coates, Huifeng Guo, Ruiming Tang, Xiuqiang He.*
### [Knowledge Graph Enhanced Models](#content)
1. **Drug Package Recommendation via Interaction-aware Graph Induction.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449962)
   
    *Zhi Zheng, Chao Wang, Dazhong Shen, Baoxing Huai, Tongzhu Liu, Enhong Chen.*
1. **Multi-behavior Recommendation with Graph Convolutional Networks.** SIGIR, 2020. [paper](https://dl.acm.org/doi/10.1145/3397271.3401072)
   
    *Bowen Jin, Chen Gao, Xiangnan He, Depeng Jin, Yong Li.*
1. **A2-GCN: An Attribute-aware Attentive GCN Model for Recommendation.** TKDE, 2020. [paper](https://arxiv.org/pdf/2003.09086.pdf) [code](https://github.com/liufancs/a2_gcn)
   
    *Fan Liu; Zhiyong Cheng; Lei Zhu; Chenghao Liu; Liqiang Nie.*   
1. **paper2repo: GitHub Repository Recommendation for Academic Papers.** WWW, 2020. [paper](https://arxiv.org/pdf/2004.06059.pdf) [code](https://github.com/hrukalive/WWW2020_paper2repo)
   
    *Huajie Shao, Dachun Sun, Jiahao Wu, Zecheng Zhang, Aston Zhang, Shuochao Yao, Shengzhong Liu, Tianshi Wang, Chao Zhang, Tarek F. Abdelzaher.*
1. **Graph Enhanced Representation Learning for News Recommendation.** WWW, 2020. [paper](https://arxiv.org/pdf/2003.14292.pdf)
   
    *Suyu Ge, Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang.*
1. **Long-tail Hashtag Recommendation for Micro-videos with Graph Convolutional Network.** CIKM, 2019. [paper](https://dl.acm.org/doi/10.1145/3357384.3357912)
   
    *Mengmeng Li, Tian Gan, Meng Liu, Zhiyong Cheng, Jianhua Yin, Liqiang Nie.*
1. **Bayes EMbedding (BEM): Refining Representation by Integrating Knowledge Graphs and Behavior-specific Networks.** CIKM, 2019. [paper](https://arxiv.org/pdf/1908.10611.pdf)
   
    *Yuting Ye, Xuwu Wang, Jiangchao Yao, Kunyang Jia, Jingren Zhou, Yanghua Xiao, Hongxia Yang.*
1. **Multi-Graph Convolution Collaborative Filtering.** ICDM, 2019. [paper](https://arxiv.org/pdf/2001.00267.pdf)
   
    *Jianing Sun, Yingxue Zhang, Chen Ma, Mark Coates, Huifeng Guo, Ruiming Tang, Xiuqiang He.*
### [Others](#content)
1. **Fi-GNN: Modeling Feature Interactions via Graph Neural Networks for CTR Prediction.** CIKM, 2019. [paper](https://arxiv.org/pdf/1910.05552.pdf) [code](https://github.com/CRIPAC-DIG/Fi_GNN)

    *Zekun Li, Zeyu Cui, Shu Wu, Xiaoyu Zhang, Liang Wang.* 
## [Sequential Recommendation](#content)
### [RNN-based Models](#content)
1. **Dynamic Memory based Attention Network for Sequential Recommendation.** AAAI, 2021. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16564)
   
    *Qiaoyu Tan, Jianwei Zhang, Ninghao Liu, Xiao Huang, Hongxia Yang, Jingren Zhou, Xia Hu.*
1. **Handling Information Loss of Graph Neural Networks for Session-based Recommendation.** KDD, 2020. [paper](https://dl.acm.org/doi/10.1145/3394486.3403170) [code](https://github.com/twchen/lessr)
   
    *Tianwen Chen, Raymond Chi-Wing Wong.*
1. **Calendar Graph Neural Networks for Modeling Time Structures in Spatiotemporal User Behaviors.** KDD, 2020. [paper](https://arxiv.org/pdf/2006.06820.pdf) [code](https://github.com/DM2-ND/CalendarGNN)
   
    *Daheng Wang, Meng Jiang, Munira Syed, Oliver Conway, Vishal Juneja, Sriram Subramanian, Nitesh V. Chawla.*   
1. **Session-Based Recommendation with Graph Neural Networks.** AAAI, 2019. [paper](https://ojs.aaai.org//index.php/AAAI/article/view/3804) [code](https://github.com/CRIPAC-DIG/SR-GNN)
   
    *Shu Wu, Yuyuan Tang, Yanqiao Zhu, Liang Wang, Xing Xie, Tieniu Tan.*
1. **Rethinking the Item Order in Session-based Recommendation with Graph Neural Networks.** CIKM, 2019. [paper](https://arxiv.org/pdf/1911.11942.pdf) [code](https://github.com/RuihongQiu/FGNN)
   
    *Ruihong Qiu, Jingjing Li, Zi Huang, Hongzhi Yin.*

### [Attention-based Models](#content)
1. **Dynamic Memory based Attention Network for Sequential Recommendation.** AAAI, 2021. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16564)
   
    *Qiaoyu Tan, Jianwei Zhang, Ninghao Liu, Xiao Huang, Hongxia Yang, Jingren Zhou, Xia Hu.*
1. **Sequence-aware Heterogeneous Graph Neural Collaborative Filtering.** SDM, 2021. [paper](https://epubs.siam.org/doi/pdf/10.1137/1.9781611976700.8)
   
    *Chen Li, Linmei Hu, Chuan Shi, Guojie Song, Yuanfu Lu.*
1. **Memory Augmented Graph Neural Networks for Sequential Recommendation.** AAAI, 2020. [paper](https://arxiv.org/pdf/1912.11730.pdf)
   
    *Chen Ma, Liheng Ma, Yingxue Zhang, Jianing Sun, Xue Liu, Mark Coates.*
### [Dynamic GNN-based Models](#content)
## [Related Technology](#content)
### [Matrix Completion](#content)
1. **Inductive Matrix Completion Based on Graph Neural Networks.** ICLR, 2020. [paper](https://openreview.net/pdf?id=ByxxgCEYDS) [code](https://github.com/muhanzhang/IGMC)
   
    *Muhan Zhang, Yixin Chen.* 
### [Random Walk](#content)
1. **An Efficient Neighborhood-based Interaction Model for Recommendation on Heterogeneous Graph.** KDD, 2020. [paper](https://arxiv.org/pdf/2007.00216.pdf) [code](https://github.com/Jinjiarui/GraphHINGE)
   
    *Jiarui Jin, Jiarui Qin, Yuchen Fang, Kounianhua Du, Weinan Zhang, Yong Yu, Zheng Zhang, Alexander J. Smola.*
1. **Distilling Structured Knowledge into Embeddings for Explainable and Accurate Recommendation.** WSDM, 2020. [paper](https://arxiv.org/pdf/1912.08422.pdf) [code](https://github.com/yuan-pku/Distilling-Structured-Knowledge-into-Embeddings-for-Explainable-and-Accurate-Recommendation)
   
    *Yuan Zhang, Xiaoran Xu, Hanning Zhou, Yan Zhang*
### [Self-Supervised Learning](#content)
1. **Self-Supervised Learning on Graphs: Deep Insights and New Directions.** arXiv, 2021. [paper](https://arxiv.org/pdf/2006.10141.pdf)
   
    *Wei Jin, Tyler Derr, Haochen Liu, Yiqi Wang, Suhang Wang, Zitao Liu, Jiliang Tang.*
1. **Self-supervised Graph Learning for Recommendation.** SIGIR, 2021. [paper](https://arxiv.org/pdf/2010.10783.pdf) [code](https://github.com/wujcan/SGL)
   
    *Jiancan Wu, Xiang Wang, Fuli Feng, Xiangnan He, Liang Chen, Jianxun Lian, Xing Xie.*   
1. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449844) [code](https://github.com/xiaxin1998/DHCN)
   
    *Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang.*
### [Knowledge Distillation](#content)
1. **GraphSAIL: Graph Structure Aware Incremental Learning for Recommender Systems.** CIKM, 2020. [paper](https://dl.acm.org/doi/10.1145/3340531.3412754)
   
    *Yishi Xu, Yingxue Zhang, Wei Guo, Huifeng Guo, Ruiming Tang, Mark Coates.*
1. **Distilling Structured Knowledge into Embeddings for Explainable and Accurate Recommendation.** WSDM, 2020. [paper](https://arxiv.org/pdf/1912.08422.pdf) [code](https://github.com/yuan-pku/Distilling-Structured-Knowledge-into-Embeddings-for-Explainable-and-Accurate-Recommendation)
   
    *Yuan Zhang, Xiaoran Xu, Hanning Zhou, Yan Zhang*   
1. **Knowledge Distillation via Instance Relationship Graph.** CVPR, 2019. [paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Knowledge_Distillation_via_Instance_Relationship_Graph_CVPR_2019_paper.pdf)
   
    *Yufan Liu, Jiajiong Cao, Bing Li, Chunfeng Yuan, Weiming Hu, Yangxi Li, Yunqiang Duan.*
1. **Binarized Collaborative Filtering with Distilling Graph Convolutional Networks.** IJCAI, 2019. [paper](https://arxiv.org/pdf/1906.01829.pdf)
   
    *Haoyu Wang, Defu Lian, Yong Ge.*
### [Hypergraph](#content)
1. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449844) [code](https://github.com/Coder-Yu/RecQ)
   
    *Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang.*
### [Variational Inference](#content)
1. **Bayes EMbedding (BEM): Refining Representation by Integrating Knowledge Graphs and Behavior-specific Networks.** CIKM, 2019. [paper](https://arxiv.org/pdf/1908.10611.pdf)
   
    *Yuting Ye, Xuwu Wang, Jiangchao Yao, Kunyang Jia, Jingren Zhou, Yanghua Xiao, Hongxia Yang.*
## [Application Scenarios](#content)
### [Social Recommendation](#content)
1. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449844) [code](https://github.com/Coder-Yu/RecQ.)
   
    *Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang.*
### [Package Recommendation](#content)
1. **Drug Package Recommendation via Interaction-aware Graph Induction.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449962)
   
    *Zhi Zheng, Chao Wang, Dazhong Shen, Baoxing Huai, Tongzhu Liu, Enhong Chen.*
### [Attack in Recommendation](#content)
1. **Graph Embedding for Recommendation against Attribute Inference Attacks.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449813)
   
    *Shijie Zhang, Hongzhi Yin, Tong Chen, Zi Huang, Lizhen Cui, Xiangliang Zhang.*
### [Diversified Recommendation](#content)
1. **DGCN: Diversified Recommendation with Graph Convolutional Networks.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449835) [code](https://github.com/tsinghua-fib-lab/DGCN)
   
    *Yu Zheng, Chen Gao, Liang Chen, Depeng Jin, Yong Li.*
### [Hashtag Recommendation](#content)
1. **Long-tail Hashtag Recommendation for Micro-videos with Graph Convolutional Network.** CIKM, 2019. [paper](https://dl.acm.org/doi/10.1145/3357384.3357912)
   
    *Mengmeng Li, Tian Gan, Meng Liu, Zhiyong Cheng, Jianhua Yin, Liqiang Nie.*
### [CTR Prediction](#content)
1. **Fi-GNN: Modeling Feature Interactions via Graph Neural Networks for CTR Prediction.** CIKM, 2019. [paper](https://arxiv.org/pdf/1910.05552.pdf) [code](https://github.com/CRIPAC-DIG/Fi_GNN)

    *Zekun Li, Zeyu Cui, Shu Wu, Xiaoyu Zhang, Liang Wang.* 