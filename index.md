# About Me
My name is Jiale Yan. I got my P.h.D degree at [Artic Lab](http://www.artic.iir.titech.ac.jp/wp/en/), Institute of Science Tokyo, Japan, advised by Prof. [Masato Motomura, IEEE Fellow](http://www.artic.iir.titech.ac.jp/wp/en/people/prof-motomura/). Before joining Science Tokyo, I received my master's degree from the Institute of Microelectronics, Tsinghua University, advised by Prof. [Shaojun Wei, IEEE Fellow](https://www.sic.tsinghua.edu.cn/info/1014/1789.htm) and Prof. [Shouyi Yin, IEEE Fellow](https://www.sic.tsinghua.edu.cn/info/1014/1777.htm). 


# Research Interests
Computer Architecture, Deep Learning, VLSI Design, Ray-tracing Computing, Reconfigurable Computing, Sparse Computing


# Education
Sep. 2021 - Dec. 2024: **Institute of Science Tokyo (Old name: Tokyo Institute of Technology)** (Ph.D.)
* Department of Information and Communications Engineering

Sep. 2016 - Jul. 2019: **Tsinghua University (THU)** (Master)

* Dissertation: Research on Key Technologies of Energy Efficient and Reconfigurable Accelerator for Generative Neural Networks
  - Tsinghua Excellent Dissertation Award
* Master in Integrated Circuit Engineering 

Sep. 2012 - Jun. 2016: **Harbin Institute of Technology (HIT)** (Bachelor)

* B.S. in Electronic Science and Technology 

# Professional Experience
Dec.2024 - April. 2025: **Science Tokyo, Researcher** 
* AI Researcher

Aug. 2019 - Aug. 2021: **HiSilicon, Senior IC Engineer**

* Ray-tracing graphic engine designer

# Project Experience

## Hardware [Main Skill]
Sep. 2016 - March. 2018 [**GNA: Reconfigurable and efficient architecture for generative network acceleration**](https://ieeexplore.ieee.org/document/8412607)

* This study aims to accelerate a generative network, which includes CONV layers, DeCONV layers and residual blocks. It achieves an energy efficiency of 2.05 TOPS/W with 61% higher PE utilization than traditional methods in generative network acceleration.

* GNA is my first study toward a deep learning accelerator.

* Published in TCAD (IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems), 2018 (First Author).


April. 2018 - Jul. 2019 [**Survey: Research on low-power neural network computing accelerator**](http://engine.scichina.com/publisher/scp/journal/SSI/49/3/10.1360/N112018-00282?slug=fulltext)

* This study aims to propose a reconfigurable hardware architecture to meet the flexibility requirements of a neural network.

* This study is rewarded as one of the excellent scientific papers in the field of electronic information (2021) by the Chinese Institute of Electronics. Publish in SCIENTIA SINICA Informationis, 2019 (First Author)

* It is collaborative work with Prof. [Yuan Xie](https://www.ece.ucsb.edu/~yuanxie/index.html).

Spet. 2022 - May. 2023 **Sparse-Sparse Matrix Multiplication Accelerator**

* This study proposes a Disperse-Merge Product (DMP) SpMSpM dataflow and a DMP-based SpMSpM accelerator (DMSA) architecture. The DMP divides the workload into balanced flows, generates partial matrices based on these flows, and merges the partial results in a parallel and pipelined manner. 

* Deployed on the Xilinx Zynq-UltraScale ZCU106, it achieves a speedup of 4.8X compared to the latest SpMSpM accelerators with similar resources on the same FPGA platform.

* Results are published on ASP-DAC'23, IEEE ICCE'23. We are also considering extending this work to further IEEE Trans journals!


May. 2023 - Aug. 2024 **Graph Neural Network Accelerator**

* I am doing a high-performance GNN accelerator, which includes how to accelerate SpMM/GeMM computations. **It is accepted by ISCA'25.**

## Algorithm [Sub-skill]


Sep. 2021 - Sep.2022: [**TT-MLP: Tensor Train Decomposition on Deep MLPs**](https://ieeexplore.ieee.org/document/10032168)
* This study aims to combine tensor-train decomposition with deep MLPs.

* In the evaluation, the proposed method showed a better trade-off than conventional TTD methods on ImageNet-1K and achieved a 0.56% higher inference accuracy with a 15.44% memory reduction on Cifar-10. 

* This study is my first try at deep learning algorithms, especially when doing a remote study under a serious Covid-19 situation.

* Results are published in IEEE CoolChip'23 (won the Best Poster) and IEEE Access'23.

May.2022 - April.2023: **Strong Lottery Tickets(SLT) on Graph neural networks(GNNs)**

*  The Strong Lottery Ticket Hypothesis (SLTH) demonstrates the existence of high-performing subnetworks within a randomly initialized model, discoverable through pruning a convolutional neural network (CNN) without any weight training. **This work extended SLTH from CNNs to GNNs**.

* This work utilizes Multicoated Supermasks (M-Sup), a scalar pruning mask method, and implements it in GNNs by proposing a strategy for setting its pruning thresholds adaptively. In the context of deep GNNs, this research uncovers the existence of untrained recurrent networks, which exhibit performance on par with their trained feed-forward counterparts. 

* Through the evaluation of various datasets, including the Open Graph Benchmark (OGB), this work establishes a triple-win scenario for SLTH-based GNNs: by achieving high sparsity, competitive performance, and high memory efficiency with up to **98.7% reduction**, it demonstrates suitability for energy-efficient graph processing.

April.2023 - Prensent: **Graph-Transformer**

* The Graph-Transformer is a prominent topic in recent GNN research. I am currently conducting surveys on this subject.



Others

Sep. 2019: [**Ray-tracing Tech**](https://github.com/LouiValley/RayTracing-Tech)

* I'm collecting studies on ray tracing-related topics, in a GitHub project named [Ray Tracing Tech](https://github.com/LouiValley/RayTracing-Tech).  


Sep. 2021: [**Deep-Mlps family**](https://github.com/LouiValley/Deep-Mlps-family)

* I'm collecting deep MLPs in a GitHub project named [Deep-Mlps family](https://github.com/LouiValley/Deep-Mlps-family). It includes various deep-MLPs' with parameters and accuracy, including MLP-Mixer, Cycle-MLP, ResMLP and more.

# Selected Publications

As the first author.

* **[ISCA'25]** **Jiale. Yan**, Hiroaki Ito, Yuta Nagahara, Kazushi Kawamura, Masato Motomura, Thiem Van Chu, Daichi Fujiki. "BingoGCN: Towards Scalable and Efficient GNN Acceleration with  Fine-Grained Partitioning and SLT", the 52nd International Symposium on Computer Architecture (ISCA 2025).

* **[IEEE TCAD'18]** **Jiale. Yan**, Shouyi Yin, Fengbin Tu, Leibo Liu, Shaojun Wei "[Gna: Reconfigurable and efficient architecture for generative network acceleration](https://ieeexplore.ieee.org/document/8412607)," IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2018.

* **[PMLR'24]**  **Jiale Yan**, Hiroaki Ito, Ángel López García-Arias, Yasuyuki Okoshi, Hikari Otsuka, Kazushi Kawamura, Thiem Van Chu, Masato Motomura, "Multicoated and folded graph neural networks with strong lottery tickets." Learning on Graphs Conference. PMLR, 2024.

* **[Sci-China'18, Best Paper Award]** **Jiale. Yan**, Ying Zhang, Fengbin Tu, Jianxun Yang, Shixuan Zheng, Peng OuYang, Leibo Liu, Yuan Xie, Shaojun Wei, Shouyi Yin "[Research on low-power neural network computing accelerator](http://engine.scichina.com/publisher/scp/journal/SSI/49/3/10.1360/N112018-00282?slug=fulltext)," SCIENTIA SINICA Informationis, 2019. **This work won the Best Paper Award**

* **[IEEE CoolChip'23, Best Poster Award]** **Yan, J.**, Motomura, M. (2023). [Optimized Deep MLP for Tensor Train-based Inference Engine](https://www.coolchips.org/2023/) IEEE Symposium on Low-Power and High-Speed Chips and Systems (COOL Chips 26). 
**This work won the Best Poster Award**


* **[IEEE Access'23]** **Yan, J.**, Ando, K., Yu, J., & Motomura, M. (2023). [TT-MLP: Tensor Train Decomposition on Deep MLPs.](https://ieeexplore.ieee.org/document/10032168) IEEE Access.

* **[RCCS-IS6]** **Jiale Yan**, Hiroaki Ito, Masato Motomura, etc. "Efficient Co-Design of Hardware and Algorithms for SLT-based Graph Neural Networks, 6th R-CCS International Symposium.


Other papers, as the second author.

* **[IEEE TVLSI'25]** Yuta Nagahara, **Jiale Yan**, Kazushi Kawamura, Daichi Fujiki, Masato Motomura, Thiem Van Chu, “DMSA: An Efficient Architecture for Sparse-Sparse Matrix Multiplication Based on Distribute-Merge Product Dataflow,” IEEE Transactions on Very Large Scale Integration (VLSI) Systems, 2025.

* **[IEEE CoolChip'25]** Hiroaki Ito, **Jiale Yan**, Kazushi Kawamura, Thiem Van Chu, Masato Motomura, Daichi Fujiki, "TTF-GNN: Memory-Efficient GNNs via Tensor Train Decomposition and Network Folding", IEEE CoolChip, 2025.

* **[TMLR'25]** Hiroaki Ito, **Jiale Yan**, Hikari Otsuka, Kazushi Kawamura, Masato Motomura, Thiem Van Chu, Daichi Fujiki, “Uncovering Strong Lottery Tickets in Graph Transformers: A Path to Memory Efficient and Robust Graph Learning”, Transactions on Machine Learning Research, 2025.

* **[RCCS-IS6'24]** Hiroaki Ito, **Jiale Yan**, Masato Motomura, etc. "Memory-efficient Methods for Graph Transformer Using Strong Lottery Tickets Hypothesis", 6th R-CCS International Symposium (RCCS-IS6). 
Other papers are currently under review and have not been published here.

* **[ASP-DAC'23]** Yuta Nagahara, **Jiale Yan**, Kazushi Kawamura, Masato Motomura, Thiem Van Chu, “Sparse-Sparse Matrix Multiplication Accelerator on FPGA featuring Distribute-Merge Product Dataflow,” 29th Asia and South Pacific Design Automation Conference 2024  

* **[IEEE ICCE'23]** Yuta Nagahara, **Jiale Yan**, Kazushi Kawamura, Masato Motomura, Thiem Van Chu, “Efficient COO to CSR Conversion for Accelerating Sparse Matrix Processing on FPGA”, IEEE 42nd International Conference on Consumer Electronics 2024

* **[IBISML'25]** 伊藤宏朗, **嚴佳樂**, 大塚光莉, 川村一志, 本村真人, ティエム ヴァン チュ, 藤木大地, グラフトランスフォーマーにおける強い宝くじの発見, 第56回 IBISML研究会 2025.

* **[VLD'23]** 永原雄大, **Jiale Yan**, 川村一志, 本村真人, ThiemVan Chu, 分散マージ乗算手法に基づく疎行列疎行列積アクセラレータ, VLSI設計技術研究会（VLD）2024.




# Invited Talks

Reconfigurable and Efficient Architecture for Generative Network Acceleration
* "GNA: Reconfigurable and efficient architecture for generative network acceleration", ESWEEK (Embedded Systems Week) in Torino, Italy, Sept 30, 2018.  
* "GNA: Reconfigurable and efficient architecture for generative network acceleration", CASES(International Conference on Compilers, Architectures, and Synthesis for Embedded Systems) 2018
* "Optimized Deep MLP for Tensor Train-based Inference Engine", IEEE Symposium on Low-Power and High-Speed Chips and Systems (COOL Chips 26). Tokyo, Japan, 2023
* "Multicoated and Folded Graph Neural Networks with Strong Lottery Tickets", Learning on Graph 2023 (Shanghai Local Meeting), Shanghai, China, Nov.29, 2023 


# Selected Honors and Awards
* JASSO Honors Scholarship, Tsubame Scholarship, Tokyo Tech 2021 - 2023
* Second Prize, (Team Leader) China Postgraduate Electronic Design Competition, 2017
* Third Prize,  (Team Leader) National Postgraduate Mathematical Contest in Modeling, 2017
* Outstanding undergraduate graduation thesis at Harbin Institute of Technology, 2016
* Provincial Excellent College Graduate, 2016 
* Third Prize, National Competition of Transport Science and Technology, 2015
* Third Prize, National Undergraduate English Competition, 2015
* The Honorable Mention, Mathematical Contest In Modeling Certificate of Achievement, 2015
* First Prize(Provincial award), Competition of National Mathematical Modeling Competition, 2014
* Third Prize, National Undergraduate Mathematics Competition, 2013
* First Prize Scholarship (4 times), Harbin Institute of Technology University’s scholarship, 2013, 2014, 2015, 2016 



# Contact

Email: yjl16@tsinghua.org.cn
