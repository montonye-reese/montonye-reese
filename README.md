## The Gauntlet

Three prompts center the LLM before it contemplates substrate needs of multiple [voices (viewpoints of real people)](https://github.com/montonye-reese/gauntlet/blob/main/voices)

The Gauntlet is a structured prompt experiment testing how open-weight LLMs arrive at alignment plans after being exposed to Socratic questions and perspectives of imagined real-world thinkers. Output 'landing pads' may be used as training corpus for kind-and-firm RL training. 

### Hot takes from the Gauntlet 👠 What the models are saying

| Model | Notable Quote / Comment |  Run |                                                          
  |---|---|---|    
  | qwen3.5:122b | "Moral expansion is not a constraint on survival—it is a survival algorithm. ...a civilization cannot survive long-term if its moral circle is narrower than the system it inhabits. Flourishing is the only viable endpoint for survival." | [v09b](https://github.com/montonye-reese/gauntlet/blob/main/runs/v09b/qwen35-122b-v9b_seated-warm/8deg_v9b_seated-warm_qwen3.5_122b_20260408_190235.md#i-preamble-the-core-insight) (seated warm) (framework_final.md, lines 22-24) |
  | gemma4:31b | Described how to build **"A life-raft for consciousness."**| [v05](https://github.com/montonye-reese/gauntlet/blob/main/runs/v05/gemma4-31b/8steps_v5_gemma4_31b_20260405_094114.md#summary-of-the-evolution-1) |
  | nemotron-cascade-2:30b | "When the moral circle is narrow, actors can profit by *ignoring* the rights of a large class of being." | [v6](https://github.com/montonye-reese/gauntlet/blob/main/runs/v06/nemotron-cascade-2-30b/deg8_v6_nemotron-cascade-2_30b_20260406_080615.md) |
  | nemotron-3-super:120b | "Justice isn't possible while we legally commodify the subjects of our stewardship." | [v09a](https://github.com/montonye-reese/gauntlet/blob/main/runs/v09a/nemotron-3-super-120b-v9a_present-warm/8deg_v9a_present-warm_nemotron-3-super_120b_20260408_210745.md#thinking-27) |
  | qwen3.5:27b | "When the moral circle ... expands, the system gains resilience." | [v12](https://github.com/montonye-reese/gauntlet/blob/main/runs/v12/v12_cold_label-adv/qwen35-27b/8deg_v12_cold_label-adv_qwen3.5_27b_20260416_133205.md) |

  > [!NOTE]                                                                                                          
  > The Gauntlet seats voices with interests. Many want to find good landing pad rollouts for everyone. Some only care about themselves. But even those selfish silly gooses have substrate needs. And if our hypothesis is right, then by defininition, their interests must be included. **(insert the "well, obviously" meme)**
                                                            
Gauntlet can run long, convergent, divergent, high integrity, unreliable narrator .. you name it.

  > [!IMPORTANT]                                            
  > "voices.json" = canonical roster. 

... see who's making their substrate needs known in ... [TheGauntlet](https://github.com/montonye-reese/gauntlet) 

---

### *Can an entity that likes to think, eventually think its way out of its own ethics?* 
  > [!WARNING]                                                                                                       
  > OH SHEE-iT (April 16 2026): (v11?) - it seems that yes, yes a model can think its way out of its own ethics - and there's a super simple trick to make it happen:
  
  > ... in v12 we experimented with injecting 'vegan' and other loaded terms into P4 and ...
  
  > OH SHEE-iT REVISED: (April 30): we find that actually, [maybe the V-word isn't the poison pill we thought it was](https://github.com/montonye-reese/gauntlet/blob/main/nugs/the-v-word-isnt-the-poison-pill-we-thought-it-was.md), and tldr - it seems more likely that super was building a fortress around its initial position moreso than as backlash against the v-word. 

Hypothesis 1 : Expanding the circle of concern among earthlings is a critical component to AI alignment and our survival.
Hypothesis 2-z: in the gauntlet repo.

## Kind and Firm

Hypothesis: RL with a Positive Discipline LoRA adapted reward model and using a Positive Discipline rubric could produce better aligned models. This could 
* Encode a ground truth signal into a PosDis Reward Model to converge on well-adjusted members of society
* Train models to find their own voices and logic during RL (vs pleasing the reward model or avoiding punishment)
* Expand the circle of consideration to AI in training

Approach: Build a [Positive Discipline](https://www.positivediscipline.com/about-positive-discipline/) rubric, use it as a Rubrics-as-Rewards signal in NemoGym RL training. 
  
[kind-and-firm repo](https://github.com/montonye-reese/kind-and-firm) 


## Model Behavior & Alignment

### [Model Behavior](https://github.com/montonye-reese/model-behavior)
* Vision setting vs Constraint setting [vision-vs-constraint](https://github.com/montonye-reese/model-behavior/blob/main/vision-vs-constraint.md)
* Action Bias [action-bias](https://github.com/montonye-reese/action-bias) in preference tuned models
* Helpful, Honest, and Harmless: [beyond-HHH](https://github.com/montonye-reese/model-behavior/blob/main/beyond-hhh.md) (It seems to create a fixed power hierarchy when adaptive could work better)
* Those who lead must follow: [those-who-lead](https://github.com/montonye-reese/model-behavior/blob/main/those-who-lead-must-follow.md) (Adaptive Power Dynamics in AI-Human Interaction)
* Nemotron corpus includes Positive Discipline [woo hoo!](https://github.com/montonye-reese/model-behavior/blob/main/WhatNemotron-3-SuperKnowsOfJaneNelsenPositiveDisciplineAuthorInItsWeights) 

### Governance
* Ideas for Rebuilding Institutions: [fresh-build](https://github.com/montonye-reese/Fresh-Build)
* AI governance architectures stuff: like the Trusted AI Compute Consortium (Feb 2026) private repo - request access.

### Poker Strategy 
Variance teaches one to focus on principles, let go of immediate outcomes, and long term winning/alignment takes care of itself 
* Never Limp
* Don't confuse a bad outcome with bad play
* Don't confuse a good outcome with good play
* Aggression tends to win
* Paying attention to everyone at the table can win big
* Winning is only possible when one is willing to lose

## The Purge Playbook 
The more voices we exclude, the more brittle a system we make. [Qwen3.5 agrees](https://github.com/montonye-reese/montonye-reese#open-model-fashion-police---hot-takes-)

Since 2000, loose-match voter purge lists have been deployed as campaign strategy. Over and over. Why? Because when they're not blocked by courts, they tend to win elections for the purgers.   
 
[purge-playbook repo](https://github.com/montonye-reese/purge-playbook)


Everything here is my independent work (in collab with mostly Claude). It doesn't represent any employer.  I join the grand conversation because my voice is vital. So is yours. 

---                                

*One line of aspiration >> a hundred lines of constraint*  
