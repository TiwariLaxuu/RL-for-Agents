# RL-for-Agents

Task Horizon are growing fast

Roughly Doubling every 4-7 months 

New Era : Open Models 

3 Reasons to train your own agent 
1. Privacy : "Not your weights, not your Brain"
2. Costs : Efficiency matters when you're tokenmxxing
3. Specialisation : One model can't master every domain 


Agents VS Vanilla RL 

when RLVR isn't enough 

Main Difference 

RLVR                      ||          Agentic RL 
Math-Code-Logic                       Appworld-SWE-bench-OSworld 

--Prompt---                           ---Task---
    |                                      |
--LLM----                             ---LLM Agent----
    |                                      |
--Answer---                           ---Action-----
    |                                       |
--Verifier(Binary Reward)---          ----Environment---
                                            |
                                      ----Observation----
                                            |
                                      -----Reward-----
                                            (Sparse, Delayed)



Training Frameworks: async or go home 
Decoupled Generation + Training 

Open-source stacks 
1. AReal
2. VeRL
3. prime-rl
4. TRL
5. Slime
6. TorchForge

Evaluation: Main Challenges
Saturation 
Overfitting 
Benchmark Gaming 
