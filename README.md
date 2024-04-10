<h1 align="center">
🧬 Awesome Docking
</h1>
<div align="center">
  
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  ![Stars](https://img.shields.io/github/stars/KyGao/awesome-docking?color=yellow&labelColor=555555)  ![Forks](https://img.shields.io/github/forks/KyGao/awesome-docking?color=blue&label=Fork&labelColor=555555)
</div>
<p align="center">
  <img src="resources/cover.png" width="400">
</p>

Alphafold-latest🔥 and RFAA🔥 have revolutionize the scope of docking. Previous work was focused on modeling different components separately, but these two studies have used a single model to simultaneously model all biomolecular interactions. Here is a curated paper list containing all kinds of deep learning-based docking, covering **Protein-Ligand Docking**, **Protein-Protein Docking**, **Protein-Nucleic Acid Docking**, and **Covalent Docking**. Additionally, we refer to works capable of handling various types of docking scenarios simultaneously as '**Versatile Docking**'. Future work will encompass tools, datasets, scoring function design, and other relvant topics. Within each category, entries are listed in reverse chronological order, with the most recent first. If a paper has multiple versions, we reference the initial publication date. The following badges are used for according purpose: 

![](https://img.shields.io/badge/paper-5291C8?style=flat&logo=Read.cv&labelColor=555555) ![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555&logocolor=555555) ![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)  ![](https://img.shields.io/badge/tag-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

If you have a paper or resource you'd like to add, please submit a pull request or open an issue.

## Categories

- [Versatile Docking](#versatile-docking)
- [Protein-Ligand Docking](#protein-ligand-docking)
  - [2024 -- Protein-Ligand](#2024----protein-ligand)
  - [2023 -- Protein-Ligand](#2023----protein-ligand)
  - [2022 -- Protein-Ligand](#2022----protein-ligand)
- [Protein-Protein Docking](#protein-protein-docking)
  - [2024 -- Protein-Protein](#2024----protein-protein)
  - [2023 -- Protein-Protein](#2023----protein-protein)
  - [2022 -- Protein-Protein](#2022----protein-protein)
  - [2021 -- Protein-Protein](#2021----protein-protein)
- [Protein-Nucleic Acid Docking](#protein-nucleic-acid-docking)
  - [2023 -- Protein-Nucleic Acid](#2023----protein-nucleic-acid)
- [Covalent Docking](#covalent-docking)
- [Survey](#survey)
  - [Protein-Ligand](#protein-ligand)
  - [Protein-Protein](#protein-protein)
  - [Protein-Nucleic Acid](#protein-nucleic-acid)
  - [Covalent](#covalent)
- [Traditional Docking Tools](#traditional-docking-tools)
  - [Open-source and free access](#open-source-and-free-access)
  - [Commercial tools](#commercial-tool)

---

## Versatile Docking

🔥**A glimpse of the next generation of AlphaFold**   
Google DeepMind AlphaFold team and Isomorphic Labs team  
*News, October 2023*  
[![](https://img.shields.io/badge/report-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://storage.googleapis.com/deepmind-media/DeepMind.com/Blog/a-glimpse-of-the-next-generation-of-alphafold/alphafold_latest_oct2023.pdf)
[![](https://img.shields.io/badge/news-AB9FF2?style=flat&logo=temporal&labelColor=555555)](https://deepmind.google/discover/blog/a-glimpse-of-the-next-generation-of-alphafold)
    
🔥**Generalized Biomolecular Modeling and Design with RoseTTAFold All-Atom**  
Rohith Krishna, Jue Wang, Woody Ahern, Pascal Sturmfels, Preetham Venkatesh, Indrek Kalvet, Gyu Rie Lee, Felix S Morey-Burrows, Ivan Anishchenko, Ian R Humphreys, Ryan McHugh, Dionne Vafeados, Xinting Li, George A Sutherland, Andrew Hitchcock, C Neil Hunter, Minkyung Baek, Frank DiMaio, David Baker  
*Science, March 2024*  
[![](https://img.shields.io/badge/science-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.science.org/doi/10.1126/science.adl2528)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbbd97deb6e06fe24c5f20fa85e1f276e3065f99f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/baker-laboratory/RoseTTAFold-All-Atom)
![Stars](https://img.shields.io/github/stars/baker-laboratory/RoseTTAFold-All-Atom?color=yellow&style=social)

## Protein-Ligand Docking

### 2024 -- Protein-Ligand
**GeoDirDock: Guiding Docking Along Geodesic Paths**  
Raúl Miñán, Javier Gallardo, Álvaro Ciudad, Alexis Molina  
*Preprint, April 2024*  
[![](https://img.shields.io/badge/under_review-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2404.06481.pdf)

**Interformer: An Interaction-Aware Model for Protein-Ligand Docking and Affinity Prediction**  
Houtim Lai, Longyue Wang, Ruiyuan Qian, Geyan Ye, Juhong Huang, Fandi Wu, Fang Wu, Xiangxiang Zeng, Wei Liu  
*Preprint, April 2024*  
[![](https://img.shields.io/badge/under_review-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.researchsquare.com/article/rs-3995849/v1)

**FABind+: Enhancing Molecular Docking through Improved Pocket Prediction and Pose Generation**  
Kaiyuan Gao, Qizhi Pei, Jinhua Zhu, Tao Qin, Kun He, Lijun Wu  
*Preprint, April 2024*  
[![](https://img.shields.io/badge/arXiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2403.20261.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6594ec85ba41682c2ae0b2c205a92ec372f0ec4b%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/QizhiPei/FABind)
![Stars](https://img.shields.io/github/stars/QizhiPei/FABind?color=yellow&style=social)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**ArtiDock: fast and accurate machine learning approach to protein-ligand docking based on multimodal data augmentation**  
Taras Voitsitskyi, Semen Yesylevskyy, Volodymyr Bdzhola, Roman Stratiichuk, Ihor Koleiev, Zakhar Ostrovsky, Volodymyr Vozniak, Ivan Khropachov, Pavlo Henitsoi, Leonid Popryho, Roman Zhytar, Alan Nafiiev, Serhii Starosyla  
*Preprint, March 2024*  
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2024.03.14.585019)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fad788c56812bea808f4cb5c31f208a6347f1d24d%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/news-AB9FF2?style=flat&logo=temporal&labelColor=555555)](https://www.biopharmatrend.com/post/713-artidock-from-receptorai-next-generation-ai-docking-that-beats-diffdock-and-alphafold-latest)
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Re-Dock: Towards Flexible and Realistic Molecular Docking with Diffusion Bridge**  
Yufei Huang, Odin Zhang, Lirong Wu, Cheng Tan, Haitao Lin, Zhangyang Gao, Siyuan Li, Stan. Z. Li  
*Preprint, February 2024*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2402.11459.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F68981c9aba4c06176f3c062b94c3e6861371bdb6%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**PackDock: a Diffusion Based Side Chain Packing Model for Flexible Protein-Ligand Docking**  
Runze Zhang, Xinyu Jiang, Duanhua Cao, Jie Yu, Mingan Chen, Zhehuan Fan, Xiangtai Kong, Jiacheng Xiong, Zimei Zhang, Wei Zhang, Shengkun Ni, Yitian Wang, Shenghua Gao, Mingyue Zheng  
*Preprint, February 2024*  
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2024.01.31.578200v1.full.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F770f53f09f541b96d0e3693ae4066b897ef9d9f5%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/Zhang-Runze/PackDock)
![Stars](https://img.shields.io/github/stars/Zhang-Runze/PackDock?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**State-specific protein–ligand complex structure prediction with a multiscale deep generative model**  
Zhuoran Qiao, Weili Nie, Arash Vahdat, Thomas F. Miller II, Animashree Anandkumar  
*Nature Machine Intelligence, February 2024*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s42256-024-00792-z)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fc9561b15c25ca781ccf1a384e978e28341bac0e4%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/zrqiao/NeuralPLexer)
![Stars](https://img.shields.io/github/stars/zrqiao/NeuralPLexer?color=yellow&style=social)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**DynamicBind: Predicting ligand-specific protein-ligand complex structure with a deep equivariant generative model**  
Wei Lu, Jixian Zhang, Huang Weifeng, Ziqiao Zhang, Chengtao Li, Shuangjia Zheng  
*Nature Communications, February 2024*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-024-45461-2)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F51894ffcf778630e7b021bc473d13d028a3b9158%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/luwei0917/DynamicBind)
![Stars](https://img.shields.io/github/stars/luwei0917/DynamicBind?color=yellow&style=social)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Deep confident steps to new pockets: strategies for docking generalization**   
Gabriele Corso, Arthur Deng, Nicholas Polizzi, Regina Barzilay, Tommi S. Jaakkola   
*ICLR, Feburary 2024*   
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=UfBIxpTK10) 
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fa2af79d2c6a75919d586590487cc3b39b42a94c2%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/LDeng0205/confidence-bootstrapping)
![Stars](https://img.shields.io/github/stars/LDeng0205/confidence-bootstrapping?color=yellow&style=social)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**(NeuralMD) A Multi-Grained Symmetric Differential Equation Model for Learning Protein-Ligand Binding Dynamics**  
Shengchao Liu, Weitao Du, Yanjing Li, Zhuoxinran Li, Vignesh Bhethanabotla, Nakul Rampal, Omar Yaghi, Christian Borgs, Anima Anandkumar, Hongyu Guo, Jennifer Chayes  
*Preprint, January 2024*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2401.15122.pdf) 
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0215dd9f346534bf4c4247220501d7ab7d7715c6%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/dynamics-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

### 2023 -- Protein-Ligand 
**(DeltaDock) Multi-scale Iterative Refinement towards Robust and Versatile Molecular Docking**  
Jiaxian Yan, Zaixi Zhang, Kai Zhang, Qi Liu  
*Preprint, December 2023*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2311.18574)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbedc29f7b553bd322df265e2c5a215f1dfd19b4e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**DiffBindFR: An SE(3) Equivariant Network for Flexible Protein-Ligand Docking**  
Jintao Zhu, Zhonghui Gu, Jianfeng Pei, Luhua Lai  
*Preprint, November 2023*
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/pdf/2311.15201.pdf)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F04911aa5c3b5d6d07507a0079ebbe6c504a462ae%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/HBioquant/DiffBindFR)
![Stars](https://img.shields.io/github/stars/HBioquant/DiffBindFR?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Structure prediction of protein-ligand complexes from sequence information with Umol**  
Patrick Bryant, Atharva Kelkar, Andrea Guljas, Cecilia Clementi, Frank Noé  
*Preprint, November 2023*  
[![](https://img.shields.io/badge/biorxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubmed.ncbi.nlm.nih.gov/37745556/)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3660911f955c532c186de3b52b03396c851c0aac%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/patrickbryant1/Umol)
![Stars](https://img.shields.io/github/stars/patrickbryant1/Umol?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**(FlexPose) Equivariant Flexible Modeling of the Protein–Ligand Binding Pose with Geometric Deep Learning**  
Tiejun Dong, Ziduo Yang, Jun Zhou, and Calvin Yu-Chian Chen  
*JCTC, November 2023*  
[![](https://img.shields.io/badge/jctc-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/full/10.1021/acs.jctc.3c00273)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Ff2633ad706a8537bd7d8d89561d4bbad71373380%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/tiejundong/FlexPose)
![Stars](https://img.shields.io/github/stars/tiejundong/FlexPose?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**PoseBusters: AI-based docking methods fail to generate physically valid poses or generalise to novel sequences**  
Martin Buttenschoen, Garrett M. Morris, Charlotte M. Deane  
*Preprint, October 2023.*  
[![](https://img.shields.io/badge/arxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2308.05777)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fdd267334c01365d362ed8239394f0ad61b41e269%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/maabuu/posebusters)
![Stars](https://img.shields.io/github/stars/maabuu/posebusters?color=yellow&style=social)
![](https://img.shields.io/badge/dataset-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**FABind: Fast and Accurate Protein-Ligand Binding**  
Qizhi Pei, Kaiyuan Gao, Lijun Wu, Jinhua Zhu, Yingce Xia, Shufang Xie, Tao Qin, Kun He, Tie-Yan Liu, Rui Yan  
*NeurIPS, September 2023*  
[![](https://img.shields.io/badge/neurips-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=PnWakgg1RL)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fef5fceee2925cb8441bf1de100b67a33eeeef3a3%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/QizhiPei/FABind)
![Stars](https://img.shields.io/github/stars/QizhiPei/FABind?color=yellow&style=social)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Efficient and accurate large library ligand docking with KarmaDock**  
Xujun Zhang, Odin Zhang, Chao Shen, Wanglin Qu, Shicheng Chen, Hanqun Cao, Yu Kang, Zhe Wang, Ercheng Wang, Jintu Zhang, Yafeng Deng, Furui Liu, Tianyue Wang, Hongyan Du, Langcheng Wang, Peichen Pan, Guangyong Chen, Chang-Yu Hsieh, Tingjun Hou  
*Nature Computational Science, September 2023*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://doi.org/10.1038/s43588-023-00511-5)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F190320029c58f7e3c1ce8fa9b908d3c88a27df2f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/schrojunzhang/KarmaDock)
![Stars](https://img.shields.io/github/stars/schrojunzhang/KarmaDock?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**(EDM-Dock) Deep Learning Model for Efficient Protein–Ligand Docking with Implicit Side-Chain Flexibility**  
Matthew R. Masters, Amr H. Mahmoud, Yao Wei, and Markus A. Lill  
*JCIM, March 2023*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://doi.org/10.1038/s43588-023-00511-5)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb29d66e1c466bd248232eee0d987118b258fb18e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/MatthewMasters/EDM-Dock)
![Stars](https://img.shields.io/github/stars/MatthewMasters/EDM-Dock?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Do deep learning models really outperform traditional approaches in molecular docking?**  
Yuejiang Yu, Shuqi Lu, Zhifeng Gao, Hang Zheng, Guolin Ke  
*ICLR workshop MLDD, March 2023*  
[![](https://img.shields.io/badge/iclr_workshop-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=JrtHZdbGtN)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6fd91f8c48b273bb6c256d5ed4e250edd1b156fa%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

🔥**DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking**   
Gabriele Corso, Hannes Stärk, Bowen Jing, Regina Barzilay, Tommi Jaakkola  
*ICLR, Feburary 2023*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=kKF8_K-mBbS)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6f0d0b897d0e0963204719b80a8af43ca0d79d90%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/gcorso/DiffDock)
![Stars](https://img.shields.io/github/stars/gcorso/DiffDock?color=yellow&style=social)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Uni-Mol: A Universal 3D Molecular Representation Learning Framework**  
Gengmo Zhou, Zhifeng Gao, Qiankun Ding, Hang Zheng, Hongteng Xu, Zhewei Wei, Linfeng Zhang, Guolin Ke  
*ICLR, Feburary 2023*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=6K2RM6wVqKu)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F11f42721f56f36a64638677ccde7784040829656%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/dptech-corp/Uni-Mol)
![Stars](https://img.shields.io/github/stars/dptech-corp/Uni-Mol?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**E3Bind: An End-to-End Equivariant Network for Protein-Ligand Docking**  
Yangtian Zhang, Huiyu Cai, Chence Shi, Jian Tang  
*ICLR, Feburary 2023*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=sO1QiAftQFv)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7cfc990d89875342528b760a4ffed9de47010b03%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

### 2022 -- Protein-Ligand 

**TANKBind: Trigonometry-Aware Neural NetworKs for Drug-Protein Binding Structure Prediction**  
Wei Lu, Qifeng Wu, Jixian Zhang, Jiahua Rao, Chengtao Li, Shuangjia Zheng  
*NeurIPS, November 2022*  
[![](https://img.shields.io/badge/neurips-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=MSBDFwGYwwt)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb886797dc34c91f186629403d7c7e2092fc25083%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/luwei0917/TankBind)
![Stars](https://img.shields.io/github/stars/luwei0917/TankBind?color=yellow&style=social)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**EquiBind: Geometric Deep Learning for Drug Binding Structure Prediction**  
Hannes Stärk, Octavian Ganea, Lagnajit Pattanaik, Dr.Regina Barzilay, Tommi Jaakkola  
*ICML, July 2022*  
[![](https://img.shields.io/badge/neurips-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.mlr.press/v162/stark22b.html)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5309f4bcb15e3dafbed759488551c1650b55dd81%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/HannesStark/EquiBind)
![Stars](https://img.shields.io/github/stars/HannesStark/EquiBind?color=yellow&style=social)
![](https://img.shields.io/badge/blind-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

## Protein-Protein Docking
### 2024 -- Protein-Protein
**Improving deep learning protein monomer and complex structure prediction using DeepMSA2 with huge metagenomics data**  
Wei Zheng, Qiqige Wuyun, Yang Li, Chengxin Zhang, P. Lydia Freddolino, Yang Zhang  
*Nature Methods, January 2024*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41592-023-02130-4)
[![](https://img.shields.io/badge/deepmsa2-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://zhanggroup.org/DeepMSA)
[![](https://img.shields.io/badge/dmfold-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://zhanggroup.org/DMFold)

**Neural Probabilistic Protein-Protein Docking via a Differentiable Energy Model**  
Huaijin Wu, Wei Liu, Yatao Bian, Jiaxiang Wu, Nianzu Yang, Junchi Yan  
*ICLR, 2024*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=qg2boc2AwU)  

**Rigid Protein-Protein Docking via Equivariant Elliptic-Paraboloid Interface Prediction**  
Ziyang Yu, Wenbing Huang, Yang Liu  
*ICLR, 2024*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=zgQ0PHeGnL)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7868daf3774809e652f83914fb7b44e36a78d7f2%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/yaledeus/ElliDock)
![Stars](https://img.shields.io/github/stars/yaledeus/ElliDock?color=yellow&style=social)
![](https://img.shields.io/badge/rigid-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

### 2023 -- Protein-Protein
**(GeoDock) Flexible protein–protein docking with a multitrack iterative transformer**  
Lee-Shin Chu, Jeffrey A. Ruffolo, Ameya Harmalkar, Jeffrey J. Gray  
*Protein Science, December 2023*  
[![](https://img.shields.io/badge/prosci-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://onlinelibrary.wiley.com/doi/epdf/10.1002/pro.4862)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F1c8af104ce6af12952581007aa19baa63f663a8f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/Graylab/GeoDock)
![Stars](https://img.shields.io/github/stars/Graylab/GeoDock?color=yellow&style=social)

**Enhancing alphafold-multimer-based protein complex structure prediction with MULTICOM in CASP15**  
Jian Liu, Zhiye Guo, Tianqi Wu, Rajashree Roy, Farhan Quadir, Chen Chen, Jianlin Cheng  
*Communications Biology, November 2023*  
[![](https://img.shields.io/badge/Communications_Biology-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s42003-023-05525-3)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F679d7389ab657a666d0149cfad9ce3b62ee50870%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/BioinfoMachineLearning/MULTICOM3)
![Stars](https://img.shields.io/github/stars/BioinfoMachineLearning/MULTICOM3?color=yellow&style=social)
![](https://img.shields.io/badge/add--on_for_alphafold-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  

**DockGame: Cooperative Games for Multimeric Rigid Protein Docking**  
Vignesh Ram Somnath, Pier Giuseppe Sessa, Maria Rodriguez Martinez, Andreas Krause  
*Preprint, October 2023*  
[![](https://img.shields.io/badge/arXiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://arxiv.org/abs/2310.06177)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0a76e5107737cd3017a880f52b91ccade4504bf3%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/vsomnath/dockgame)
![Stars](https://img.shields.io/github/stars/vsomnath/dockgame?color=yellow&style=social)
![](https://img.shields.io/badge/rigid-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/multimeric-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)

**Diffdock-pp: Rigid protein-protein docking with diffusion models**  
Mohamed Amine Ketata, Cedrik Laue, Ruslan Mammadov, Hannes Stärk, Menghua Wu, Gabriele Corso, Céline Marquet, Regina Barzilay, Tommi S. Jaakkola  
*ICLR workshop MLDD, March 2023*  
[![](https://img.shields.io/badge/iclr_workshop-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=AM7WbQxuRS)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F345eb3195aac43eb5dcaacc0a7fd288be0fa4491%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/ketatam/DiffDock-PP)
![Stars](https://img.shields.io/github/stars/ketatam/DiffDock-PP?color=yellow&style=social)
![](https://img.shields.io/badge/rigid-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Deep Learning for Flexible and Site-Specific Protein Docking and Design**  
Matthew McPartlon, Jinbo Xu  
*BioRxiv, April 2023*  
[![](https://img.shields.io/badge/bioRxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2023.04.01.535079)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F663d7f9d2b4b8fcbb488fdb07a7458f734e62726%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
![](https://img.shields.io/badge/known--pocket-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  

### 2022 -- Protein-Protein
**Physics-informed deep neural network for rigid-body protein docking**  
Freyr Sverrisson, Jean Feydy, Joshua Southern, Michael M Bronstein, Bruno E Correia  
*ICLR workshop MLDD, April 2022*  
[![](https://img.shields.io/badge/iclr_workshop-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=5yn5shS6wN)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F59f1e3f333f85db9294658ccfe7f0a5f6a9458bd%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/rigid-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  

**Independent SE(3)-Equivariant Models for End-to-End Rigid Protein Docking**  
Octavian-Eugen Ganea, Xinyuan Huang, Charlotte Bunne, Yatao Bian, Regina Barzilay, Tommi S. Jaakkola, Andreas Krause  
*ICLR, January 2022*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=GQjaI9mLet)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb190df7856f71856cbd98e1394c6513df279d53e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/octavian-ganea/equidock_public)
![Stars](https://img.shields.io/github/stars/octavian-ganea/equidock_public?color=yellow&style=social)
![](https://img.shields.io/badge/rigid-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

### 2021 -- Protein-Protein 
🔥**Protein complex prediction with AlphaFold-Multimer**  
Richard Evans, Michael O’Neill, A. Pritzel, Natasha Antropova, Andrew Senior, Tim Green, Augustin Zídek, Russ Bates, Sam Blackwell, Jason Yim, O. Ronneberger, S. Bodenstein, Michal Zielinski, Alex Bridgland, Anna Potapenko, Andrew Cowie, Kathryn Tunyasuvunakool, Rishub Jain, Ellen Clancy, Pushmeet Kohli, J. Jumper, D. Hassabis  
*BioRxiv, October 2021*  
[![](https://img.shields.io/badge/bioRxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2021.10.04.463034)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F2556e820cba6bda75f6f31b76bc74d9e36d72cb3%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/google-deepmind/alphafold)
![Stars](https://img.shields.io/github/stars/google-deepmind/alphafold?color=yellow&style=social) 
![](https://img.shields.io/badge/flexible-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  

## Protein-Nucleic Acid Docking
### 2023 -- Protein-Nucleic Acid

🔥**Accurate prediction of protein-nucleic acid complexes using RoseTTAFoldNA**  
Minkyung Baek, Ryan McHugh, Ivan Anishchenko, Hanlun Jiang, David Baker, Frank DiMaio  
*Nature Methods, November 2023*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41592-023-02086-5)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F0c0ad28901d1cae2cc6c7b9c1f66e9e46afc5ec5%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/uw-ipd/RoseTTAFold2NA)
![Stars](https://img.shields.io/github/stars/uw-ipd/RoseTTAFold2NA?color=yellow&style=social)

**EquiPNAS: improved protein-nucleic acid binding site prediction using protein-language-model-informed equivariant deep graph neural networks**  
Rahmatullah Roche, Bernard Moussad, Md Hossain Shuvo, Sumit Tarafder, Debswapna Bhattacharya  
*BioRxiv, September 2023*  
[![](https://img.shields.io/badge/bioRxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/search/Protein-Nucleic%252BAcid%252B)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/Bhattacharya-Lab/EquiPNAS)
![Stars](https://img.shields.io/github/stars/Bhattacharya-Lab/EquiPNAS?color=yellow&style=social)
![](https://img.shields.io/badge/language_model-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Evaluating native-like structures of RNA-protein complexes through the deep learning method**  
Chengwei Zeng, Yiren Jian, Soroush Vosoughi, Chen Zeng, Yunjie Zhao  
*Nature Communications, February 2023*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41467-023-36720-9)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F43253ab8bfa9f19c18764fdcfb550395f5cdfc75%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/Zhaolab-GitHub/DRPScore_v1.0)
![Stars](https://img.shields.io/github/stars/Zhaolab-GitHub/DRPScore_v1.0?color=yellow&style=social)
![](https://img.shields.io/badge/evaluation-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 


## Covalent Docking

**Cov_DOX: A Method for Structure Prediction of Covalent Protein–Ligand Bindings**  
Lin Wei, Yaru Chen, Jiaqi Liu, Li Rao, Yanliang Ren, Xin Xu, Jian Wan  
*Journal of Medicinal Chemistry, March 2022*  
[![](https://img.shields.io/badge/Medicinal_Chemistry-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/full/10.1021/acs.jmedchem.1c02007)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FURL%3Ahttps%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FCov_DOX%253A-A-Method-for-Structure-Prediction-of-Wei-Chen%2Fec80310e4d4a9f0308963e1cfccbd624d9fde2da%2F%3Ffields%3DcitationCount&query=citationCount&style=social&label=Citation&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/non--cov_based-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  

**CovPDB: a high-resolution coverage of the covalent protein–ligand interactome**  
Mingjie Gao, Aurelien F. A. Moumbock, Ammar Qaseem, Qianqing Xu, Stefan Gunther  
*Nucleic Acids Research, September 2021*  
[![](https://img.shields.io/badge/Nucleic_Acids_Res.-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://academic.oup.com/nar/article/50/D1/D445/6377397)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FURL%3Ahttps%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FCovPDB%253A-a-high-resolution-coverage-of-the-covalent-Gao-Moumbock%2Fa800cdd78504470a4b8c3a5fd31879a249686676%2F%3Ffields%3DcitationCount&query=citationCount&style=social&label=Citation&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://drug-discovery.vm.uni-freiburg.de/covpdb/)
![](https://img.shields.io/badge/dataset-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Fragment-based covalent ligand discovery**  
Wenchao Lu, Milka Kostic, Tinghu Zhang, Jianwei Che, Matthew P. Patricelli, Lyn H. Jones, Edward T. Chouchaniae, Nathanael S. Gray  
*RSC Chemical Biology, February 2021*  
[![](https://img.shields.io/badge/RSC_Chemical_Biology-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.rsc.org/en/content/articlelanding/2021/CB/D0CB00222D)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FURL%3Ahttps%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FFragment-based-covalent-ligand-discovery-Lu-Kostic%2Fb525ba2c0b80e4587f2b1c6f667cf0009a46b356%2F%3Ffields%3DcitationCount&query=citationCount&style=social&label=Citation&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/hybrid_method-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  

**Covalent docking of large libraries for the discovery of chemical probes**  
Nir London, Rand M Miller, Shyam Krishnan, Kenji Uchida, John J Irwin, Oliv Eidam, Lucie Gibold, Peter Cimermančič, Richard Bonnet, Brian K Shoichet, Jack Taunton  
*Nature Chemical Biology, September 2014*  
[![](https://img.shields.io/badge/Nature_Chemical_Biology-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4232467/)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FURL%3Ahttps%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FCovalent-Docking-of-Large-Libraries-for-the-of-London-Miller%2F90211028d92ba511542f8b1ccdbdbc7720e6710a%2F%3Ffields%3DcitationCount&query=citationCount&style=social&label=Citation&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://drug-discovery.vm.uni-freiburg.de/covpdb/)
![](http://covalent.docking.org/)
![](https://img.shields.io/badge/non--cov_based-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  

**Docking Covalent Inhibitors: A Parameter Free Approach To Pose Prediction and Scoring**  
Kai Zhu, Kenneth W. Borrelli, Jeremy R. Greenwood, Tyler Day, Robert Abel, Ramy S. Farid, and Edward Harder  
*Journal of Chemical Information and Modeling, June 2014*  
[![](https://img.shields.io/badge/Chemical_Information_and_Modeling-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://pubs.acs.org/doi/10.1021/ci500118s)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FURL%3Ahttps%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FDocking-Covalent-Inhibitors%253A-A-Parameter-Free-To-Zhu-Borrelli%2F2d9998235f41a9b9ef91cde87dc1bab05b194592%2F%3Ffields%3DcitationCount&query=citationCount&style=social&label=Citation&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/parameter_free-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  

**CovalentDock: Automated covalent docking with parameterized covalent linkage energy estimation and molecular geometry constraints**  
Xuchang Ouyang, Shuo Zhou, Chinh Tran To Su, Zemei Ge, Runtao Li, Chee Keong Kwoh  
*Journal of Computational Chemistry, February 2013*  
[![](https://img.shields.io/badge/Computational_Chemistry-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://onlinelibrary.wiley.com/doi/10.1002/jcc.23136)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FURL%3Ahttps%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FCovalentDock%253A-Automated-covalent-docking-with-and-Ouyang-Zhou%2F13e5c154c51d9d9950b8eca7668d4e83b957c1ae%2F%3Ffields%3DcitationCount&query=citationCount&style=social&label=Citation&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/project-38C26D?style=flat&logo=googlecloud&labelColor=555555)](https://code.google.com/archive/p/covalentdock/)
![](https://img.shields.io/badge/Autodock_based-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

## Survey
### Protein-Ligand 

**Machine-learning methods for ligand–protein molecular docking**  
Kevin Crampon, Alexis Giorkallos, Myrtille Deldossi, Stéphanie Baud, Luiz Angelo Steffenel   
*Drug Discovery Today, January 2022*  
[![](https://img.shields.io/badge/drugdis-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.sciencedirect.com/science/article/abs/pii/S1359644621003974)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F790e0a160fff355ce2fbb51beb4362dfcc58a830%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**A practical guide to large-scale docking**  
Brian J. Bender, Stefan Gahbauer, Andreas Luttens, Jiankun Lyu, Chase M. Webb, Reed M. Stein, Elissa A. Fink, Trent E. Balius, Jens Carlsson, John J. Irwin & Brian K. Shoichet    
*Nature Protocols, December 2021*  
[![](https://img.shields.io/badge/natureprotocols-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.nature.com/articles/s41596-021-00597-z)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F31a2f29489f4a95ed85f8ffb854de758e8be4c09%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**An Overview of Scoring Functions Used for Protein–Ligand Interactions in Molecular Docking**  
Jin Li, Ailing Fu, Le Zhang  
*Interdisciplinary Sciences: Computational Life Sciences, March 2019*  
[![](https://img.shields.io/badge/InterSciComLifeSci-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://link.springer.com/article/10.1007/s12539-019-00327-w)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7eaa28830e31289a102084653654c3f911f05413%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**Progress in molecular docking**  
Jiyu Fan, Ailing Fu, Le Zhang  
*Quantitative Biology, June 2019*  
[![](https://img.shields.io/badge/QuantBio-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://link.springer.com/article/10.1007/s40484-019-0172-y)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3c8b953cccb19a0a1679c28f73b33df20b2fd10e%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**Molecular Docking: Shifting Paradigms in Drug Discovery**  
Luca Pinzi, Giulio Rastelli    
*International Journal of Molecular Sciences, September 2019*  
[![](https://img.shields.io/badge/ijms-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.mdpi.com/1422-0067/20/18/4331)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F8f7948d72b19b3be7191396c5e637cdb14a2371c%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**From machine learning to deep learning: Advances in scoring functions for protein–ligand docking**  
Chao Shen, Junjie Ding, Zhe Wang, Dongsheng Cao, Xiaoqin Ding, Tingjun Hou   
*WIREs computational molecular science, June 2019*  
[![](https://img.shields.io/badge/ComMolSci-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://wires.onlinelibrary.wiley.com/doi/abs/10.1002/wcms.1429)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F9a297e83ca2bf1b3af089e51d85e927544ddfe04%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**Software for molecular docking: a review**  
Nataraj S. Pagadala, Khajamohiddin Syed, Jack Tuszynski   
*Biophysical Reviews, January 2017*  
[![](https://img.shields.io/badge/BioReview-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://link.springer.com/article/10.1007/s12551-016-0247-1)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fcd6e2fde7c80146a5f42bbe4e3638951e796ce0a%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**Dynamic Docking: A Paradigm Shift in Computational Drug Discovery**  
Gioia, Dario, Martina Bertazzo, Maurizio Recanatini, Matteo Masetti, Andrea Cavalli   
*Molecules, November 2017*  
[![](https://img.shields.io/badge/Molecules-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.mdpi.com/1420-3049/22/11/2029)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F49d40250c1bf1eb95b5c8caa3c2f663f336f117d%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**Insights into Protein–Ligand Interactions: Mechanisms, Models, and Methods**  
Xing Du, Yi Li, Yuan-Ling Xia, Shi-Meng Ai, Jing Liang, Peng Sang, Xing-Lai Ji, Shu-Qun Liu  
*International Journal of Molecular Sciences, January 2016*  
[![](https://img.shields.io/badge/MolSci-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.mdpi.com/1422-0067/17/2/144)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbfd1b11cf32a063a7deec39ec0d76232f365582a%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

### Protein-Protein

**Protein–Protein Docking: Past, Present, and Future**  
Sharon Sunny, PB Jayaraj  
*The protein journal, February 2022*  
[![](https://img.shields.io/badge/PROTEINJ-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://link.springer.com/article/10.1007/s10930-021-10031-8)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F60d7599aef518716e447853f0fa0cdafa774eabb%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**A survey on computational models for predicting protein–protein interactions**   
Lun Hu, Xiaojuan Wang, Yu-An Huang, Pengwei Hu, Zhu-Hong You  
*Briefings in Bioinformatics, September 2021*  
[![](https://img.shields.io/badge/BriefBioinform-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://academic.oup.com/bib/article/22/5/bbab036/6159365)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F171b6d5c35ac3cda7a821bff4041f360bee20e54%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**What method to use for protein–protein docking?**  
Kathryn Porter, Israel Desta, Dima Kozakov, Sandor Vajda  
*Current Opinion in Structural Biology, April 2019*   
[![](https://img.shields.io/badge/CURROPINSTRUCBIOL-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.sciencedirect.com/science/article/abs/pii/S0959440X18300691)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5098ef6ab4fbf1b5a7b180fd91cddac231abfd85%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

### Protein-Nucleic Acid 

**Challenges in structural modeling of RNA-protein interactions**  
Xudong Liu, Yingtian Duan, Xu Hong, Juan Xie, Shiyong Liu  
*Current Opinion in Structural Biology, June 2023*  
[![](https://img.shields.io/badge/StructuralBiology-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.sciencedirect.com/science/article/pii/S0959440X23000970)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb56c2784e1154c86541ee16b1aaeacfc6a46a321%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

**Protein–RNA interaction prediction with deep learning: structure matters**  
Junkang Wei, Siyuan Chen, Licheng Zong, Xin Gao, Yu Li  
*Briefings in Bioinformatics， January 2022*  
[![](https://img.shields.io/badge/BrefInBio-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://academic.oup.com/bib/article/23/1/bbab540/6470965)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fd8eb3568107b21787751cd6c25776aacfa991979%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

### Covalent 

**Docking covalent targets for drug discovery: stimulating the computer-aided drug design community of possible pitfalls and erroneous practices**  
Abdul-Quddus Kehinde Oyedele, Abdeen Tunde Ogunlana, Ibrahim Damilare Boyenle, Ayodeji Oluwadamilare Adeyemi, Temionu Oluwakemi Rita, Temitope Isaac Adelusi, Misbaudeen Abdul-Hammed, Oluwabamise Emmanuel Elegbeleye, Tope Tunji Odunitan  
*Molecular Diversity, September 2022*  
[![](https://img.shields.io/badge/Molecular_Diversity-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://link.springer.com/article/10.1007/s11030-022-10523-4)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FURL%3Ahttps%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FDocking-covalent-targets-for-drug-discovery%253A-the-of-Oyedele-Ogunlana%2Ff347739ce3bbe75cf8bebe42aebbed12d4d9da6c%2F%3Ffields%3DcitationCount&query=citationCount&style=social&label=Citation&labelColor=555555&color=ED8936)

## Traditional Docking Tools
### Open-source and free access

- **Smina**  
  [![](https://img.shields.io/badge/source_forge-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://sourceforge.net/projects/smina)
- 🔥**AutoDock Suite**  
  [![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://ccsb.scripps.edu/projects/docking)
  [![](https://img.shields.io/badge/AutoDock_Vina-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/ccsb-scripps/AutoDock-Vina/releases)
  ![Stars](https://img.shields.io/github/stars/ccsb-scripps/AutoDock-Vina?color=yellow&style=social)
- **AutoDock-GPU**  
  [![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/ccsb-scripps/AutoDock-GPU)
  ![Stars](https://img.shields.io/github/stars/ccsb-scripps/AutoDock-GPU?color=yellow&style=social)
- **MGLTools software suite**  
  [![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://ccsb.scripps.edu/mgltools/)
  ![](https://img.shields.io/badge/free--access-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 
- **SwissDock**    
  [![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](http://www.swissdock.ch/)
  ![](https://img.shields.io/badge/free--access-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555)  
- **rDock**  
  [![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://rdock.github.io)
  [![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/CBDD/rDock)
  ![Stars](https://img.shields.io/github/stars/CBDD/rDock?color=yellow&style=social)

### Commercial tool

- **GOLD Suite**  
  [![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://www.ch.cam.ac.uk/computing/software/gold-suite)
- **GLIDE**  
  [![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://www.schrodinger.com/products/glide)
- **MOE-Dock**  
  [![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)](https://www.computabio.com/molecular-docking-service.html)
