---
marp: true
title: Privatization of AI research
description: 
theme: uncover
paginate: true
_paginate: false
---


![bg](https://source.unsplash.com/glRqyWJgUeY)

![](#fff)
# <!--fit--> The Privatization of AI Research(-ers):

Causes and Potential Consequences

From university-industry interaction to public research brain-drain?


<style scoped>a { color: #eee; }</style>

<!-- This is presenter note. You can write down notes through HTML comment. -->

---


Roman Jurowetzki, Daniel Hain
Aalborg Univ. Business School, DK
[IKE](https://www.business.aau.dk/research/ike/) / [AI Growth Lab](https://www.business.aau.dk/research/ai-growth-lab/) / [aidenmark.dk](https://aidenmark.dk/)

Juan Mateos-Garcia, Konstantinos Stathoulopoulos
NESTA, UK

## Download the paper [https://arxiv.org/abs/2102.01648](https://arxiv.org/abs/2102.01648) 📝

---

![bg](#123)
![](#fff)

# Main questions we look into
- Does the private sector "harvest" the best performing AI researchers? i.e. which attributes contribute to transitions.
- After transitioning into industry, does their (publicly available) output decline?

We speculate about:
- What does that mean for public interest, ethics, fairness and safety in emerging AI technologies?

---

![bg right 60%](https://upload.wikimedia.org/wikipedia/commons/6/6d/Timnit_Gebru_crop.jpg)

#### **[#ISupportTimnit](https://googlewalkout.medium.com/standing-with-dr-timnit-gebru-isupporttimnit-believeblackwomen-6dadc300d382)**

- AI researcher Timnit Gebru dismissed from Google Brain (Ethics co-lead) in Dec. 2020
- Disagreement with management over conference paper
- Margaret Mitchell terminated in Feb. 2021


---
<!-- 

![bg left 70%](https://upload.wikimedia.org/wikipedia/commons/6/6d/Timnit_Gebru_crop.jpg)

- Critique of recent large language models
- Concerns about training data and fairness
- (Growing) Resource requirements for training as well as transparency

---
-->

### Some more background:
- Growing private sector participation in AI research:
    - Google had in 2019 the highest number of accepted papers at NeurIPS
    - Standard frameworks went from being developed in academia (Theano & Caffe) to industry (Tensorflow & PyTorch)
    - Star researches leading industry AI labs
    - [stateof.ai report](https://docs.google.com/presentation/d/1ZUimafgXCBSLsgbacd6-a-dqO7yLyzIl1ZJbiCBUUT4/edit?usp=sharing)
    - Reasons include access to data, infrastructure, easy integration of research

---


<!-- - Modern AI techniques require large datasets available in industry
- Potential disconnect between academic AI and industry needs forcing industry to take basic research "in their own hands"
- Tight integration of AI systems and industrial cloud platforms exploiting synergies and increasing competitiveness
- Culture allowing academic publication helps attracting scholars and running "blue-skies" research
- Ability to internalize externalities

--- -->

### Potential risks of AI privatization

- potential homogenization of public and private research spheres
- potential neglect of long-term negative social externalities
- steering of the trajectory towards "de-democratization" of AI due to focus on data and resource-hungry techniques rather than promotion of "leaner" approaches
- Worker displacement without productivity growth
- Fairness/bias issues
--- 

![bg left](https://source.unsplash.com/CWbxnAk77so)
#### Possible transition mechanisms


- Researcher-push (Roach and Sauermann, 2010)
- Technology-push (Ahmed and Wahed, 2020)
- Industry-pull 
--- 

<!-- ![bg](#123)
![](#fff)
### Private vs public AI development?
- Private AI labs play an increasingly important role
- They advance AI tech but also study ethical risks
- We don't know what we don't know - not everything is pulished
- Commercial interest may not be always in line with research agendas of employees
- Start-up acquisition argument

#### Argument for bolstering public AI research 

--- -->
### What we do in this paper
- Study bibliographic data and reconstruct AI researcher careers (~83k researchers, active  2015-2020)
- Provide descriptive analysis on researcher and output levels
- Identify "switchers"
- Survival analysis: reasons for transition into industry
- Diff-in-diff: consequences of transition

---
![bg](#123)
![](#fff)
### <!--fit--> Some descriptives first 📊

---

<!-- ![bg](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/f1_fos_trends.png)


--- -->

![bg 90%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/f2_part_trend.png)


---



![bg 90%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/f5_net_flows.png)


---

![bg 90%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/f6_trans_rankings.png)

---

![bg 95%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/T1_variables.png)

---

![bg 95%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/T3_descriptives.png)

---
### Survival Analysis

- Aim: Identifying drivers of UI transition
- Model: Cox proportional hazard (DV: Propability of UI transition)
- Sample: All academia & academia-industry trajectory researchers

---

![bg  65%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/T4_survival.png)

---
![bg](#123)
![](#fff)

## Survival Analysis -insights

- Deep learning researchers are more likely to transition into industry
- Researchers with a more extended network to colleagues in industry are less likely to transiion
- The impact of research output as measured by citations (not quantity of publications) is crucial when explaining transitions into industry


---
## Diff-in-diff exploring consequences

- Aim: Identify impact of AI transition on research performance & knowledge dissemination
- Modl: Diff-in-Diff regression (DV: Researcher's citation rank) 
- Sample: PSM matched sample of university-industry with one university remaining researcher
- Treatment: University Industry transition (of matched pair)


---

![bg 55%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/T5_d-i-d.png)

---

![bg 60%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/fig_interaction_1.png)

---
![bg](#123)
![](#fff)

# Diff-in-diff exploring consequences

- Compared with very similar colleagues that don't transition, those researchers that do produce more impactful research (higher **cit$^{rank}$**)

- There is some indication that over time their impact decreases: Fewer publications of breakthrough research (possible); one-hit-wonder?


---


<!-- 
![bg](#123)
![](#fff)

# All in all?
- Does the private sector "harvest" the best performing AI researchers? **Yes** ✅
- After transitioning into industry, does their (publicly available) output decline? **Possibly** ✅
- What does that mean for public interest, ethics, fairness and safety in emerging AI technologies? **Public research needs to remain attractive for star- AI-researchers** 🧐


--- -->



## Now what - policy implication

- There is nothing wrong with impactful industry AI labs
- Better coordination and funding of public mission-oriented AI research!
- Development and enforcement of guidelines / certification of AI
- What do industrial AI ethics units do? Mapping/evaluation? "Alignment"
- Where do commercial interest clash with public objectives?

---

# References

- Roach, M. and Sauermann, H. (2010). A taste for science? phd scientists’ academic orientation and self-selection into research careers in industry. Research policy, 39(3):422–434.

- Ahmed, N. and Wahed, M. (2020). The de-democratization of ai: Deep learning and the compute divide in artificial intelligence research.

---


# Backup - slides
---

## Next steps for this paper
- Solidify framework
- More detailed analysis of the transition outcomes: 
    - diversity and novely ouf output
    - collaboration patterns
- From knowledge diffusion back to knowledge production?

---

![bg 95%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/f3_fos_evol.png)


---

![bg 70%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/f4_trans_types_evol.png)

---

![bg 50%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/fig_desc_matrix.png)

---

![bg 55%](https://raw.githack.com/nestauk/ai_research/dev/reports/pres_strassb/media/f7_trans_orgs.png)

ai-privatization – Deployment Source