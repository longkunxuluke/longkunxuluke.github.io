---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## About *(Updated: 02-Oct-2024)*

My name is Longkun Xu, people also call me Luke. 

I earned my PhD in _computational chemistry_ at the _Australian National University_ in 2022,
under the supervision of _Prof. Michelle Coote_. After that I joined _Samsung Research China-Beijing (SRC-B)_
and worked as an research engineer. In July 2024 I joined _Dongyangguang (HEC) New Energy Research
Institute_ as a senior researcher. My research interests focus on method development of computational
chemistry and computational materials, AI for Science and Science for AI, HPC and quantum computing, and their applications
in many industrial scenarios including battery, display, semiconductor, capacitor, aluminum foil, fluorine
chemicals, and BMS algorithms. I have published 10+ papers in journals including _JACS, Nature
Communication, JCTC, JPCL, JPCC, JPCA_. My research was highlighted in _AI for Science Global Outlook
2023 Edition, EurekAlert!, PHYS.ORG, Chemistry in Australia_. I server as a reviewer for AI conferences
_ICML(2023, 2024), NeurIPS(2022, 2023)_ and chemical journals including _JCTC_ and _JPCA_.

You can find my blog posts [here](https://longkunxuluke.github.io/year-archive/), which are some tutorials used to answer questions I have been frequently asked, feel free to let me know your comments and questions.You can contact me via longkunx@gmail.com

![WO](/images/WO-2.jpg)

## Education and Employment

[07/2024]-[Now], Senior Researcher, Dongyangguang (HEC) New Energy Research Institute, Dongguan, China

[12/2021]-[07/2024], Engineer (05/2022 - 07/2024) <- Intern (12/2021 - 05/2022), Samsung Research China-Beijing (SRC-B), Beijing, China

[10/2018]-[04/2022], PhD student (Computational Chemistry), Australian National University, Canberra, Australia

[07/2018]-[09/2018], Assistant Editor, MDPI publisher, Beijing, China

[09/2015]-[07/2018], Master's degree (Applied Chemistry), Sichuan University, Chengdu, China

[09/2011]-[07/2015], Bachelor's degree (Material Chemistry), Qingdao Agricultural University, Qingdao, China

## Research Interests

More introductions to my current and previous research projects can be found in my [PhD thesis](https://web.archive.org/web/20220422085348id_/https://openresearch-repository.anu.edu.au/bitstream/1885/261844/1/LongkunXU_Thesis_2022.pdf) and our [book chapter](https://www.elsevier.com/books/annual-reports-on-computational-chemistry/dixon/978-0-323-99092-9).

Following are some related keywords often appeared in my papers:

- *Computational Chemistry*: quantum chemistry, MD simulation, multi-scale calculation, ...
- *AI for Science*: machine learning potentials, generative AI for molecular generation, ...
- *Quantum Computating and HPC*: quantum computing for quantum chemistry, HPC, ...
- *Molecular and Materials Science*:
  - *Solvation*: electrolyte solution, ionic liquids, electrostatic and polarization interactions, external electric field, ...
  - *Materials*: battery, OLED, semiconductors, capacitor, aluminum foil, fluorine chemicals...
  - *Biology*: drug, peptide, protein, synthetic accessibility, retrosynthesis, ...
- *BMS Algorithms*
  
*Research Value*: I think a good computational method development should be theoretically fundamental (use math and physics to solve issues, not by tuning parameters), easy to use (black-box, automatic and open-source) and generally effective for most chemical systems (versatile). A good calculational applications should aim to offer new physical insights and guide the design of products. 

I am particularly interested in the following topics:

### 1. Materials Images Segmentation

Image segmentation methods can make huge contributions in studying materials science. A large number of features can be extracted from segmented materials images to correlate with target materials properties for better and more efficient materials design. At HEC, I develop a method using SAM based image segmentation methods for analysing SEM images of battery cathode materials, from segmented images over 260 relevant features of particles can be extracted to predict properties of cathode materials. I have built a web app associated with the algorithm, using flask and html techniques. The web app has been successfully used by experimental researchers at HEC.

![sam4sem](/images/sam4sem.png)

### 2. Data-efficient AI4S

My interests in *AI4S* include machine learning potential (with long-range interactions and field effects), automatic differentiation algorithms, deep generative models, graph theory, and their applications into interface modelling, enhanced sampling method, force field optimization, molecular generation, material property prediction and chemical reaction networks, etc.

Particularly I am interested in developing data efficient deep learning models, as data shortage is one central challenge of AI4S. With my co-workers, we propose two strategies: stability indicated sampling (SIS) and using multi-fidelity training data.

For the first one, we developed SIS-MLPMD, a new method to sample training data of machine learning potentials based
on temperature stability in MD simulation. Applied the method to study the long-time reactive dynamics of
SEI formation process at the interface of Lithium metal batteries, see [2023 JPCC](https://pubs.acs.org/doi/10.1021/acs.jpcc.3c05522). 

For the second one, we developed a method to use multi-fidelity training data of JAX-ReaxFF and DFT to reduce the
computational costs in training SchNet and MACE based machine learning potentials. The method was
employed to study a diverse range of properties of 2D semiconductor materials, see [2024 JPCL](https://pubs.acs.org/doi/abs/10.1021/acs.jpclett.3c03080).

![data_efficient_ai4s](/images/ai4s.png)

### 3. Computational Solvation Science
### 3.1. Structures and properties of ionic liquids under external electric field;
Structures and properties of ionic liquids under external electric field is closely related with the design of ionic liquids based electrochemical devices. In [2021JACS](https://pubs.acs.org/doi/full/10.1021/jacs.1c06385), we analysed details of this topic using both computational and experimental techniques. A plateau in the open circuit potential (OCP) was observed upon application of an external electric field and its removal, which persisted in some ionic liquids over several hours. We propose this method as an easy and straightforward technique to characterize and compare the degree of order of different ionic liquids. Several parameters were also calculated using the trajectory of the polarizable molecular dynamic simulations to characterise the ordering of different ionic liquids. By considering ion dipole projection, the diffusion coefficient of the cation and its volume, a good correlation was found between the measured OCP and the calculated quantities for different ionic liquids, which offers a way to choose suitable ionic liquids for electrochemical applications.

![OCP](/images/publication5-toc.PNG.jpg)

### 3.2. Electrostatic catalysis in unusual solvent environment; 

Achieving electrostatic catalysis in polar solvent is highly desirable, especially in some unusual and complex solvent environment where the mean field approximation is invalid. For example, under some conditions, the normal solvent networks can be broken and the ordered solvent is formed, this is a very interesting phenomenon. In [2020JACS](https://pubs.acs.org/doi/abs/10.1021/jacs.0c05643) working with the group of [Prof.Ekaterina I Pas](https://mccg.erc.monash.edu/) employing classical molecular dynamic simulations with the Drude oscillator-based polarizable force field, quantum chemical calculations, and ONIOM (DFT:semi-empirical) multiscale calculations, we investiagted the potential of ordered solvent and ionic liquids in catalysing chemical reactions. Bubble surface is another unique electrostatic environment where high concentration of excess OH- exist, in [2020 Nat. Commun.](https://www.nature.com/articles/s41467-020-20186-0), we use GFN-XTB method based MD simulation and ONIOM(CCSD(T)/CBS:DHDFT) methods to help experimental collaborators ([Dr Simone Ciampi group](https://research.curtin.edu.au/supervisor/dr-simone-ciampi/)) prove that the high concentration of OH- can promote the oxidation potential of itself, which might be useful for further works in the fields of electrocatalysis and electrosynthesis. 

![Ordered solvent and ionic liquids](/images/TOC-300dpi.png)

### 3.3. Improving the accuracy of implicit solvent models; 

The implicit solvent models together with quantum chemical methods is the main strategy in modelling solution-phase properties and reactions. Thus, its accuracy in producing the solvation free energies is very important. In [2019JPCA](https://pubs.acs.org/doi/abs/10.1021/acs.jpca.9b04920), we disccussed different methods to improve the SMD solvation free energies and associated pKa values. In [2019JCTC](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.9b00888), we presented the optimal electrostatic scaling factor (ESF) values in a wide range of solvents using PCM-UAHF and PCM-UAKS methods, we proposed the mixed-ESF method to improve the accuracy in calculating solution-phase properties.

![Improving the accuracy of implicit solvent models](/images/2019JCTC.png)

### 3.4. Non-equilibrium solvation and solvent reorganization; 

Non-equilibrium solvation is an important conecpt originaly proposed by Prof. Rudolph A. Marcus in his well-known Marcus theory. It is a key factor in modelling the superfast processes in solution phase, for example, electron transfer and electronic excitation. Prof. Xiang-Yuan Li and co-workers have been working on implementing the constrained-equilibrium method in the non-equilibrium solvation theory. In [2017CPL](https://www.sciencedirect.com/science/article/pii/S000926141730427X), we derived the expressions of non-equilibrium solvation free energy within the framework of analytical Onsager model and applied it to model charge-transfer excited state. The theory was developed and implemented in the local Q-Chem program, see [2017PCCP](https://pubs.rsc.org/lv/content/articlehtml/2017/cp/c7cp05673g), [2018 PCCP HOT article](https://pubs.rsc.org/lv/content/articlelanding/2018/cp/c8cp00930a/unauth#!divAbstract) and [2017CP](https://www.sciencedirect.com/science/article/pii/S0301010417301398).

![Non-equilibrium solvation and solvent reorganization](/images/2017CPL.png)

*The full list of my publications can be found from the google scholar in the left sidebar.*

## Peer Review Service

Reviewers for the following journals and conferences: *ICML 2024 workshop (AI4Science, SPIGM), NeurIPS2023 workshop (AI4Science, GenBio), ICML
2023 workshop (SPIGM), NeurIPS2022 workshop (AI4Science), JCTC, JPCA*

## Talks and Posters

[12/2020], [ASIL9](https://www.monash.edu/asil9), [poster](https://github.com/longkunxuluke/ordered_solvent/blob/master/ASIL9-Xu.pdf) and [video](https://www.youtube.com/watch?v=9JgCmZJXgn0), Zoom

[10/2019], [APATCC2019](https://www.apatcc2019.com/), poster, Sydney, Australia

[06/2017], [ncqc2017](http://www1.chemsoc.org.cn/meeting/home/info.asp?id=202), poster, Dalian, China

## Awards and Fellowships

Samsung Excellent Proposal Award (2023)

Postgraduate Research Support (2020)

HDR Fee Remission Merit Scholarship (2018-2021)

ANU PhD Scholarship (International) (2018-2021)

Second Class Scholarship for Gruduate Student (2015-2018)

Hailier Scholarship for Outstanding Students (2013)

## Teaching Service

Mentored Interns: 
- Kehan Wang (2022-2023 @Samsung, Now: Researcher @China Telecom)
- Mingwei Ge (2022 @Samsung, Now: PhD student @Yale)

Teaching assistant for undergraduate course *Physical Chemistry* (2016)

## News

[8/2023] Our [2023 JPCC](https://pubs.acs.org/doi/abs/10.1021/acs.jpcc.3c05522) was reported by *AI for Science Global Outlook 2023 Edition*, see page 179 in [here](https://image.deeptechchina.com/2023%E7%89%88%E3%80%8A%E7%A7%91%E5%AD%A6%E6%99%BA%E8%83%BD%28AI4S%29%E5%85%A8%E7%90%83%E5%8F%91%E5%B1%95%E8%A7%82%E5%AF%9F%E4%B8%8E%E5%B1%95%E6%9C%9B%E3%80%8B.pdf)

[12/2021] Our [2021 JACS](https://pubs.acs.org/doi/abs/10.1021/jacs.1c06385) was reported by *Chemistry in Australia*, see page 15 in [here](https://chemaust.raci.org.au/sites/default/files/pdf/2021/CiA_Dec21_web.pdf)

[12/2020] Our [2020 Nat. Commun.](https://www.nature.com/articles/s41467-020-20186-0) was reported by several news platforms including [EurekAlert!](https://www.eurekalert.org/pub_releases/2020-12/cu-tbo121020.php), [PHYS.ORG](https://phys.org/news/2020-12-tiny-electrodes-key-chemical.html) and [Chemistry in Australia](https://chemaust.raci.org.au/article/march-may-2021/electrified-bubbles.html).

[11/2020] Our [2020 JACS paper](https://pubs.acs.org/doi/abs/10.1021/jacs.0c05643) was reported by *Chemistry in Australia*, see page 14 in [here](https://chemaust.raci.org.au/sites/default/files/pdf/2020/CiA_Sept_Nov2020.pdf)








