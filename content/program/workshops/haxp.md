---
title: "HAXP"
date: 2026-03-19T00:00:00+00:00
draft: false
---

# HAXP: Human-Aware and Explainable Planning

ICAPS 2026 Workshop <br/>
Dublin, Ireland
June 28, 2026
<!-- Room 6, Melbourne Connect, <br/>
Melbourne, Victoria, Australia <br/>
November 10, 2025 -->

<!-- The program is available [here](https://haxp-icaps.web.app/2025). -->

## Program

<style>
.program-table table {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: 3rem;
}
.program-table th,
.program-table td {
  padding: 10px 14px;
  border: 1px solid #e0e0e0;
  text-align: left;
  vertical-align: top;
  line-height: 1.5;
}
.program-table thead th {
  background: #f5f5f5;
  font-weight: 700;
}
.program-table td:first-child,
.program-table th:first-child {
  white-space: nowrap;
  width: 1%;
}
.program-table tbody tr:nth-child(even) {
  background: #fafafa;
}
</style>

<div class="program-table">

| Time        | Session                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 9:00–9:15   | Welcome & Opening Remarks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| 9:15–10:15  | [**Keynote 1**](#keynotes)<br>Mohan Sridharan                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| 10:30–10:50 | Coffee Break                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| 10:50–12:30 | **Paper Session 1**<br>**Generalized Execution for Dialogue Planning** — Victoria Armstrong, Christian Muise<br>**Iterative Planning with MUGS Explanations: Exploring the Design Space** — Johannes Schmalz, David Groß, Rebecca Eifler, Julián Méndez, Raimund Dachselt, Stefan Gumhold, Jörg Hoffmann<br>**Generating Explainable Counterfactual Policies through Temporal Logic Queries** — Arnaud Lequen, Clément Legrand-Lixon, Léo Saulières<br>**Constraint based Plan Distance Metric for Operator-Centric Replanning in Multi-Agent Progression Missions** — Emile Siboulet, Arthur Bit-Monnot, Marc-Emmanuel Coupvent des Graviers, Christophe Guettier<br>**Explaining Symbolic Action Policies using Facet Reasoning** — Jennifer Santos, Johannes K Fichte, Daniel Gnad |
| 13:00–14:30 | Lunch Break                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| 14:30–15:30 | [**Keynote 2: When Explanations Need Explanation: The Case of the Semi-Factual**](#keynotes)<br>Mark Keane                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| 15:35–15:55 | **Paper Session 2**<br>**An Epistemic Human-Aware Task Planner Integrating Agents Expectations** — Gabriele Sartor, Rachid Alami                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 16:00–16:20 | Coffee Break                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| 16:20–17:20 | **Paper Session 2 (Ctn)**<br>**How Hard Is It to Lie in Model Reconciliation?** — Huanghua Sheng, Pascal Bercher, Sarath Sreedharan<br>**Can LLMs Explain Plans Well?** — Philip D. Hopkins, Stylianos Loukas Vasileiou, Sarath Sreedharan<br>**Do You Even Know What I Want? Improving LLMs Ability to Detect Hidden User Intent** — Kelsey Sikes, Sarath Sreedharan                                                                                                                                                                                                                                                                                                                                                                                            |
| 17:20–18:00 | Fishbowl Discussion                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

</div>



## Keynotes

### Keynote 1

**Speaker:** Mohan Sridharan

*Title and abstract to be announced.*

### Keynote 2

**Title:** When Explanations Need Explanation: The Case of the Semi-Factual

**Speaker:** Mark Keane

**Abstract:** Traditionally, eXplainable Artificial Intelligence (XAI) casts decision-making scenarios as single-shot interactions, in which a single decision is explained to a user in a single step (end of story). However, sequential decision-making scenarios tend to be much more complicated; plans can require a series of explanations for successive steps or explanations that expand on an initial explanation (e.g., unpacking the details of a planning step). Such scenarios require us to consider multiple explanations and their relationships to one another. Here, I consider semi-factual or "even-if" explanations which often need to be explained further, because they can conflict with user understandings. Semi-factuals explain what changes to input features do not change outcomes (unlike counterfactuals which show the feature-changes that change outcomes). For example, if I apply for a $5k loan and am refused, I could be told "Even if you asked for a $100 loan, you would still be refused". Psychologically, semi-factuals have been shown to weaken people's causal models; in this loan example, a customer's belief that the refusal was due to the loan amount is negated. Accordingly, users can find these explanations counter-intuitive, requiring further explanation (e.g., one that might tell them that their credit-score is more important than loan-amount in the system's decision-making). I show how these "explanations of explanations" can be computed from trend-based analyses of changing feature-importances for different instances and show that people prefer them to single-shot ones. More generally, this work shows some of the complexity that can arise when one moves beyond single-shot scenarios.



## Aim and Scope of the Workshop

As artificial intelligence (AI) is increasingly being adopted into application solutions, the challenge of supporting effective interactions with humans is becoming more apparent. Partly this is to support integrated working styles, in which humans and intelligent systems cooperate in problem-solving, but also it is a necessary step in the process of building and calibrating trust as humans migrate greater competence and responsibility to such systems. The International Workshop on Human-Aware and Explainable Planning (HAXP), formerly known as the Explainable AI Planning (XAIP) workshop, brings together the latest and best in human-AI interaction and explainability, in the context of planning, scheduling, RL and other forms of sequential decision-making process. The workshop is collocated with ICAPS, the premier conference on automated planning and scheduling. Learn more: [HAXP](https://haxp.org)

## Topics of Interest

The workshop includes - but is not limited to - the following topics:

* Human-aware planning, scheduling, and execution.
* Human monitoring, plan & goal recognition, and behavior prediction.
* Mixed-initiative planning and scheduling systems.
* Learning methods for planning/scheduling in the presence of humans.
* Explanations of behavior in sequential decision-making/decision-support.
* Explanation of scheduling/allocation decisions to human stakeholders.
* Improving interpretability and explainability of AI planning/scheduling systems.
* Generating predictable and interpretable behavior.
* Methods for reward, goal, preference, or constraint specification for reinforcement learning agents.
* Creating interpretable and adaptive user interfaces for planning/scheduling systems.
* Proactive assistance and decision-support in human-AI collaborative scenarios.
* Cognitive modeling, social interaction, and theory of mind.
* Safety, ethics, fairness, transparency and responsible behavior generation in the context of planning/scheduling systems.
* Representation and acquisition of human behavioral models.
* Theories and applications of human behavior models.
* Trust, communication, and collaboration in human-AI teams.
* Benchmarking planning/scheduling domains for human-AI interaction.
* Large language models in human-aware planning & scheduling.

<!-- ## Accepted Papers

* **<a href="https://openreview.net/pdf?id=Zj8UqVxClT">Finding Semantically Guided Repairs in PDDL Domains Using LLMs</a>** <br>
Nader Karimi Bavandpour and Pascal Bercher
* **<a href="https://openreview.net/pdf?id=rRjEMmavbR">A Collaborative Numeric Task Planning Framework based on Constraint Translations using LLMs</a>**<br>
Anthony Favier, Ngoc La, Pulkit Verma, and Julie A. Shah
* **<a href="https://openreview.net/pdf?id=5tR1k4LwtL">How Humans Explain the Difference in the Quality of Plans -- A User Study</a>**<br>
Benjamin Krarup, Amanda Jane Coles, Dancheng Gao, Derek Long, and David E. Smith
* **<a href="https://openreview.net/pdf?id=d4BMCAsHC2">Explainable Planning via Counterfactual Task Analysis for the Beluga Challenge and Beyond</a>**<br>
Elliot Gestrin, Gustaf Söderholm, Paul Höft, Mauricio Salerno, Jendrik Seipp, and Daniel Gnad
* **<a href="https://openreview.net/pdf?id=qfgi8aPbTU">Plan Explanation through Recommendations</a>**<br>
Sarath Sreedharan, Trisha Ghali, and David E. Smith
* **<a href="https://openreview.net/pdf?id=YVD85eTdDa">Revisiting Action Failures Through the Lens of Cooperative Games</a>**<br>
Sarath Sreedharan and David E. Smith
* **<a href="https://openreview.net/pdf?id=mLtxlPOizm">When Humans Revise Their Beliefs, Explanations Matter: Evidence from User Studies and What It Means for AI Alignment</a>**<br>
Stylianos Loukas Vasileiou, Antonio Rago, Maria Vanina Martinez, and William Yeoh -->



## Accepted Papers

- **How Hard Is It to Lie in Model Reconciliation?**  
  Huanghua Sheng, Pascal Bercher, Sarath Sreedharan

- **Generalized Execution for Dialogue Planning**  
  Victoria Armstrong, Christian Muise

- **Iterative Planning with MUGS Explanations: Exploring the Design Space**  
  Johannes Schmalz, David Groß, Rebecca Eifler, Julián Méndez, Raimund Dachselt, Stefan Gumhold, Jörg Hoffmann

- **Generating Explainable Counterfactual Policies through Temporal Logic Queries**  
  Arnaud Lequen, Clément Legrand-Lixon, Léo Saulières

- **Constraint based Plan Distance Metric for Operator-Centric Replanning in Multi-Agent Progression Missions**  
  Emile Siboulet, Arthur Bit-Monnot, Marc-Emmanuel Coupvent des Graviers, Christophe Guettier

- **An Epistemic Human-Aware Task Planner Integrating Agents Expectations**  
  Gabriele Sartor, Rachid Alami

- **Explaining Symbolic Action Policies using Facet Reasoning**  
  Jennifer Santos, Johannes K Fichte, Daniel Gnad

- **Do You Even Know What I Want? Improving LLMs Ability to Detect Hidden User Intent**  
  Kelsey Sikes, Sarath Sreedharan

- **Can LLMs Explain Plans Well?**  
  Philip D. Hopkins, Stylianos Loukas Vasileiou, Sarath Sreedharan



## Important Dates

* **Paper submission deadline: ~~May 10~~ May 17, 2026 UTC-12**
* Notification of acceptance: June 10, 2026 UTC-12
* Camera-ready paper submissions: TBD

* Workshop date: June 28, 2026

## Submission Details

We invite submissions of the following types: 

* Full technical papers making an original contribution; up to 9 pages including references.
* Short technical papers making an original contribution; up to 5 pages including references. 
* Position papers proposing HAXP challenges, outlining HAXP ideas, debating issues relevant to HAXP; up to 5 pages including references.

Submissions will be hosted on [ChairingTool](https://chairingtool.com/conferences/haxp26/main-track)
Please ensure that you have registered with ChairingTool. 
<!-- New profiles with an institutional email will be activated immediately. However, new profiles without an institutional email may take up to two weeks to be activated. -->

Papers must be prepared according to the instructions for ICAPS 2026 (in AAAI format) available at: [Paper template](https://aaai.org/authorkit26-1/)


Authors who are considering submitting to the workshop papers rejected from the main conference, please ensure you do your utmost to address the comments given by ICAPS reviewers. Please do not submit papers that are already accepted for the main conference to the workshop.

Every submission will be reviewed by members of the program committee according to the usual criteria such as relevance to the workshop, the significance of the contribution, and technical quality. *Submissions are double-blind*.

The workshop is meant to be an open and inclusive forum, and we encourage papers that report on work in progress or that do not fit the mold of a typical conference paper.

At least one author of each accepted paper must attend the workshop in order to present the paper. All participants need to register to the main ICAPS conference. There will be no separate registration required.

## Organizing Committee

* [Benjamin Krarup](https://scholar.google.co.uk/citations?user=yEjXNsQAAAAJ&hl=en) | King’s College London, UK
* [Alan Lindsay](http://tinyurl.com/AlanLindsayScholar) | Simplifai Systems, UK
* [Silvia Tulli](https://silviatulli.com/) | Sorbonne University, France
* [Stylianos Loukas Vasileiou](https://thestlucas.com/) | New Mexico State University, USA
* [Chenyuan Zhang](https://sites.google.com/view/chenyuanzhang) | Monash University, Australia
<!-- * [Pulkit Verma](https://pulkitverma.net) | Massachusetts Institute of Technology, USA -->

<!-- ## Extended Program Committee -->

<!-- * [Pascal Bercher](https://comp.anu.edu.au/people/pascal-bercher/) | Australian National University, Australia
* [Daniel Fišer](https://danfis.cz/) | Aalborg University, Denmark
* [Daniel Gnad](https://mrlab.ai/daniel-gnad/) | Heidelberg University, Germany and Linköping University, Sweden
* [Alban Grastien](http://www.grastien.net/ban/) | Australian National University, Australia
* [Akkamahadevi Hanni](https://scholar.google.com/citations?user=sDZ4u1oAAAAJ&hl=en) | Arizona State University, USA
* [Rohan R Paleja](https://www.rohanpaleja.com/) | Purdue University, USA
* [Shashank Shekhar](https://shekharsai.github.io/) | University of Caen Normandy, France
* [Emile Siboulet](https://scholar.google.com/citations?user=6gf1iZcAAAAJ) | LAAS-CNRS, France and Safran Electronics & Defense, France
* [Ho Chit Siu](https://www.ll.mit.edu/biographies/ho-chit-siu) | MIT Lincoln Laboratory, USA
* [Christabel Wayllace](https://www.cwayllace.com/) | New Mexico State University, USA
* [Mohammad Yousefi](https://yousefi.ai/) | Australian National University, Australia -->

## Steering Committee

* [Jeremy Frank](https://www.linkedin.com/in/jeremy-frank-62141bb3/) | NASA Ames Research Center, USA
* [Claudia Goldman](https://il.linkedin.com/in/claudiagoldman) | The Hebrew University of Jerusalem, Israel
* [Jörg Hoffmann](http://fai.cs.uni-saarland.de/hoffmann/) | Saarland University, Germany
* [Subbarao Kambhampati](https://rakaposhi.eas.asu.edu/) | Arizona State University, USA
* [David Smith](http://psresearch.xyz/) | PS Research, USA
* [William Yeoh](https://sites.wustl.edu/wyeoh/) | Washington University in St. Louis, USA
