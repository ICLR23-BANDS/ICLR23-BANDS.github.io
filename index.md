---
layout: default
---


# Overview

| **Date** | May 5, 2023 (9 am - 18:00 pm US Eastern Daylight Time) |
| **Link** | [https://iclr.cc/virtual/2023/workshop/12825](https://iclr.cc/virtual/2023/workshop/12825) (ICLR registration required)
| **Location** | *Virtually*
| **Schedule** | [Click here](./schedule)


Backdoor attacks aim to cause consistent misclassification of any input by adding a specific pattern called a trigger. Unlike adversarial attacks requiring generating perturbations on the fly to induce misclassification for one single input, backdoor attacks have prompt effects by simply applying a pre-chosen trigger. Recent studies have shown the feasibility of launching backdoor attacks in various domains, such as computer vision (CV), natural language processing (NLP), federated learning (FL), etc. As backdoor attacks are mostly carried out through data poisoning (i.e., adding malicious inputs to training data), it raises major concerns for many publicly available pre-trained models. Companies relying on user data to construct their machine learning models are also susceptible to backdoor attacks.

<!-- Defending against backdoor attacks has sparked multiple lines of research, including detecting inputs with backdoor triggers, determining whether a model has hidden backdoors, eliminating potential backdoors inside a model, etc. Many defense techniques are effective against some particular types of backdoor attacks. However, with increasingly emerging diverse backdoors, the defense performance of existing work tends to be limited. Most defense techniques and attacks are developed for the computer vision domain. It is yet to explore the connection between attacks and defenses among different domains. -->

This workshop, **B**ackdoor **A**ttacks a**N**d **D**efen**S**es in Machine Learning (**BANDS**), aims to bring together researchers from government, academia, and industry that share a common interest in exploring and building more secure machine learning models against backdoor attacks. 

<!-- With the wide adoption of large pre-trained models in real-world applications, any injected malicious behaviors, such as backdoors in those models, are particularly concerning. It is, therefore, particularly important to gather researchers in the area and expand the community to improve the security of machine learning. -->

<!-- This workshop aims to answer the following questions:
- What other types of backdoor attacks can we find in CV/NLP/FL machine learning models?
- Can we launch backdoor attacks in other domains, such as binary analysis tools, network intrusion detection systems, reinforcement learning, etc.?
- What are the similarities and differences of backdoor attacks in various tasks?
- How can we measure the stealthiness of backdoor attacks in different domains? What are the costs and practicality of launching backdoor attacks in the real world?
- What is the performance of existing defense techniques in studied domains? Can they be adapted to other domains?
- How can we develop a general defense method against a variety of backdoor attacks and even unseen attacks?
- Are there other forms of defenses that are practical in the real world? -->

# Featured Speakers
Speakers are in alphabetical order by last name.

|<img src="./assets/images/chen.png" alt="Pin-Yu Chen" class="speaker-image"/>|<img src="./assets/images/guo.jpg" alt="Wenbo Guo" class="speaker-image"/>|<img src="./assets/images/amir.jpeg" alt="Amir Houmansadr" class="speaker-image"/>|
|[Pin-Yu Chen](https://sites.google.com/site/pinyuchenpage/home)<br />IBM Research AI|[Wenbo Guo](https://henrygwb.github.io/)<br />UC Berkeley|[Amir Houmansadr](https://people.cs.umass.edu/~amir/)<br />University of Massachusetts<br />|
|<img src="./assets/images/jia.jpg" alt="Ruoxi Jia" class="speaker-image"/>|<img src="./assets/images/bo_li.jpg" alt="Bo Li" class="speaker-image"/>|<img src="./assets/images/Mahoney.jpeg" alt="Michael Mahoney" class="speaker-image"/>|
[Ruoxi Jia](https://ruoxijia.info/)<br />Virginia Tech<br />|[Bo Li](https://aisecure.github.io/)<br />UIUC|[Michael Mahoney](https://www.stat.berkeley.edu/~mmahoney/)<br />UC Berkeley and ICSI|
|<img src="./assets/images/Shmatikov.jpeg" alt="Vitaly Shmatikov" class="speaker-image"/>|<img src="./assets/images/zhang.jpg" alt="Yang Zhang" class="speaker-image"/>|<img src="./assets/images/ben.jpg" alt="Ben Y. Zhao" class="speaker-image"/>|
|[Vitaly Shmatikov](https://www.cs.cornell.edu/~shmat/)<br />Cornell Tech<br />|[Yang Zhang](https://yangzhangalmo.github.io/)<br />CISPA|[Ben Y. Zhao](https://people.cs.uchicago.edu/~ravenben/)<br />UChicago<br />|

# Panelists
Panelists are in alphabetical order by last name.

|<img src="./assets/images/pin-yu.jpg" alt="Pin-Yu Chen" class="speaker-image"/>|<img src="./assets/images/jia.jpg" alt="Ruoxi Jia" class="speaker-image"/>|<img src="./assets/images/bo_li.jpg" alt="Bo Li" class="speaker-image"/>|
|[Pin-Yu Chen](https://sites.google.com/site/pinyuchenpage/home)<br />IBM Research AI|[Ruoxi Jia](https://ruoxijia.info/)<br />Virginia Tech<br />|[Bo Li](https://aisecure.github.io/)<br />UIUC|
|<img src="./assets/images/Shmatikov.jpeg" alt="Vitaly Shmatikov" class="speaker-image"/>|<img src="./assets/images/ben.jpg" alt="Ben Y. Zhao" class="speaker-image"/>|
|[Vitaly Shmatikov](https://www.cs.cornell.edu/~shmat/)<br />Cornell Tech<br />|[Ben Y. Zhao](https://people.cs.uchicago.edu/~ravenben/)<br />UChicago<br />|


# Best Paper Award
- <b>[How to Backdoor Diffusion Models?](https://openreview.net/pdf?id=iIg0_loMVm)</b> <br /> Sheng-Yen Chou (National Tsing Hua University & The Chinese University of Hong Kong), Pin-Yu Chen (IBM Research), Tsung-Yi Ho (The Chinese University of Hong Kong)


# Organizers

|<img src="./assets/images/tao.jpg" alt="Guanhong Tao" width="225"/>|<img src="./assets/images/kaiyuan.jpg" alt="Kaiyuan Zhang" width="225"/>|<img src="./assets/images/Shan.jpg" alt="Shawn Shan" width="225"/>|<img src="./assets/images/ewenger.jpg" alt="Emily Wenger" width="225"/>|
|[Guanhong Tao](https://www.cs.purdue.edu/homes/taog/)<br />Purdue University|[Kaiyuan Zhang](https://kaiyuanzhang.com/)<br />Purdue University|[Shawn Shan](https://www.shawnshan.com/)<br />University of Chicago|[Emily Wenger](https://www.emilywenger.com/)<br />University of Chicago|
|<img src="./assets/images/zhu.jpg" alt="Rui Zhu" width="225"/>|<img src="./assets/images/Eugene.jpg" alt="Eugene Bagdasaryan" width="225"/>|<img src="./assets/images/Manoj.jpg" alt="Naren Sarayu Manoj" width="225"/>|<img src="./assets/images/taylor.jpg" alt="Taylor Kulp-McDowall" width="225"/>|
|[Rui Zhu](https://nextjs-notion-starter-kit-sigma-three.vercel.app/)<br />Indiana University|[Eugene Bagdasaryan](https://www.cs.cornell.edu/~eugene/)<br />Cornell Tech|[Naren Sarayu Manoj](https://www.nsmanoj.com/)<br />TTIC|[Taylor Kulp-McDowall](https://www.linkedin.com/in/taylorwk/)<br />IARPA|
|<img src="./assets/images/aafer.jpg" alt="Yousra Aafer" width="225"/>|<img src="./assets/images/ma.jpg" alt="Shiqing Ma" width="225"/>|<img src="./assets/images/xiangyu.jpg" alt="Xiangyu Zhang" width="225"/>|
|[Yousra Aafer](https://cs.uwaterloo.ca/~yaafer/)<br />University of Waterloo|[Shiqing Ma](https://people.cs.rutgers.edu/~sm2283/)<br />Rutgers University|[Xiangyu Zhang](https://www.cs.purdue.edu/homes/xyzhang/)<br />Purdue University|