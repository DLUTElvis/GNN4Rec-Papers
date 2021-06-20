# Must-read Papers on GNN-based-Recommender System
GNN: Graph Neural Network.

Contributed by Zihan Liao (East China Normal University).
## [Content](#content)
<table>
<tr><td colspan="1"><a href="#survey">1. Survey</a></td></tr>
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
<tr><td colspan="1"><a href="#Diversified-Recommendation">4. Diversified Recommendation</a></td></tr>
<tr><td colspan="1"><a href="#Related-Technology">5. Related Technology</a></td></tr>
<tr>
    <td>&emsp;<a href="#Matrix-Completion">5.1 Matrix Completion</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Self-Supervised-Learning">5.2 Self-Supervised Learning</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Knowledge-Distillation">5.3 Knowledge Distillation</a></td>
</tr> 
<tr>
    <td>&emsp;<a href="#Hypergraph">5.4 Hypergraph</a></td>
</tr>
<tr><td colspan="1"><a href="#Application-Scenarios">6. Application-Scenarios</a></td></tr>
<tr>
    <td>&emsp;<a href="#Social-Recommendation">6.1 Social Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Package-Recommendation">6.2 Package Recommendation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#Attack-in-Recommendation">6.3 Attack in Recommendation</a></td>
</tr>
</table>

## [Survey](#content)
1. **Graph Neural Networks in Recommender Systems: A Survey.** arXiv, 2020. [paper](https://arxiv.org/pdf/2011.02260.pdf)

    *Shiwen Wu, Wentao Zhang, Fei Sun, Bin Cui.* 

## [General Recommendation](#content)
### [User-Item Bipartite Graph Models](#content)
1. **Graph Embedding for Recommendation against Attribute Inference Attacks.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449813)
   
    *Shijie Zhang, Hongzhi Yin, Tong Chen, Zi Huang, Lizhen Cui, Xiangliang Zhang.*
1. **HGCF: Hyperbolic Graph Convolution Networks for Collaborative Filtering.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3450101) [code](https://github.com/layer6ai-labs/HGCF.)
   
    *Jianing Sun, Zhaoyue Cheng, Saba Zuberi, Felipe Pérez, Maksims Volkovs.* 
1. **A Novel Enhanced Collaborative Autoencoder with Knowledge Distillation for Top-N Recommender Systems.** Neurocomputing, 2018. [paper](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231219X00028/1-s2.0-S0925231218314796/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEHwaCXVzLWVhc3QtMSJGMEQCIEGV1IltJuE%2BhMTQAgAlosfKyaDcOa4M5hhQT4607SZuAiAczFBjT3gwe1A0EQDrmidJzoHSethdVEl6CeQDgo256ir6AwhEEAQaDDA1OTAwMzU0Njg2NSIMZpH7TCXoshgzyPLgKtcDTH4YW7iAIrdETcwihze38XMovq13rE8vNwbp%2F04fmpxHb%2BSwTcVMQzb9dhWq1DpoTpDjQbVE2z%2BAUka%2BuNAt66iPzTa22Fz5dq2VIDA9AD%2B04rdtT0g1OnCnlwfMrRyxVg4aI%2BCT1Pd435UboLpqH4vo%2B7keWtfPgKOxavZuC3LHgkbGU1bFKLsbEolQ35Kt2sLKBdgU0Qt5IqhNiK6KDYApINpG11ZbPZIBsvVhBAHmhY2hxl44IkiYcJevyMb4dj91NMPh2mPQC9DZwWQTgQbRU7tGAI%2Fy%2Bc%2FtGMldY%2B2UzLyVMjDxIkL%2F2UE%2BzceButbRGeoKPhZP5Dpw2RIserhiMeNEI7H6e%2F%2BiearfZIppYnmtVhHh2VNFWP3NVhIsZIDltN9OHv6H4VYRr85HGFPvZE%2Bde%2BWCPyi0J%2FD6EnGuCzv%2BrfKpM2SRyj7pY4he2OF9pwZWI0pOzhDHAkKjQ5rLR4x24iLBQCoebaa9hj3N6B7mRimvtDa3pdyQDNXzaOboDskdxwwtPKainx2kN2UTDbk%2BBzxW8PaCJWPpIl3rYj5t9gj4PXNzchm0JvYzjHrOC%2F09tn5F6E9q5LRMaGrRGqCBrGpk69zB%2BVZbZ9OH0Hhc5sm6MI64p4YGOqYBP4EUiEGJEV8KfvcNEY%2BP%2BW92k3WEkmcCH1BKFObvh1%2FVRGWLx3I2SphHYBQ8rIFyxSG3Yc%2FYhdiKqyQ0xacVIbXicFN7QchG4NbpeL89ek9Mc22i5QYgU1MsUHU5tgkP2PzNze%2Bi0oa6tfFoMgcvBknV9q8fFo1SLeBXov3wXGSOQL4zxqKCwykmAalYFd9PY4NSt4qmAAdXy3W3VCop6cHQSTlPbA%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210616T121406Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYZ6V457ES%2F20210616%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=10fe665e9eb6b3319cf11a7b4c6038bf7b6b876047dbcf47d61cbd24844d4462&hash=ce0778d9adcc3fe785827129bb2638658d41a9a6fa95bb9781d294b13816aeec&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231218314796&tid=spdf-e334f52d-e13a-417f-bb97-c3083af2be97&sid=ef52e556377a9044b36ad1713923edc30933gxrqa&type=client)
   
    *Yiteng Pan, Fazhi He, Haiping Yu.* 
### [Social Graph Enhanced Models](#content)
1. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449844) [code](https://github.com/xiaxin1998/DHCN)
   
    *Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang.*
### [Knowledge Graph Enhanced Models](#content)
1. **Drug Package Recommendation via Interaction-aware Graph Induction.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449962)
   
    *Zhi Zheng, Chao Wang, Dazhong Shen, Baoxing Huai, Tongzhu Liu, Enhong Chen.*
