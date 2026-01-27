---
layout: post
title: Research Directions
date:   2023-11-20
---

My fundamental career goal is to make AI systems trustworthy. My fundamental research goal is to discover knowledge to do so. This research goal involves / will involve me in different fields of AI research, including Interpretability, Alignment, Governance, and Safety. Below are questions I have worked on or will work on connected to my mission.
 
### When should we lose trust in AI Systems?
Knowing when to lose trust in a system is knowing when it will fail. To know when a system will fail, you must know (1) what they are vulnerable to and when (2) can those vulnerabilities be exploited. To understand both of these for AI systems, you can examine the components of the system or its interactions with each other. **Trojan-attacks and adversarial examples** focus on one such component, the training data, to induce specific malicious behaviors.  **Interpretability** examines the interaction between the data and the model to understand (1) what is the underlying mechanism happening and (2) how can that be communicated and understood by the end-user.

The current state of not guaranteeing failure for commercial AI systems is laughable. Take for instance the current safety mechanisms for the most popular models, which purport to be aligned with human preferences and safety of users. [Apparently all of them are vulnerable to cheap text-based attacks](https://llm-attacks.org/).
I am especially interested on replacements for the superficial (and possibly counterproductive) alignment techniques that we currently have, such as Reinforcement Learning from Human Feedback (RLHF), which can reward deceptive behavior and be exploited by adversaries as aforementioned.

<p>
  <img width="70%" 
  src="../assets/img/reddit_grandma.png" 
  align="center"
  style="margin: 10px 30px 10px 10px;">
</p>

[from Reddit](https://www.reddit.com/r/ChatGPT/comments/12uke8z/the_grandma_jailbreak_is_absolutely_hilarious/)


### How can all of us trust AI Systems?
AI Systems are designed to be generalizable (i.e. adapt their knowledge to the specific environment). However, this is not always the case, and the opposite may sometimes be true: that current AI Systems instead can change the environment to better suit itself, which includes the users (it is debatable whether this happens with social media recommender systems on users (e.g. a user may develop Body Dysmorphic Disorder from looking exclusively on recommended photos)).

For <ins> all of us </ins> to trust these systems, we need the participation of everyone affected in designing and contributing data towards a system to be deployed in an environment. The environment has to be specified and not just an afterthought. I am interested in designing methods that make **AI system design and governance** inclusive amongst everyone affected, especially from the Majority World, countries who have been historically excluded from such activities even in other technology and social domains. One research direction I believe is important is on **low-resource languages**, which would enable greater adoption of AI systems within the Majority World as well as preserving minority languages.

For all the potential of these Systems to persuade and manipulate, it must be used to depolarize and regain consensus on which sources of information we as a society value. Researchers seek to align AI systems, but **align them to whose interests?** I believe that it is a combination of the public interest, users, and those affected by these systems. Current alignment techniques assumes that humans have a homogenous set of values. I am interested in efforts that replace such techniques that account for value uncertainties and different value systems, along with repurposing these current alignment techniques for consensus building, [such as this work that uses AI systems that can find consensus given diverse preferences](https://arxiv.org/abs/2211.15006).


### What is this trust for? 
### Towards Revealing Hidden Worlds

<p style="text-align: center;">"Just as there are odors that dogs can smell and we cannot, as well as sounds that dogs can hear and we cannot, so too there are wavelengths of light we cannot see and flavors we cannot taste.

Why then, given our brains wired the way they are, does the remark “Perhaps there are thoughts we cannot think,” surprise you?

Evolution, so far, may possibly have blocked us from being able to think in some directions; there could be unthinkable thoughts."</p>
<p style="text-align: center;">    - Richard Hamming in <em> The Unreasonable Effectiveness of Mathematics </em> </p>
<br>

What is the intelligence in the artificial? In the biological? In ourselves? Of AI agents, of creatures more complicated and primitive, of other people? What is it like to be what we can never be? And how can that lead us to understand intelligent creatures a bit better? AI is finally allowing us to push the frontiers of what we can know of external beings and systems, of transmission of culture and language, of songs older than any of our ancestors. What is it like to unlock a hidden world present in plain sight? What are the repercussions for the study of psychology, gender, linguistics, sociology, biology, and ecology?

<p style="text-align: center;">❝These sounds that we can’t hear, this light that we can’t see, how do we even know about these things in the first place? Well, we built tools. We built tools that adapt these things that are outside of our senses, to our human bodies, our human senses. We can’t hear ultrasonic sound, but you hook a microphone up to an oscilloscope and there it is. You’re seeing that sound with your plain old monkey eyes. We can’t see cells and we can’t see galaxies, but we build microscopes and telescopes and these tools adapt the world to our human bodies, to our human senses. When Hamming says there could be unthinkable thoughts, we have to take that as “Yes, but we build tools that adapt these unthinkable thoughts to the way that our minds work and allow us to think these thoughts that were previously unthinkable."❞ </p>
<p style="text-align: center;">    - Bret Victor in <em> The Media for Thinking the Unthinkable </em> </p>
<br>

There will be things that we will never be able to understand, but we will try to approximate them with the tools we have built. I think this is the biggest benefit of AI. My hope is that AI can help us unlock what we cannot know and do ourselves. And with these constantly-refined principles, unlock wisdom with our newfound powers. 