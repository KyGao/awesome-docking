# awesome-docking

<div align="center">
  
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  ![Stars](https://img.shields.io/github/stars/KyGao/awesome-docking?color=yellow&labelColor=555555)  ![Forks](https://img.shields.io/github/forks/KyGao/awesome-docking?color=blue&label=Fork&labelColor=555555)
</div>
<p align="center">
  <img src="resources/cover.png" width="400">
</p>

🔥 Alphafold-latest and RFAA have  revolutionize the scope of docking. Previous work was focused on modeling different components separately, but these two studies have used a single model to simultaneously model all biomolecular interactions. Here is a curated paper list containing all kinds of deep learning-based docking, covering **Protein-Ligand Docking**, **Protein-Protein Docking**, **Protein-Nucleic Acid Docking**, and **Covalent Docking**. Additionally, we refer to works capable of handling various types of docking scenarios simultaneously as '**Versatile Docking**'. Future work will encompass tools, datasets, scoring function design, and other relvant topics. Within each category, entries are listed in reverse chronological order, with the most recent first. If a paper has multiple versions, we reference the initial publication date. The following badges are used for according purpose: ![](https://img.shields.io/badge/paper-5291C8?style=flat&logo=Read.cv&labelColor=555555) ![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555&logocolor=555555) ![](https://img.shields.io/badge/website-AB9FF2?style=flat&logo=temporal&labelColor=555555&logocolor=555555)  ![](https://img.shields.io/badge/tag-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

If you have a paper or resource you'd like to add, please submit a pull request or open an issue.

## Categories

- [Versatile Docking](#versatile-docking)
- [Survey](#survey)
- [Protein-Ligand Docking](#protein-ligand-docking)
  - [Year 2023 -- Protein-Ligand Docking](#year-2023----protein-ligand-docking)
  - [Year 2022 -- Protein-Ligand Docking](#year-2022----protein-ligand-docking)
- [Protein-Protein Docking](#protein-protein-docking)
  - [Year 2023 -- Protein-Protein Docking](#year-2023----protein-protein-docking)
  - [Year 2022 -- Protein-Protein Docking](#year-2022----protein-protein-docking)
- [Protein-Nucleic Acid Docking](#protein-nucleic-acid-docking)
- [Covalent Docking](#covalent-docking)

---

## Versatile Docking

**A glimpse of the next generation of AlphaFold**🔥   
Google DeepMind AlphaFold team and Isomorphic Labs team  
*News, October 2023*  
[![](https://img.shields.io/badge/report-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://storage.googleapis.com/deepmind-media/DeepMind.com/Blog/a-glimpse-of-the-next-generation-of-alphafold/alphafold_latest_oct2023.pdf)
[![](https://img.shields.io/badge/news-AB9FF2?style=flat&logo=temporal&labelColor=555555)](https://deepmind.google/discover/blog/a-glimpse-of-the-next-generation-of-alphafold)
    
**Generalized Biomolecular Modeling and Design with RoseTTAFold All-Atom**🔥   
Rohith Krishna, Jue Wang, Woody Ahern, Pascal Sturmfels, Preetham Venkatesh, Indrek Kalvet, Gyu Rie Lee, Felix S Morey-Burrows, Ivan Anishchenko, Ian R Humphreys, Ryan McHugh, Dionne Vafeados, Xinting Li, George A Sutherland, Andrew Hitchcock, C Neil Hunter, Minkyung Baek, Frank DiMaio, David Baker  
*Preprint, October 2023*  
[![](https://img.shields.io/badge/bioxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2023.10.09.561603)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fbbd97deb6e06fe24c5f20fa85e1f276e3065f99f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)

## Survey

## Protein-Ligand Docking
### Year 2023 -- Protein-Ligand Docking

**Structure prediction of protein-ligand complexes from sequence information with Umol**  
Patrick Bryant, Atharva Kelkar, Andrea Guljas, Cecilia Clementi, Frank Noé  
*Preprint, November 2023*  
[![](https://img.shields.io/badge/bioxiv-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://www.biorxiv.org/content/10.1101/2023.11.03.565471)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F3660911f955c532c186de3b52b03396c851c0aac%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/patrickbryant1/Umol)
![Stars](https://img.shields.io/github/stars/patrickbryant1/Umol?color=yellow&style=social)
![](https://img.shields.io/badge/blind_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

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
![](https://img.shields.io/badge/blind_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Efficient and accurate large library ligand docking with KarmaDock**  
Xujun Zhang, Odin Zhang, Chao Shen, Wanglin Qu, Shicheng Chen, Hanqun Cao, Yu Kang, Zhe Wang, Ercheng Wang, Jintu Zhang, Yafeng Deng, Furui Liu, Tianyue Wang, Hongyan Du, Langcheng Wang, Peichen Pan, Guangyong Chen, Chang-Yu Hsieh, Tingjun Hou  
*Nature Computational Science, September 2023*  
[![](https://img.shields.io/badge/nature-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://doi.org/10.1038/s43588-023-00511-5)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F190320029c58f7e3c1ce8fa9b908d3c88a27df2f%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/schrojunzhang/KarmaDock)
![Stars](https://img.shields.io/github/stars/schrojunzhang/KarmaDock?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Do deep learning models really outperform traditional approaches in molecular docking?**  
Yuejiang Yu, Shuqi Lu, Zhifeng Gao, Hang Zheng, Guolin Ke  
*ICLR workshop MLDD, March 2023*  
[![](https://img.shields.io/badge/iclr_workshop-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=JrtHZdbGtN)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6fd91f8c48b273bb6c256d5ed4e250edd1b156fa%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/blind_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking**🔥   
Gabriele Corso, Hannes Stärk, Bowen Jing, Regina Barzilay, Tommi Jaakkola  
*ICLR, Feburary 2023*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=kKF8_K-mBbS)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F6f0d0b897d0e0963204719b80a8af43ca0d79d90%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/gcorso/DiffDock)
![Stars](https://img.shields.io/github/stars/gcorso/DiffDock?color=yellow&style=social)
![](https://img.shields.io/badge/blind_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**Uni-Mol: A Universal 3D Molecular Representation Learning Framework**  
Gengmo Zhou, Zhifeng Gao, Qiankun Ding, Hang Zheng, Hongteng Xu, Zhewei Wei, Linfeng Zhang, Guolin Ke  
*ICLR, Feburary 2023*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=6K2RM6wVqKu)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F11f42721f56f36a64638677ccde7784040829656%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/dptech-corp/Uni-Mol)
![Stars](https://img.shields.io/github/stars/dptech-corp/Uni-Mol?color=yellow&style=social)
![](https://img.shields.io/badge/known--pocket_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**E3Bind: An End-to-End Equivariant Network for Protein-Ligand Docking**  
Yangtian Zhang, Huiyu Cai, Chence Shi, Jian Tang  
*ICLR, Feburary 2023*  
[![](https://img.shields.io/badge/iclr-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=sO1QiAftQFv)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F7cfc990d89875342528b760a4ffed9de47010b03%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
![](https://img.shields.io/badge/blind_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

### Year 2022 -- Protein-Ligand Docking

**TANKBind: Trigonometry-Aware Neural NetworKs for Drug-Protein Binding Structure Prediction**  
Wei Lu, Qifeng Wu, Jixian Zhang, Jiahua Rao, Chengtao Li, Shuangjia Zheng  
*NeurIPS, November 2022*  
[![](https://img.shields.io/badge/neurips-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://openreview.net/forum?id=MSBDFwGYwwt)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2Fb886797dc34c91f186629403d7c7e2092fc25083%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/luwei0917/TankBind)
![Stars](https://img.shields.io/github/stars/luwei0917/TankBind?color=yellow&style=social)
![](https://img.shields.io/badge/blind_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

**EquiBind: Geometric Deep Learning for Drug Binding Structure Prediction**  
Hannes Stärk, Octavian Ganea, Lagnajit Pattanaik, Dr.Regina Barzilay, Tommi Jaakkola  
*ICML, July 2022*  
[![](https://img.shields.io/badge/neurips-5291C8?style=flat&logo=Read.cv&labelColor=555555)](https://proceedings.mlr.press/v162/stark22b.html)
![Dynamic JSON Badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F5309f4bcb15e3dafbed759488551c1650b55dd81%3Ffields%3DcitationCount&query=%24.citationCount&label=citation&style=social&labelColor=555555&color=ED8936)
[![](https://img.shields.io/badge/code-38C26D?style=flat&logo=GitHub&labelColor=555555)](https://github.com/HannesStark/EquiBind)
![Stars](https://img.shields.io/github/stars/HannesStark/EquiBind?color=yellow&style=social)
![](https://img.shields.io/badge/blind_docking-FD6F6F?style=flat&logo=darkreader&labelColor=555555&logocolor=555555) 

## Protein-Protein Docking
### Year 2023 -- Protein-Protein Docking
### Year 2022 -- Protein-Protein Docking

## Protein-Nucleic Acid Docking

## Covalent Docking

