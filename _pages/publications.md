---
layout: archive
title: "Publications"
author_profile: true
---
# Conference Paper
- [Federated Intelligent Terminals Facilitate Stuttering Monitoring](https://sigport.org/documents/federated-intelligent-terminals-facilitate-stuttering-monitoring "Link of this paper")
  
    **Yongzi Yu**, Wanyong Qiu, Chen Quan, Kun Qian*, Zhihua Wang, Yu Ma, Bin Hu*, Björn W. Schuller, and Yoshiharu Yamamoto,in Proceedings of ICASSP, pp. 1-5, Rhodes Island, Greek, June 2023. (**CCF-B, oral**)


# Jounal Paper

- [A novel technology of structural distance feature of Raman spectra and convolutional neural network for alcohol dependence diagnosis](https://www.sciencedirect.com/science/article/pii/S0026265X23001030 "Link of this paper")

    Yifan Feng, Cheng Chen, Shuxian Liu, Bingyu Dong, **Yongzi Yu**, Chen Chen, Xiaoyi Lv, Microchemical Journal, 189, 108485. (IF=5.304)

# Under review Paper
- Heart Sound Abnormality Detection from Multi-institutional Collaboration: Introducing a Federated Learning Framework
  
    Wanyong Qiu, Chen Quan, Lixian Zhu, **Yongzi Yu**, Zhihua Wang, Yu Ma, Mengkai Sun, Yi Chang, Kun Qian, Bin Hu, Yoshiharu Yamamoto and Bjeorn W.Schuller， IEEE Transactions on Information Forensics and Security, **under review**, pp. 1-11, April 2023.(IF=7.231)

-  Data-Free Federated Transformers Distillation via Diversity Randomly Sample

   Zhongxiang Lei, **Yongzi Yu**, Chongyang Shi, Yuanchi Ma, Jinyan Liu, in Proceedings of NeurIPS, **under review**, pp. 1-12, New Orleans, Dec 2023. (**CCF-A**)

- Explainable Stuttering Recognition using Axial Attention

    Yu Ma, Yuting Huang, Kaixiang Yuan, Guangzhe Xuan, **Yongzi Yu**, Hengrui Zhong, Rui Li, Jian Shen, Kun Qian, Bin Hu, Bj¨orn W. Schuller and Yoshiharu Yama, in Proceedings of ICIC 2023, **under review**, pp. 1-11, Zhengzhou, China, August 2023. (**CCF-C**)

# Working Paper
- A Survey. I wrote it for a transaction
- Federated learning for multitasks. I cooperate with my friend.
- Federated learning using fate. I cooperate with my friend.
- Optimization
- Differential privacy. I am studying it and plan to make some breakthroughs. 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}




