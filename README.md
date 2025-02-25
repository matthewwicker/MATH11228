# MATH11228
A Public Repository Containing Slides and Coursework on Adversarial Robustness

### Course Slides

The course comprises a roughly 90 minute lecture covering the primary motivations for studying adersarial robustness in machine learning. We then formulate the robustness of a function as an optimization problem and explore first-order methods for crafting adversarial examples discussing the most seminal works [1][2]. We discuss critical drawbacks of first-order methods including lack of soundess which motivates certification methods. We provide the mathematical prelimaries on interval bound propagation [3] a simple abstraction which enables us to formally rule out the existance of a successful adversarial attack. Finally, we discuss harnessing both of these techniques for adversarial training. If time permits, we will quickly discuss some other applications to explainability [4] and poisoning [5].

### Coursework Assignment

The assigned coursework is a jupyter notebook that already implients some of the preliinary algorithms we observe in the lecture. We ask students to extend the FGSM algorithm of [1] to the PGD algorithm in [2]. Additionally, we ask students to incorperate their implimentation of PGD into training as discussed in [2]. Within the notebook students will find an implimentation of interval bound propagation [3], but this purely for students who find this aspect of robustness interesting; no coursework question is asked regarding these. 


[1] - https://arxiv.org/abs/1412.6572

[2] - https://arxiv.org/abs/1706.06083

[3] - https://arxiv.org/abs/1810.12715

[4] - https://arxiv.org/abs/2212.08507

[5] - https://arxiv.org/abs/2406.05670
