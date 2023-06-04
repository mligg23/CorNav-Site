---
layout: default
---

## Abstract

Given a natural language, a general robot has to comprehend the instruction and find the target object or location based on visual observations even in unexplored environments. Most agents rely on massive diverse training data to achieve better generalization, which requires expensive labor. These agents often focus on common objects and fewer tasks, thus are not intelligent enough to handle different types of instructions. To facilitate research in open-set vision-and-language navigation, we propose a benchmark named MO-VLN, aiming at testing the effectiveness and generalization of the agent in the multi-task setting. First, we develop a 3D simulator rendered by realistic scenarios using Unreal Engine 5, containing more realistic lights and details. The simulator contains three scenes, i.e., cafe, restaurant, and nursing house, of high value in the industry. Besides, our simulator involves multiple uncommon objects, such as takeaway cup and medical adhesive tape, which are more complicated compared with existing environments. Inspired by the recent success of large language models (e.g., ChatGPT, Vicuna) and large multi-modal models (e.g., GPT-4, LLaVA), we construct diverse high-quality data of instruction type without human annotation. Our benchmark MO-VLN provides five tasks: 1) goal-conditioned navigation given a specific object category (e.g., fork''); 2) goal-conditioned navigation given simple instructions (e.g., Search for and move towards a tennis ball''); 3) step-by-step instruction following; 4) finding abstract object based on high-level instruction (e.g., ``I am thirsty''); 5) navigation completion with assisted dialogue, which allows the agent to ask questions and acquire more information about the goal Since training an agent with specific tasks is not general, we implement multiple zero-shot baselines on our benchmark, exploiting the advantages of pre-trained open-vocabulary models and large language models. The open-vocabulary model is used for prompt-based grounding, while the large language model is employed to both understand the input instruction and perform commonsense reasoning for planning. We conduct in-depth studies to evaluate current open-vocabulary models and large language models, and find that there is still a large gap between baselines and human performance especially on complicated tasks.

Keywords: Vision-and-Language Navigation; Multi-Task; Open-set; Zero-Shot



[LeaderBoard](./leaderboard.html)

## Reference

```
@inproceedings{xliang2023benchmark,
  title={MO-VLN: A Multi-Task Benchmark for Open-set Zero-Shot Vision-and-Language Navigation},
  author={Xiwen Liang, Liang Ma, Shanshan Guo, Jianhua Han, Hang Xu, Shikui Ma, Xiaodan Liang},
  booktitle={NeurIPS 2023},
  pages={TBD},
  year={2023},
  organization={TBD}
}
```
