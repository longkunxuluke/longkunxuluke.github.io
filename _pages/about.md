---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## About

My name is Longkun Xu, people also call me Luke. 

I am currently a computational materials researcher intern at SAIT China lab, Samsung Electronics, where I am working on the intersection of AI, HPC and computational material science to design materials used in Samsung products, e.g., battery, display and semiconductors materials. Previously I was a PhD student at the Australian National University.

I have 7 years experience (2015-2022) with computational chemistry and also have hands-on experience with machine learning and academic publishing industry. I am familiar with Python, SQL, R, Julia, web data, high performance computing, neural network potential, etc.

I am interested in any job using computational science, AI and HPC to solve real-world pratical problems within and beyond the domain of chemistry, e.g., battery and material design, drug discovery and retrosynthesis, etc. Here's my [CV](https://github.com/longkunxuluke/longkunxuluke.github.io/blob/master/CV_LongkunXU.pdf) and [简历](https://github.com/longkunxuluke/longkunxuluke.github.io/blob/master/%E7%AE%80%E5%8E%86_%E5%BE%90%E9%BE%99%E5%9D%A4.pdf).

You can find my blog posts [here](https://longkunxuluke.github.io/year-archive/), which are some tutorials used to answer questions I have been frequently asked, feel free to let me know your comments and questions.You can contact me via longkunx@gmail.com

![WO](/images/WO-2.jpg)

## Education and Employment

[05/2022]-[Current], Engineer, [SAIT China Lab](https://www.sait.samsung.co.kr/saithome/about/labs.do), Samsung Electronics, Beijing, China

[12/2021]-[05/2022], Intern, [SAIT China Lab](https://www.sait.samsung.co.kr/saithome/about/labs.do), Samsung Electronics, Beijing, China

[10/2018]-[10/2021], PhD student (Chemistry), Supervisor: [Prof. Michelle Coote](https://cootelab.com/), Australian National University, Canberra, Australia

[07/2018]-[09/2018], Assistant Editor ([Materials](https://www.mdpi.com/journal/materials), [High-Throughput](https://www.mdpi.com/journal/high-throughput)), MDPI publisher, Beijing, China

[09/2015]-[07/2018], Master's degree (Applied Chemistry), Supervisor: [Prof. Xiang-Yuan Li](http://ccg.scu.edu.cn/a/default.html), Sichuan University, Chengdu, China

[09/2011]-[07/2015], Bachelor's degree (Material Chemistry), Qingdao Agricultural University, Qingdao, China

## Research Interests

My research is mainly about the following keywords: computational chemistry, AI, HPC, solvation, battery and materials design, drug discovery and retrosynthesis. 

I think a good computational method development should be theoretically simple (elegant), easy to use (black-box & automatic) and generally effective for most systems (versatile). A good calculational applications should aim to offer new physical insights and guide the design of products. 

I am particularly interested in the following topics:

### 1. AI for Materials
After joining Samsung, my research focus was changed to *AI for Materials*. I am working on the intersection of AI, HPC and computational material science to design materials used in Samsung products, e.g., battery, display and semiconductors materials.

### 2. Computational Solvation Science
### 2.1. Structures and properties of ionic liquids under external electric field;
Structures and properties of ionic liquids under external electric field is closely related with the design of ionic liquids based electrochemical devices. In [2021JACS](https://pubs.acs.org/doi/full/10.1021/jacs.1c06385), we analysed details of this topic using both computational and experimental techniques. A plateau in the open circuit potential (OCP) was observed upon application of an external electric field and its removal, which persisted in some ionic liquids over several hours. We propose this method as an easy and straightforward technique to characterize and compare the degree of order of different ionic liquids. Several parameters were also calculated using the trajectory of the polarizable molecular dynamic simulations to characterise the ordering of different ionic liquids. By considering ion dipole projection, the diffusion coefficient of the cation and its volume, a good correlation was found between the measured OCP and the calculated quantities for different ionic liquids, which offers a way to choose suitable ionic liquids for electrochemical applications.

![OCP](/images/publication5-toc.PNG.jpg)

### 2.2. Electrostatic catalysis in unusual solvent environment; 

Achieving electrostatic catalysis in polar solvent is highly desirable, especially in some unusual and complex solvent environment where the mean field approximation is invalid. For example, under some conditions, the normal solvent networks can be broken and the ordered solvent is formed, this is a very interesting phenomenon. In [2020JACS](https://pubs.acs.org/doi/abs/10.1021/jacs.0c05643) working with the group of [Prof.Ekaterina I Pas](https://mccg.erc.monash.edu/) employing classical molecular dynamic simulations with the Drude oscillator-based polarizable force field, quantum chemical calculations, and ONIOM (DFT:semi-empirical) multiscale calculations, we investiagted the potential of ordered solvent and ionic liquids in catalysing chemical reactions. Bubble surface is another unique electrostatic environment where high concentration of excess OH- exist, in [2020 Nat. Commun.](https://www.nature.com/articles/s41467-020-20186-0), we use GFN-XTB method based MD simulation and ONIOM(CCSD(T)/CBS:DHDFT) methods to help experimental collaborators ([Dr Simone Ciampi group](https://research.curtin.edu.au/supervisor/dr-simone-ciampi/)) prove that the high concentration of OH- can promote the oxidation potential of itself, which might be useful for further works in the fields of electrocatalysis and electrosynthesis. 

![Ordered solvent and ionic liquids](/images/TOC-300dpi.png)

### 2.3. Improving the accuracy of implicit solvent models; 

The implicit solvent models together with quantum chemical methods is the main strategy in modelling solution-phase properties and reactions. Thus, its accuracy in producing the solvation free energies is very important. In [2019JPCA](https://pubs.acs.org/doi/abs/10.1021/acs.jpca.9b04920), we disccussed different methods to improve the SMD solvation free energies and associated pKa values. In [2019JCTC](https://pubs.acs.org/doi/abs/10.1021/acs.jctc.9b00888), we presented the optimal electrostatic scaling factor (ESF) values in a wide range of solvents using PCM-UAHF and PCM-UAKS methods, we proposed the mixed-ESF method to improve the accuracy in calculating solution-phase properties.

![Improving the accuracy of implicit solvent models](/images/2019JCTC.png)

### 2.4. Non-equilibrium solvation and solvent reorganization; 

Non-equilibrium solvation is an important conecpt originaly proposed by Prof. Rudolph A. Marcus in his well-known Marcus theory. It is a key factor in modelling the superfast processes in solution phase, for example, electron transfer and electronic excitation. Prof. Xiang-Yuan Li and co-workers have been working on implementing the constrained-equilibrium method in the non-equilibrium solvation theory. In [2017CPL](https://www.sciencedirect.com/science/article/pii/S000926141730427X), we derived the expressions of non-equilibrium solvation free energy within the framework of analytical Onsager model and applied it to model charge-transfer excited state. The theory was developed and implemented in the local Q-Chem program, see [2017PCCP](https://pubs.rsc.org/lv/content/articlehtml/2017/cp/c7cp05673g), [2018 PCCP HOT article](https://pubs.rsc.org/lv/content/articlelanding/2018/cp/c8cp00930a/unauth#!divAbstract) and [2017CP](https://www.sciencedirect.com/science/article/pii/S0301010417301398).

![Non-equilibrium solvation and solvent reorganization](/images/2017CPL.png)

### The full list of my publications can be found from the google scholar in the left sidebar.

## Peer Review

Reviewers for the following journals: [JPCA](https://pubs.acs.org/journal/jpcafh)

## Talks and Posters

[12/2020], [ASIL9](https://www.monash.edu/asil9), [poster](https://github.com/longkunxuluke/ordered_solvent/blob/master/ASIL9-Xu.pdf) and [video](https://www.youtube.com/watch?v=9JgCmZJXgn0), Zoom

[10/2019], [APATCC2019](https://www.apatcc2019.com/), poster, Sydney, Australia

[06/2017], [ncqc2017](http://www1.chemsoc.org.cn/meeting/home/info.asp?id=202), poster, Dalian, China

## Awards and Fellowships

Postgraduate Research Support (2020)

HDR Fee Remission Merit Scholarship (2018-2021)

ANU PhD Scholarship (International) (2018-2021)

Second Class Scholarship for Gruduate Student (2015-2018)

Hailier Scholarship for Outstanding Students (2013)

## Teaching Service

Teaching assistant for undergraduate course *Physical Chemistry* (2016)

## News

[12/2021] Our [2021 JACS](https://pubs.acs.org/doi/abs/10.1021/jacs.1c06385) was reported by *Chemistry in Australia*, see page 15 in [here](https://chemaust.raci.org.au/sites/default/files/pdf/2021/CiA_Dec21_web.pdf)

[12/2020] Our [2020 Nat. Commun.](https://www.nature.com/articles/s41467-020-20186-0) was reported by several news platforms including [EurekAlert!](https://www.eurekalert.org/pub_releases/2020-12/cu-tbo121020.php), [PHYS.ORG](https://phys.org/news/2020-12-tiny-electrodes-key-chemical.html) and [Chemistry in Australia](https://chemaust.raci.org.au/article/march-may-2021/electrified-bubbles.html).

[11/2020] Our [2020 JACS paper](https://pubs.acs.org/doi/abs/10.1021/jacs.0c05643) was reported by *Chemistry in Australia*, see page 14 in [here](https://chemaust.raci.org.au/sites/default/files/pdf/2020/CiA_Sept_Nov2020.pdf)




