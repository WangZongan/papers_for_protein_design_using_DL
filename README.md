# List of papers about Proteins Design using Deep Learning

## About this repository

Inspired by Kevin Kaichuang Yang's [Machine-learning-for-proteins](https://github.com/yangkky/Machine-learning-for-proteins). In terms of the fast changing of **protein design in DL**, I started making this dynamic repository as a record of papers for these newcomers like me.  

## Menu

- [List of papers about Proteins Design using Deep Learning](#list-of-papers-about-proteins-design-using-deep-learning)
  - [About this repository](#about-this-repository)
  - [Menu](#menu)
  - [Reviews](#reviews)
  - [Hallucination](#hallucination)
    - [trRosetta/trDesign-based](#trrosettatrdesign-based)
    - [AlphaFold2-based](#alphafold2-based)
  - [Function to Scaffold](#function-to-scaffold)
  - [Scaffold/Template to Sequence](#scaffoldtemplate-to-sequence)
  - [Sequence to Scaffold](#sequence-to-scaffold)
  - [Function to Sequence](#function-to-sequence)
  - [Generative Models](#generative-models)
    - [CM-Align](#cm-align)
    - [VAE-based](#vae-based)
    - [GAN-based](#gan-based)
    - [NLP-based](#nlp-based)
    - [GNN-based](#gnn-based)
    - [Bayesian-based](#bayesian-based)
    - [Pretrained-based](#pretrained-based)
    - [RL-based](#rl-based)
  - [Molecular Design Models](#molecular-design-models)

## Reviews

**Deep generative modeling for protein design**  
Strokach, Alexey, and Philip M. Kim.  
[Current Opinion in Structural Biology 72 (2022)](https://www.sciencedirect.com/science/article/pii/S0959440X21001573)

**Protein sequence design with deep generative models**  
Wu, Zachary, et al.  
[Current Opinion in Chemical Biology 65 (2021)](https://www.sciencedirect.com/science/article/pii/S136759312100051X)

## Hallucination

Hallucination is inverting prediction model for design

### trRosetta/trDesign-based

 **Design of proteins presenting discontinuous functional sites using deep learning**  
Tischer, Doug, et al.  
[bioRxiv (2020)](https://www.biorxiv.org/content/10.1101/2020.11.29.402743v1.abstract)  

**De novo protein design by deep network hallucination**  
Anishchenko, I., Pellock, S.J., Chidyausiku, T.M. et al.  
[Nature (2021)](https://doi.org/10.1038/s41586-021-04184-w)  

**Structure-based protein design with deep learning**  
Ovchinnikov, Sergey, and Po-Ssu Huang.  
[Current opinion in chemical biology 65 (2021): 136-144.](https://www.sciencedirect.com/science/article/pii/S1367593121001125)  

**Protein sequence design by conformational landscape optimization**  
Norn, Christoffer, et al.  
[Proceedings of the National Academy of Sciences 118.11 (2021)](https://www.pnas.org/content/118/11/e2017228118)

**Fast differentiable DNA and protein sequence optimization for molecular design**  
Linder, Johannes, and Georg Seelig.  
[arXiv preprint arXiv:2005.11275 (2020)](https://arxiv.org/abs/2005.11275)

### AlphaFold2-based

**End-to-end learning of multiple sequence alignments with differentiable Smith-Waterman**  
Petti, Samantha, et al.  
[bioRxiv (2021)](http://repository.cshl.edu/id/eprint/40409/)  

**Deep learning methods for designing proteins scaffolding functional sites**  
Wang, J., et al.  
[bioRxiv(2021)](https://europepmc.org/article/ppr/ppr419387)  

**AlphaDesign: A de novo protein design framework based on AlphaFold**  
Jendrusch, Michael, Jan O. Korbel, and S. Kashif Sadiq.  
[bioRxiv (2021)](https://www.biorxiv.org/content/10.1101/2021.10.11.463937.abstract)  

**Using AlphaFold for Rapid and Accurate Fixed Backbone Protein Design**  
Moffat, Lewis, Joe G. Greener, and David T. Jones.  
[bioRxiv (2021)](https://www.biorxiv.org/content/10.1101/2021.08.24.457549v1)  

## Function to Scaffold

**Design of metalloproteins and novel protein folds using variational autoencoders**  
Greener, Joe G., Lewis Moffat, and David T. Jones.  
[Scientific reports 8.1 (2018)](https://www.nature.com/articles/s41598-018-34533-1)  

**Function-guided protein design by deep manifold sampling**  
Vladimir Gligorijevic, Stephen Ra, Daniel Berenberg, Richard Bonneau, Kyunghyun Cho  
[NeurIPS2021](https://www.mlsb.io/papers_2021/MLSB2021_Function-guided_protein_design_by.pdf)

**A backbone-centred energy function of neural networks for protein design**  
Huang, B., Xu, Y., Hu, X. et al  
[Nature (2022)](https://doi.org/10.1038/s41586-021-04383-5)

## Scaffold/Template to Sequence

**Rotamer-Free Protein Sequence Design Based on Deep Learning and Self-Consistency**  
Liu, Yufeng, et al.  
[Nature portfolio(2022)](https://www.researchsquare.com/article/rs-1209166/v1)

**DenseCPD: improving the accuracy of neural-network-based computational protein sequence design with DenseNet**  
Qi, Yifei, and John ZH Zhang.  
[Journal of chemical information and modeling 60.3 (2020)](https://pubs.acs.org/doi/pdf/10.1021/acs.jcim.0c00043)  

**TERMinator: A Neural Framework for Structure-Based Protein Design using Tertiary Repeating Motifs**  
Li, Alex J., et al.  
[NeurIPS 2021](https://www.mlsb.io/papers_2021/MLSB2021_TERMinator:_A_Neural_Framework.pdf)  

**Fast and flexible protein design using deep graph neural networks.**  
Strokach, Alexey, et al.  
[Cell Systems 11.4 (2020)](https://www.sciencedirect.com/science/article/pii/S2405471220303276)  

**Computational generation of proteins with predetermined three-dimensional shapes using ProteinSolver.**  
Strokach, Alexey, et al.  
[STAR protocols 2.2 (2021)](https://www.sciencedirect.com/science/article/pii/S2666166721002124)  

**Computational protein design with deep learning neural networks**  
Wang, Jingxue, et al.  
[Scientific reports 8.1 (2018)](https://www.nature.com/articles/s41598-018-24760-x.pdf)  

**Design of metalloproteins and novel protein folds using variational autoencoders**.
Greener, Joe G., Lewis Moffat, and David T. Jones.  
[Scientific reports 8.1 (2018)](https://www.nature.com/articles/s41598-018-34533-1)

## Sequence to Scaffold

**Protein sequence design with a learned potential**  
Anand-Achim, Namrata, et al.  
[Biorxiv (2021)](https://www.biorxiv.org/content/10.1101/2020.01.06.895466v3.full.pdf)

## Function to Sequence

**Deep neural language modeling enables functional protein generation across families**  
Madani, Ali, et al.  
[bioRxiv (2021)](https://www.biorxiv.org/content/10.1101/2021.07.18.452833.abstract)  

## Generative Models

### CM-Align

**AutoFoldFinder: An Automated Adaptive Optimization Toolkit for De Novo Protein Fold Design**  
Shuhao Zhang, Youjun Xu, Jianfeng Pei, Luhua Lai  
[NeurIPS2021](https://www.mlsb.io/papers_2021/MLSB2021_AutoFoldFinder.pdf)  

### VAE-based

**Generating functional protein variants with variational autoencoders**  
Hawkins-Hooker, Alex, et al.  
[PLoS computational biology 17.2 (2021)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008736)

**Therapeutic enzyme engineering using a generative neural network**  
Giessel, Andrew, et al.  
[Scientific Reports 12.1 (2022)](https://www.nature.com/articles/s41598-022-05195-x)

**Function-guided protein design by deep manifold sampling**  
Gligorijevic, Vladimir, et al.  
[bioRxiv (2021)](https://www.biorxiv.org/content/10.1101/2021.12.22.473759v1)

**Deep generative models create new and diverse protein structures**  
Zeming, Tom, Yann and Alexander.  
[NeurIPS 2021](https://www.mlsb.io/papers_2021/MLSB2021_Deep_generative_models_create.pdf)

### GAN-based

**Conditional Generative Modeling for De Novo Protein Design with Hierarchical Functions**  
Kucera, Tim, Matteo Togninalli, and Laetitia Meng-Papaxanthos  
[bioRxiv (2021)](https://www.biorxiv.org/content/10.1101/2021.11.10.467885v1.abstract)  

**Expanding functional protein sequence spaces using generative adversarial networks**  
Repecka, Donatas, et al.  
[Nature Machine Intelligence 3.4 (2021)](https://www.nature.com/articles/s42256-021-00310-5)

**Generative modeling for protein structures**  
Anand, Namrata, and Possu Huang.  
[NeurIPS 2018](https://proceedings.neurips.cc/paper/2018/file/afa299a4d1d8c52e75dd8a24c3ce534f-Paper.pdf)

**HelixGAN: A bidirectional Generative Adversarial Network with search in latent space for generation under constraints**
Xie, Xuezhi, and Philip M. Kim.  
[NeurIPS 2021](https://www.mlsb.io/papers_2021/MLSB2021_HelixGAN:_A_bidirectional_Generative.pdf)
### NLP-based

**Recurrent neural network model for constructive peptide design**  
Müller, Alex T., Jan A. Hiss, and Gisbert Schneider.  
[Journal of chemical information and modeling 58.2 (2018)](https://pubs.acs.org/doi/pdf/10.1021/acs.jcim.7b00414)  

**Deep learning to design nuclear-targeting abiotic miniproteins**  
Schissel, Carly K., et al.  
[Nature Chemistry 13.10 (2021)](https://www.nature.com/articles/s41557-021-00766-3)

**Protein design and variant prediction using autoregressive generative models**  
Shin, Jung-Eun, et al.  
[Nature communications 12.1 (2021)](https://www.nature.com/articles/s41467-021-22732-w.pdf)

**ECNet is an evolutionary context-integrated deep learning framework for protein engineering**  
Luo, Yunan, et al.  
[Nature communications 12.1 (2021)](https://www.nature.com/articles/s41467-021-25976-8)

**Guided Generative Protein Design using Regularized Transformers**  
Castro, Egbert, et al.  
[arXiv preprint arXiv:2201.09948 (2022)](https://arxiv.org/abs/2201.09948)

**Generative Language Modeling for Antibody Design**  
Shuai, Richard W., Jeffrey A. Ruffolo, and Jeffrey J. Gray.  
[bioRxiv (2021)](https://www.biorxiv.org/content/10.1101/2021.12.13.472419v1)

### GNN-based

**Generative models for graph-based protein design**  
Ingraham, John, et al.  
[NeurIPS2019](https://openreview.net/forum?id=ByMEAHrgLB)

### Bayesian-based

**AntBO: Towards Real-World Automated Antibody Design with Combinatorial Bayesian Optimisation**  
Khan, Asif, et al.  
[arXiv preprint(2022)](https://arxiv.org/abs/2201.12570)

### Pretrained-based

**Progen: Language modeling for protein generation**  
Madani, Ali, et al.  
[arXiv preprint arXiv:2004.03497 (2020)](https://arxiv.org/abs/2004.03497)

### RL-based

**Model-based reinforcement learning for biological sequence design**  
Angermueller, Christof, et al.  
[International conference on learning representations. 2019](https://openreview.net/forum?id=HklxbgBKvr&fileGuid=3xgr169o12oUrbxS)  

## Molecular Design Models

In consideration of learning more various of models for design, these are commended models from **Molecular Design** are helpful.

**CELLS: Cost-Effective Evolution in Latent Space for Goal-Directed Molecular Generation**  
Chen, Zhiyuan, et al.  
[arXiv preprint arXiv:2112.00905 (2021)](https://arxiv.org/abs/2112.00905)  

to be continued...
