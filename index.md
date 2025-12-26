---
layout: default
---
# Welcome!
 
I am a PhD candidate in Computer Science (AI/NLP) at Colorado State University, advised by [Dr. Nikhil Krishnaswamy](https://www.nikhilkrishnaswamy.com/) at the [SIGNAL Lab](https://www.signallab.ai/people). My research focuses on training AI systems for effective multi-agent collaboration through friction-aware alignment and partner-aware learning. I am grateful to be supported by the [Wim Böhm Ph.D. Fellowship in Computer Science](https://natsci.source.colostate.edu/ram-legacy-wim-bohm/) in 2025, the [Evolutionary Computing and Artificial Intelligence Fellowship](https://compsci.colostate.edu/scholarships-fellowships/) in 2024 and multiple DARPA grants including the [Friction for Accountability in Conversational Transactions](https://www.darpa.mil/research/programs/friction-for-accountability-in-conversational-transactions) (FACT) program. In summer-fall 2025,  I worked in RL for personalized recommendation at [Amazon Science](https://www.amazon.science/). I also worked with [Cresta Intelligence](https://cresta.com/) on robust email writing agents using multi-turn RL in summer 2025. Previously, I contributed to efficient preference alignment in LLMs for healthcare applications at [Optum AI](https://www.optumlabs.com/work/artificial-intelligence.html). 

**I am currently seeking Full-Time Research Scientist/Machine Learning Engineer positions.**

# My Research
My work brings three strands together to address long-horizon, multi-turn alignment of LLMs in multi-agent settings — whether the agent is human or machine. The broader goal is to move toward true agency: systems that reason about consequences, interactions, and values over time, rather than optimizing myopic reward signals.

First — causal generalization. I study how LLMs can transfer an understanding of user values to unseen situations, especially during long collaborations where trajectories diverge and standard evaluations (LLM judges, static reward models) break down. Instead of evaluating agents in isolation, my work studies them interactionally — asking how behavior changes when agents respond to one another. In [Roleplay Collaboration] (https://arxiv.org/abs/2509.05882), I introduced a counterfactual evaluation framework that simulates alternative dialogue loops to measure the marginal contribution of adding a new agent to the team — particularly important when adding an agent has cost and uncertain ripple effects.
Second — principled credit assignment. I design learning objectives that attribute outcomes to the mechanisms that actually caused them, while discounting misleading or adversarial contributions. This allows policies to reason about short- vs. long-term tradeoffs transparently. In [Interruptible Collaborative Roleplayer](https://arxiv.org/abs/2510.22462)  (NeurIPS 2025), I developed an RL objective that operationalizes intentionality: models learn to remain consistent under counterfactual contexts, enabling constrained, stable policy updates when we already know how the agent should behave.
Third — cognitively grounded collaboration. Drawing from BDI, pragmatics, and cognitive modeling, I turn dialogue signals into richer supervision so systems can adapt to evolving, user-specific preferences. Real collaborations often stall in “frictive states” — moments of belief misalignment or uncertainty. In the[Frictional Agent Alignment Framework](https://aclanthology.org/2025.acl-long.542/) (ACL 2025), I introduced an offline algorithm that detects and models such moments, helping LLMs resolve disagreement and guide groups toward common ground.
In the past, I led the development of **[AxomiyaBERTa](https://aclanthology.org/2023.findings-acl.739/)**, the *first* monolingual Assamese transformer-based language model, which set new benchmarks for low-resource language processing by leveraging Assamese-specific phonological signals in transfer learning.

 
## News and Events
- Dec' 25: Had an incredible experience presenting at NeurIPS 2025 and meeting with the legendary Rich Sutton. 
- Nov' 25: Gave an invited talk at [NSF iSAT](https://www.colorado.edu/research/ai-institute/) on my latest work in partner-aware LLMS. 
- Oct' 25: Successfully wrapped up PhD Applied Science internship at [Amazon Science](https://www.amazon.science/) with my incredible mentors Alireza Bagheri Garakani and Fan Yang. 
- Oct' 25: [Paper](https://arxiv.org/abs/2510.22462) on Learning "Partner-Aware" Collaborators in Multi-Party Collaboration accepted at NeurIPS 2025 Main Track. [Code](https://github.com/csu-signal/ICR) 
- Jul' 25: Successfully wrapped up internship at [Cresta Intelligence](https://www.amazon.science/) under the mentorship of [Chuan Wang] (https://www.linkedin.com/in/cwang24/) 
- May' 25: [Paper](https://openreview.net/forum?id=gMvARxotd6) on Friction Agent Alignment Framework (FAAF) accepted at ACL 2025 Main Conference. [Code](https://github.com/AbhijnanNath/FAAF_ACL) for the curious! 
- April' 25: 🏆 Awarded the Wim Bohm and Partners Ph.D. Award, 2025 by the Department of Computer Science, Colorado State University for meritorious accomplishments in the Ph.D. Program.
- April' 25: Presented [DPL](https://aclanthology.org/2025.naacl-long.190/) on Diverse Preference Learning (oral) at NAACL 2025 Main Conference. 
- April' 25: Will be joining Amazon as Applied Science Intern in July, 25 . Supervised by Yan Gao.
- April' 25: Started working with [Cresta Intelligence](https://cresta.com/) as a PhD Machine Learning Research Intern to design high-performance contact center AI agents. 
- Feb' 25: Presented my research on “Friction” Agents at DARPA's Friction and Accountability in Conversational Transactions (FACT) PI Meeting in Stanford University!
- Jan' 25 📝 Paper on Diverse Preference Learning (DPL) in LLMs accepted at NAACL 2025 Main Conference!
- Jan' 25 🏆 Awarded Ph.D. Candidacy — getting closer to the goal! 
- 🎉 Best Paper Award at Educational Data Mining (EDM) 2024
- 🎓 Received PhD Candidacy with Distinction, December 2024
- 🏆 Awarded Evolutionary Computing and AI Graduate Fellowship 2024
- 📝 Paper accepted at NAACL 2024 (Oral)
- 📝 Paper accepted at Findings of EMNLP 2024
- 📝 Paper accepted at LREC-COLING 2024


## Selected Publications

* **[Learning" Partner-Aware" Collaborators in Multi-Party Collaboration](https://arxiv.org/abs/2510.22462)**  
  *Neurips 2025 Main Track*  
  A novel approach to learning partner-aware and intentional collaborator agents via counterfactual regularization for multi-agent collaboration.

* **[Frictional Agent Alignment Framework: Slow Down and Don't Break Things](https://aclanthology.org/2025.acl-long.542/)**  
  *ACL 2025*  
  An LLM alignment framework for learning an optimal intervention agent that guides a group of collaborator agents. 

* **[Simultaneous Reward Distillation and Preference Learning: Get You a Language Model Who Can Do Both](https://arxiv.org/pdf/2410.08458)**  
  *Preprint*  
  A novel approach to combining reward learning with preference optimization in language models.

* **[DPL: Diverse Preference Learning Without A Reference Model](https://drive.google.com/file/d/1N0vDYeeHic2dbISrtJAZfkYKmORTZNz2/view?usp=sharing)**  
  *NAACL Main 2025*  
  Pioneering work on preference learning that eliminates the need for reference models while maintaining diversity.

* **[Okay, Let's Do This! Modeling Event Coreference with Generated Rationales](https://arxiv.org/pdf/2404.03196.pdf)** 🏆  
  *NAACL 2024 (Oral)*  
  Novel approach to event coreference using LLM-generated rationales and knowledge distillation.  
  [Code](https://github.com/csu-signal/llama_cdcr)

* **["Any Other Thoughts, Hedgehog?" Linking Deliberation Chains](https://www.nikhilkrishnaswamy.com/assets/docs/pdfs/EMNLP-2024-Nath.pdf)** ⭐  
  *Findings of EMNLP 2024*  
  Proposed a novel task of linking reasoning chains in multi-agent collaborative dialogues.  
  [Code](https://github.com/csu-signal/ProbingDelibration)

[View all publications →](publications)


## Quick Links
- [Publications](publications.md)
- [Curriculum Vitae](Nath_CV_short.pdf)
- [Research Statement](nath_research_statement_2025_website.pdf)
- [Google Scholar](https://scholar.google.com/citations?user=J9FdsyYAAAAJ&hl=en)
- [GitHub](https://github.com/AbhijnanNath)
- [LinkedIn](https://linkedin.com/in/abhijnan-nath-737727169)
- [Youtube Channel](https://www.youtube.com/@avign5291)

## Contact
Email: abhijnan.nath@colostate.edu  
Department of Computer Science  
Colorado State University  
Fort Collins, CO 80523
