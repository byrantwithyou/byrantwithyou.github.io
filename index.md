---
layout: homepage
---
## About Me
I'm currently a Ph.D. student in computer science at [Purdue University](https://www.purdue.edu/), advised by [Prof. Abulhair Saparov](https://asaparov.org/){:target="_blank" rel="noopener noreferrer"}. Previously, I earned a Master of Science in Computer Science from [ETH Zurich](https://ethz.ch/en.html){:target="_blank" rel="noopener noreferrer"}, Switzerland, and a Bachelor of Engineering in Software Engineering from [Tongji University](https://en.tongji.edu.cn/p/){:target="_blank" rel="noopener noreferrer"}, China.  

## Research Interests

My research focuses on LLM agents, particularly their evaluation, post-training, and self-improvement. I am also interested in applying AI agents to scientific discovery.


## Experience
 - External Research Collaborator, [Nace.ai](https://www.nace.ai/){:target="_blank" rel="noopener noreferrer"}
 
 I collaborated with Nace.ai on developing a hypernetwork-based approach for test-time adaptation. I first curated a large-scale training dataset comprising 4 million counterfactual reasoning questions with long-context inputs. I then trained a hypernetwork in a distributed setting to dynamically generate a context-specific LoRA adapter for each input. Our approach outperformed several model editing and in-context learning baselines while achieving lower inference costs.

 - Research Internship, [TikTok US Infrastructure Lab](https://us.tiktok.com/){:target="_blank" rel="noopener noreferrer"}

During my internship at TikTok, I investigated performance bottlenecks in RDMA-based distributed memory transfers within internal database systems. I collaborated closely with cross-functional team members to diagnose slow queries and identify underlying performance issues. My investigation spanned multiple system layers, including software architecture, network protocols, and hardware-level primitives. I extensively leveraged performance profiling and observability tools, such as eBPF, to analyze system behavior and pinpoint bottlenecks. I also contributed to developing and optimizing other database functionality throughout the internship.

## Selected Publications

<!-- Replace the entries below with your real publications. No images needed. -->
**[$$\left(\mathcal{LC}\right)^2$$: *L*earning *C*onstant-size *L*atent *C*ontext for Language Model Agents](/assets/lclc.pdf){:target="_blank" rel="noopener noreferrer"}**   
**Yunxin Sun**, Abulhair Saparov  
*preprint*

**[Do Language Models Follow Occam’s Razor? An Evaluation of Parsimony in Inductive and Abductive Reasoning](https://arxiv.org/abs/2509.03345){:target="_blank" rel="noopener noreferrer"}**  
**Yunxin Sun**, Abulhair Saparov  
*EMNLP Main*, 2026.  


**[Reasoning Models Reason Well, Until They Don’t](https://aclanthology.org/2025.ijcnlp-long.52/){:target="_blank" rel="noopener noreferrer"}**  
Revanth Rameshkumar, Jimson Huang, **Yunxin Sun**, Fei Xia, Abulhair Saparov  
*AACL-IJCNLP*, 2025.  

## Technical Skills
- **Programming:** Python, C/C++, SQL, Bash
- **ML Frameworks:** PyTorch, Hugging Face Transformers, TRL, PEFT
- **LLM Tools:** vLLM, SGLang, Unsloth
- **Scientific Computing:** NumPy, SciPy, pandas, scikit-learn
- **Infrastructure:** Linux, Git, Docker, SLURM
