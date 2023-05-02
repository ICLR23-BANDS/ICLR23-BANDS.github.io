---
layout: default
---


Backdoor attacks aim to cause consistent misclassification of any input by adding a specific pattern called a trigger. Unlike adversarial attacks requiring generating perturbations on the fly to induce misclassification for one single input, backdoor attacks have prompt effects by simply applying a pre-chosen trigger. Recent studies have shown the feasibility of launching backdoor attacks in various domains, such as computer vision (CV), natural language processing (NLP), federated learning (FL), etc. As backdoor attacks are mostly carried out through data poisoning (i.e., adding malicious inputs to training data), it raises major concerns for many publicly available pre-trained models. Companies relying on user data to construct their machine learning models are also susceptible to backdoor attacks.

Defending against backdoor attacks has sparked multiple lines of research, including detecting inputs with backdoor triggers, determining whether a model has hidden backdoors, eliminating potential backdoors inside a model, etc. Many defense techniques are effective against some particular types of backdoor attacks. However, with increasingly emerging diverse backdoors, the defense performance of existing work tends to be limited. Most defense techniques and attacks are developed for the computer vision domain. It is yet to explore the connection between attacks and defenses among different domains.

With the wide adoption of large pre-trained models in real-world applications, any injected malicious behaviors, such as backdoors in those models, are particularly concerning. It is, therefore, particularly important to gather researchers in the area and expand the community to improve the security of machine learning.

This workshop aims to answer the following questions:
- What other types of backdoor attacks can we find in CV/NLP/FL machine learning models?
- Can we launch backdoor attacks in other domains, such as binary analysis tools, network intrusion detection systems, reinforcement learning, etc.?
- What are the similarities and differences of backdoor attacks in various tasks?
- How can we measure the stealthiness of backdoor attacks in different domains? What are the costs and practicality of launching backdoor attacks in the real world?
- What is the performance of existing defense techniques in studied domains? Can they be adapted to other domains?
- How can we develop a general defense method against a variety of backdoor attacks and even unseen attacks?
- Are there other forms of defenses that are practical in the real world?

# Call for Papers


We invite submissions on any aspect of backdoor attacks and defenses in machine learning, which includes but is not limited to:

- Novel backdoor attacks against ML systems, including CV, NLP, ML models in cyber-physical systems, etc.
- Detecting backdoored models under different threat models, such as having limited clean data or no data, no access to model weights, using attack samples, etc.
- Eliminating backdoors in attacked models under different settings, such as limited access or no access to the original training/test data
- Certification/verification methods against backdoor attacks with guarantees
- Real-world or physical backdoor attacks in deployed systems, such as autonomous driving systems, facial recognition systems, etc.
- Hardware-based backdoor attacks in ML
- Backdoors in distributed learning, federated learning, reinforcement learning, etc.
- Theoretical understanding of backdoor attacks in machine learning
- Explainable and interpretable AI in backdoor scenario
- Futuristic concerns on trustworthiness and societal impact of ML systems regarding backdoor threats
- Exploration of the relation among backdoors, adversarial robustness, fairness
- New applications of backdoors in other scenarios, such as watermarking ML property, boosting privacy attacks, etc.

The workshop will employ a double-anonymous review process. Each submission will be evaluated based on the following criteria:

- Soundness of the methodology
- Novelty
- Relevance to the workshop
- Societal impacts

We only consider submissions that haven’t been published in any peer-reviewed venue, including ICLR 2023 conference. **We allow dual submission with other workshops or conferences. The workshop is non-archival and will not have any official proceedings.** All accepted papers will be allocated either a virtual poster presentation, or a virtual talk slot.

## Important Dates


<table class="foo">  
  <tr>
    <td width="30%"><b>Submission Deadline</b></td>
    <td width="70%">
      <strike>January 25</strike> <b>February 3</b>, 2023, Anywhere on Earth (AoE) <b>Extended!</b></td>
  </tr>
  <tr>
    <td><b>Author notification</b></td>
    <td>March 3, 2023, Anywhere on Earth (AoE) </td>
  </tr>
  <tr>
    <td><b>Camera ready deadline</b></td>
    <td>April 15, 2023, Anywhere on Earth (AoE)</td>
  </tr>
</table>


## Camera Ready

The final version should be submitted to OpenReview: [https://openreview.net/group?id=ICLR.cc/2023/Workshop/BANDS](https://openreview.net/group?id=ICLR.cc/2023/Workshop/BANDS)

The final version should have up to 4 pages (excluding references, acknowledgements, or appendices). It is recommended to use the template provided at: [Download (LaTeX)](./files/iclr2023.zip)

Or modify the submission latex files as follows:

* Add command "\iclrfinalcopy" in iclr2023_conference.tex
* Change line 88 in iclr2023_conference.sty to "\lhead{Published at ICLR 2023 Workshop on Backdoor Attacks and Defenses in Machine Learning}"


## Author Instructions

Papers should be submitted to OpenReview: [https://openreview.net/group?id=ICLR.cc/2023/Workshop/BANDS](https://openreview.net/group?id=ICLR.cc/2023/Workshop/BANDS)

Submitted papers should have up to 4 pages (excluding references, acknowledgements, or appendices). Please use the ICLR submission template provided at: [https://github.com/ICLR/Master-Template/raw/master/iclr2023.zip](https://github.com/ICLR/Master-Template/raw/master/iclr2023.zip)

Submissions must be anonymous following ICLR double-blind reviewing guidelines, ICLR Code of Conduct and Code of Ethics. Accepted papers will be hosted on this workshop website but are considered non-archival and can be submitted to other workshops, conferences or journals if their submission policy allows.

## Code of Conduct (Drawn from ICLR)

All workshop participants, including authors, are required to adhere to the ICLR code of conduct ([https://iclr.cc/public/CodeOfConduct](https://iclr.cc/public/CodeOfConduct)). All authors of submitted papers are required to read the Code of Conduct, adhere to it, and explicitly acknowledge this during the submission process. The Code of Conduct applies to all conference participation, including paper submission, reviewing, and paper discussion.

## Code of Ethics (Drawn from ICLR)

All workshop participants, including authors, are required to adhere to the ICLR Code of Ethics ([https://iclr.cc/public/CodeOfEthics](https://iclr.cc/public/CodeOfEthics)). All authors of submitted papers are required to read the Code of Ethics, adhere to it, and explicitly acknowledge this during the submission process. The Code of Ethics applies to all conference participation, including paper submission, reviewing, and paper discussion.
