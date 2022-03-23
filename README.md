# Seeing Confusion Through a New Lens: On the Impact of Atoms on Novices' Code Comprehension
José Aldo Silva da Costa · Rohit Gheyi · Fernando Castor · Pablo Roberto · Márcio Ribeiro · Baldoino Fonseca

## Overview
Code comprehension is crucial for software maintenance and evolution processes, but it can be hindered by small code patterns known as atoms of confusion. These atoms of confusion are tiny code snippets that can confuse developers causing them to misjudge the behavior of the code. Previous studies investigated several atoms of confusion. They mainly investigated the presence of the atoms in a real-world setting, the developers’ opinions, and controlled experiments which measured time and accuracy. However, these approaches have limitations and we need more empirical evidence from a finer-grained perspective to better understand how the atoms affect the code comprehension and to what extent they do so. To complement previous studies, we evaluate how six atoms of confusion affect the code comprehension of human subjects with eye tracking. We compare programs obfuscated by atoms of confusion with functionally equivalent clarified versions. We perform a controlled experiment with 32 novices in Python language and we measure their time, accuracy, and visual effort while determining the outputs of programs. We measure visual effort with fixation duration, fixations count, and regressions count. We found that the clarified version of the code containing the atom Operator Precedence reduced the time spent in the region that contains the atom to the extent of 38.6%. The fixation duration, the fixations count, and the regressions count reduced to the extent of 34.1%, 32.3%, and 50%, respectively. The clarified version of the code containing the True or False Evaluation reduced the regressions count in the region that contains the atom by 47.3%. On the other hand, the clarified version of Multiple Variable Assignment increased the time in the region that contains the atom and the regressions count by 30.1% and 60%, respectively. We observed improvements with the clarified versions of Conditional Expression, Implicit Predicate, and Assignment Operator, however, not statistically significant. An eye tracker allowed us to investigate how much time the subjects spent in specific regions of the code containing the atoms and their clarifying versions, measure to what extent the atoms impacted the fixation duration, fixations count, and regressions count, and how the atoms impacted the way the subjects read the code. One of the nuances we observed is that the clarified version of Multiple Variable Assignment increased the time spent in the region supposed to be clearer, while increased the number of vertical regressions, and turned the reading of the code into a less direct manner by the addition of one more line of code. Based on our findings, we encourage researchers to consider eye tracking to evaluate atoms of confusion with fine granularity. We also encourage educators to give preference to patterns in the teaching practice that do not impact the understanding and visual effort of students. In addition, practitioners and language designers should also be careful when using these patterns in the language syntax.

Keywords: atoms of confusion · eye tracking · code comprehension 

## Experiment Material

All tasks, forms, reponse time, accuracy, and fixation data of all tasks are available <a href="">here</a>.

## Results

All tables summarizing the results are available <a href="">here</a>.

## Graphical Visualizations 

All graphical visualizations regarding fixations are available <a href="">here</a>.