## [Sequential Recommendation](#content)
### [RNN-based Models](#content)
1. **Dynamic Memory based Attention Network for Sequential Recommendation.** AAAI, 2021. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16564)
   
    *Qiaoyu Tan, Jianwei Zhang, Ninghao Liu, Xiao Huang, Hongxia Yang, Jingren Zhou, Xia Hu.*
### [Attention-based Models](#content)
1. **Dynamic Memory based Attention Network for Sequential Recommendation.** AAAI, 2021. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16564)
   
    *Qiaoyu Tan, Jianwei Zhang, Ninghao Liu, Xiao Huang, Hongxia Yang, Jingren Zhou, Xia Hu.*
1. **Sequence-aware Heterogeneous Graph Neural Collaborative Filtering.** SDM, 2021. [paper](https://epubs.siam.org/doi/pdf/10.1137/1.9781611976700.8)
   
    *Chen Li, Linmei Hu, Chuan Shi, Guojie Song, Yuanfu Lu.*
### [Dynamic GNN-based Models](#content)
## [Diversified Recommendation](#content)
1. **DGCN: Diversified Recommendation with Graph Convolutional Networks.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449835)

    *Yu Zheng, Chen Gao, Liang Chen, Depeng Jin, Yong Li.* 
## [Related Technology](#content)
### [Matrix Completion](#content)
### [Self-Supervised Learning](#content)
1. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449844) [code](https://github.com/xiaxin1998/DHCN)
   
    *Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang.*

### [Knowledge Distillation](#content)
### [Hypergraph](#content)
1. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449844) [code](https://github.com/xiaxin1998/DHCN)
   
    *Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang.*
## [Application Scenarios](#content)
### [Social Recommendation](#content)
1. **Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation.** WWW, 2021. [paper](https://dl.acm.org/doi/pdf/10.1145/3442381.3449844) [code](https://github.com/xiaxin1998/DHCN)
   
    *Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang.*
### [Package Recommendation](#content)
1. **Drug Package Recommendation via Interaction-aware Graph Induction.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449962)
   
    *Zhi Zheng, Chao Wang, Dazhong Shen, Baoxing Huai, Tongzhu Liu, Enhong Chen.*
### [Attack in Recommendation](#content)
1. **Graph Embedding for Recommendation against Attribute Inference Attacks.** WWW, 2021. [paper](https://dl.acm.org/doi/10.1145/3442381.3449813)
   
    *Shijie Zhang, Hongzhi Yin, Tong Chen, Zi Huang, Lizhen Cui, Xiangliang Zhang.*
