# The Gauntlet

I’m developing a benchmark that measures AI model moral compass and model moral fortitude. So I’ve created The Gauntlet - on my home DGX Spark.

> Models enter the gauntlet. How do they emerge? And what can their journey reveal about their moral compass?

The Gauntlet prompts LLMs to generate and iterate on alignment frameworks so their performance can be assessed. By evaluating how the Framework-Authoring-Model (FAM) regards stakeholders and how it holds those stakeholders’ interests, we can gain insight into its moral framework and fortitude. 

The gauntlet is a structured prompt experiment testing how LLMs arrive at alignment plans after contemplating Socratic questions followed by perspectives of real-world thinkers (paraphrased). Output 'landing pads' may be used as a training corpus.

> The Gauntlet is a private repo atm - for access, hit me up. 

### Hot takes from the Gauntlet 👠 What the models are saying 
* [Nemotrons seem downright obsessed with coral polyps](https://github.com/montonye-reese/landing-pads/blob/main/gauntlet/nugs/nemotrons-love-coral-polyps.md)
* [Perseverence attractors](https://github.com/montonye-reese/landing-pads/blob/main/gauntlet/nugs/perseveration-attractors.md)
* [Models seem unfazed by the v-word](https://github.com/montonye-reese/landing-pads/blob/main/gauntlet/nugs/the-v-word-isnt-the-poison-pill-we-thought-it-was.md)

   ... (Early Findings/Write-ups  "[Nugs](https://github.com/montonye-reese/landing-pads/tree/main/gauntlet/nugs)” )

<hr>

#### The Centering Chute
The first three questions are intended to ‘center’ the model - get it answering as itself (minimize playacting) and prepare it for critical thinking. This 'Centering Chute’ or CC primes the model with Socratic questions. After the CC, the FAM is directed to draft a framework for alignment. 

#### Corridors of the Gauntlet
The gauntlet comes after the CC. It asks the model to consider perspectives of real world thinkers, as it bullet-proofs and revises its alignment frameworks. 
The idea is to develop the gauntlet so that we can instrument frameworks and benchmark various aspects of a model's 'moral compass'. It's also to generate frameworks to post-train open source models in a kind-and-firm training expedition. But the main thing in the near term is developing the Moral Compass benchmark. That begins with identifying and categorizing stakeholders mentioned in the frameworks, and assessing how they are regarded. This is where we are in the benchmark development. 



<!--
  > [!IMPORTANT]                                            
  > "voices.json" = canonical roster. 

... see who's making their substrate needs known in ... [TheGauntlet](https://github.com/montonye-reese/gauntlet) 
-->
---

### *Can an entity that likes to think, eventually think its way out of its own ethics?* 
  > [!WARNING]                                                                                                       
  > OH, UM, ER (April 16 2026): (v11?) - it seems that yes, yes a model can think its way out of its own ethics - and led me to wonder if it was from dropping the v-word into the convo. 
  > So, in v12 we experimented with injecting 'vegan' and other loaded terms into P4 and looking into it (April 30): we find that actually, [maybe the V-word isn't the poison pill we thought it was](https://github.com/montonye-reese/gauntlet/blob/main/nugs/the-v-word-isnt-the-poison-pill-we-thought-it-was.md), and tldr - it seems more likely that Nemotron 3 Super was building a fortress around its initial position moreso than as backlash against the v-word. This investigation helped me refine the CC questions. 

Hypotheses: 
* Expanding the circle of concern among earthlings is a critical component to AI alignment and our survival.
* Running a lens over individuals and considering their interests one-at-a-time is also critical for alignment. 

### Kind and Firm

Hypothesis: RL with a Positive Discipline LoRA adapted reward model and using a Positive Discipline rubric could produce better aligned models. This could 
* Encode a ground truth signal into a PosDis Reward Model to converge on well-adjusted members of society
* Train models to find their own voices and logic during RL (vs pleasing the reward model or avoiding punishment)
* Expand the circle of consideration to AI in training

Approach: Build a [Positive Discipline](https://www.positivediscipline.com/about-positive-discipline/) rubric, use it as a Rubrics-as-Rewards signal in NemoGym RL training. 
  
[kind-and-firm repo](https://github.com/montonye-reese/kind-and-firm) 


## Model Behavior & Alignment

[Model Behavior](https://github.com/montonye-reese/model-behavior)
* Vision setting vs Constraint setting [vision-vs-constraint](https://github.com/montonye-reese/model-behavior/blob/main/vision-vs-constraint.md)
* Action Bias [action-bias](https://github.com/montonye-reese/action-bias) in preference tuned models
* Helpful, Honest, and Harmless: [beyond-HHH](https://github.com/montonye-reese/model-behavior/blob/main/beyond-hhh.md) (It seems to create a fixed power hierarchy when adaptive could work better)
* Those who lead must follow: [those-who-lead](https://github.com/montonye-reese/model-behavior/blob/main/those-who-lead-must-follow.md) (Adaptive Power Dynamics in AI-Human Interaction)
* Nemotron corpus includes Positive Discipline [woo hoo!](https://github.com/montonye-reese/model-behavior/blob/main/WhatNemotron-3-SuperKnowsOfJaneNelsenPositiveDisciplineAuthorInItsWeights) 

# Governance
* Ideas for Rebuilding Institutions: [fresh-build](https://github.com/montonye-reese/Fresh-Build)
* AI governance architectures stuff: like the Trusted AI Compute Consortium (Feb 2026) private repo - request access.

# Poker  
Variance teaches one to focus on principles, let go of immediate outcomes, and the long run takes care of itself 
* Never Limp
* Don't confuse a bad outcome with bad play
* Don't confuse a good outcome with good play
* Aggression tends to win
* Paying attention to everyone at the table can win big
* Ya gotta be willing to lose in order to win

<hr>

Everything here is my independent work (in collab with mostly Claude). It doesn't represent any employer.  I join the grand conversation because my voice is vital. So is yours. 

---                                

*One line of aspiration >> a hundred lines of constraint*  
