---
layout: default
---


# Overview

| **Date** | May 5, 2023 (9 am - 18:00 pm US Eastern Time) |
| **Location** | The workshop will be held *virtually*. The internal ICLR workshop website is [here](https://iclr.cc/) (ICLR registration required).|


Backdoor attacks aim to cause consistent misclassification of any input by adding a specific pattern called a trigger. Unlike adversarial attacks requiring generating perturbations on the fly to induce misclassification for one single input, backdoor attacks have prompt effects by simply applying a pre-chosen trigger. Recent studies have shown the feasibility of launching backdoor attacks in various domains, such as computer vision (CV), natural language processing (NLP), federated learning (FL), etc. As backdoor attacks are mostly carried out through data poisoning (i.e., adding malicious inputs to training data), it raises major concerns for many publicly available pre-trained models. Companies relying on user data to construct their machine learning models are also susceptible to backdoor attacks.

Defending against backdoor attacks has sparked multiple lines of research, including detecting inputs with backdoor triggers, determining whether a model has hidden backdoors, eliminating potential backdoors inside a model, etc. Many defense techniques are effective against some particular types of backdoor attacks. However, with increasingly emerging diverse backdoors, the defense performance of existing work tends to be limited. Most defense techniques and attacks are developed for the computer vision domain. It is yet to explore the connection between attacks and defenses among different domains.

This workshop, **B**ackdoor **A**ttacks a**N**d **D**efen**S**es in Machine Learning (**BANDS**), aims to bring together researchers from government, academia, and industry that share a common interest in exploring and building more secure machine learning models against backdoor attacks. With the wide adoption of large pre-trained models in real-world applications, any injected malicious behaviors, such as backdoors in those models, are particularly concerning. It is, therefore, particularly important to gather researchers in the area and expand the community to improve the security of machine learning.

This workshop aims to answer the following questions:
- What other types of backdoor attacks can we find in CV/NLP/FL machine learning models?
- Can we launch backdoor attacks in other domains, such as binary analysis tools, network intrusion detection systems, reinforcement learning, etc.?
- What are the similarities and differences of backdoor attacks in various tasks?
- How can we measure the stealthiness of backdoor attacks in different domains? What are the costs and practicality of launching backdoor attacks in the real world?
- What is the performance of existing defense techniques in studied domains? Can they be adapted to other domains?
- How can we develop a general defense method against a variety of backdoor attacks and even unseen attacks?
- Are there other forms of defenses that are practical in the real world?
