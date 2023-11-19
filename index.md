# About Me
My name is Jiale Yan. I'm currently a P.h.D candidate at [Artic Lab](http://www.artic.iir.titech.ac.jp/wp/en/), Tokyo Institute of Technology, Japan, advised by Prof. [Masato Motomura, IEEE Fellow](http://www.artic.iir.titech.ac.jp/wp/en/people/prof-motomura/). Before joining Tokyo Tech, I received my master's degree from the Institute of Microelectronics, Tsinghua University, advised by Prof. [Shaojun Wei](https://www.ime.tsinghua.edu.cn/info/1015/1151.htm) and Prof. [Shouyi Yin](https://www.ime.tsinghua.edu.cn/info/1015/1018.htm). 


# Research Interests
Computer Architecture, Deep Learning, VLSI Design, Ray-tracing Computing, Reconfigurable Computing, Sparse Computing


# Education
Sep. 2021 - Now: **Tokyo Institute of Technology (Tokyo Tech)** (Ph.D. student)
* Department of Information and Communications Engineering

Sep. 2016 - Jul. 2019: **Tsinghua University (THU)** (Master)

* Dissertation: Research on Key Technologies of Energy Efficient and Reconfigurable Accelerator for Generative Neural Networks
  - Tsinghua Excellent Dissertation Award
* Master in Integrated Circuit Engineering 

Sep. 2012 - Jun. 2016: **Harbin Institute of Technology (HIT)** (Bachelor)

* B.S. in Electronic Science and Technology 

# Professional Experience
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


May. 2023 - Present **Graph Neural Network Accelerator**

* I am doing a high-performance GNN accelerator, which includes how to accelerate SpMM/GeMM computations. **It is an exciting research.**

## Algorithm [Sub-skill]


Sep. 2021 - Sep.2022: [**TT-MLP: Tensor Train Decomposition on Deep MLPs**](https://ieeexplore.ieee.org/document/10032168)
* This study aims to combine tensor-train decomposition with deep MLPs.

* In the evaluation, the proposed method showed a better trade-off than conventional TTD methods on ImageNet-1K and achieved a 0.56% higher inference accuracy with a 15.44% memory reduction on Cifar-10. 

* This study is my first try at deep learning algorithms, especially when doing a remote study under a serious Covid-19 situation.

* Results are published in IEEE CoolChip'23 (won the Best Poster) and IEEE Access'23.

May.2022 - April.2023: **Strong Lottery Tickets(SLT) on Graph neural networks(GNNs)**

*  The Strong Lottery Ticket Hypothesis (SLTH) demonstrates the existence of high-performing subnetworks within a randomly initialized model, discoverable through pruning a convolutional neural network (CNN) without any weight training. **This work extended SLTH from CNNs to GNNs**.

* This work utilizes Multicoated Supermasks (M-Sup), a scalar pruning mask method, and implements it in GNNs by proposing a strategy for setting its pruning thresholds adaptively. In the context of deep GNNs, this research uncovers the existence of untrained recurrent networks, which exhibit performance on par with their trained feed-forward counterparts. This paper also introduces the Multi-Stage Folding and Unshared Masks methods to expand the search space in terms of both architecture and parameters. 

* Through the evaluation of various datasets, including the Open Graph Benchmark (OGB), this work establishes a triple-win scenario for SLTH-based GNNs: by achieving high sparsity, competitive performance, and high memory efficiency with up to 98.7\% reduction, it demonstrates suitability for energy-efficient graph processing.

April.2023 - Prensent: **Graph-Transformer**

* The Graph-Transformer is a prominent topic in recent GNN research. I am currently conducting surveys on this subject.



Others

Sep. 2019: [**Ray-tracing Tech**](https://github.com/LouiValley/RayTracing-Tech)

* I'm collecting studies on ray tracing-related topics, in a GitHub project named [Ray Tracing Tech](https://github.com/LouiValley/RayTracing-Tech).  


Sep. 2021: [**Deep-Mlps family**](https://github.com/LouiValley/Deep-Mlps-family)

* I'm collecting deep MLPs in a GitHub project named [Deep-Mlps family](https://github.com/LouiValley/Deep-Mlps-family). It includes various deep-MLPs' with parameters and accuracy, including MLP-Mixer, Cycle-MLP, ResMLP and more.

# Selected Publications

* **[IEEE TCAD'18]** **Jiale. Yan**, Shouyi Yin, Fengbin Tu, Leibo Liu, Shaojun Wei "[Gna: Reconfigurable and efficient architecture for generative network acceleration](https://ieeexplore.ieee.org/document/8412607)," IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2018.
* **[Sci-China'18]** **Jiale. Yan**, Ying Zhang, Fengbin Tu, Jianxun Yang, Shixuan Zheng, Peng OuYang, Leibo Liu, Yuan Xie, Shaojun Wei, Shouyi Yin "[Research on low-power neural network computing accelerator](http://engine.scichina.com/publisher/scp/journal/SSI/49/3/10.1360/N112018-00282?slug=fulltext)," SCIENTIA SINICA Informationis, 2019.

* **[IEEE Access'23]** **Yan, J.**, Ando, K., Yu, J., & Motomura, M. (2023). [TT-MLP: Tensor Train Decomposition on Deep MLPs.](https://ieeexplore.ieee.org/document/10032168) IEEE Access.

* **[IEEE CoolChip'23]** **Yan, J.**, Motomura, M. (2023). [Optimized Deep MLP for Tensor Train-based Inference Engine](https://www.coolchips.org/2023/) IEEE Symposium on Low-Power and High-Speed Chips and Systems (COOL Chips 26). 
*This work won the Best Poster Award*

* **[ASP-DAC'23]** Yuta Nagahara, **Jiale Yan**, Kazushi Kawamura, Masato Motomura, Thiem Van Chu, “Sparse-Sparse Matrix Multiplication Accelerator on FPGA featuring Distribute-Merge Product Dataflow,” 29th Asia and South Pacific Design Automation Conference 2024  

* **[IEEE ICCE'23]** Yuta Nagahara, **Jiale Yan**, Kazushi Kawamura, Masato Motomura, Thiem Van Chu, “Efficient COO to CSR Conversion for Accelerating Sparse Matrix Processing on FPGA”, IEEE 42nd International Conference on Consumer Electronics 2024

* **[LoG'23]**  **Jiale Yan**, Hiroaki Ito, Ángel López García-Arias, Yasuyuki Okoshi, Hikari Otsuka, Kazushi Kawamura, Thiem Van Chu, Masato Motomura, “Multicoated and Folded Graph Neural Networks with Strong Lottery Tickets”, Learning on Graphs Conference 2023

Other papers are currently under review and have not been published here.

# Invited Talks

Reconfigurable and Efficient Architecture for Generative Network Acceleration
* ESWEEK (Embedded Systems Week) in Torino, Italy, Sept 30, 2018.  
* CASES(International Conference on Compilers, Architectures, and Synthesis for Embedded Systems) 2018
* IEEE Symposium on Low-Power and High-Speed Chips and Systems (COOL Chips 26). Tokyo, Japan, 2023


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
Address: Tokyo, Japan

Email: yan.j.ae@m.titech.ac.jp
