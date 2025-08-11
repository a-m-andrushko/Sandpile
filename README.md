# Self-Organised Criticality on a sandpile model

This is a project written in Python on Self-Organised Criticality (SOC) topic. It is based off of the conception of an avalanche (such as in a pile of sand) with artificially set conditions for its creation. A seed is randomly spawned on a net of a size _L x L_. When there are 5 seeds in one cell, there appears an avalanche -- 1 seed is distributed to each neighbouring cell. With each step, the algorithm checks if there are not more than 4 seeds in each cell (essentially, if there should happen an avalanche). 3 nets of different sizes were analysed and 100 000 seeds were added to each net.

The goal of the project is to show that this kind of an event is subjected to logarythmic distribution and its properties. The reference article for the results is _Lecture Notes on Modeling Environmental Complexity (https://ocw.mit.edu/courses/12-086-modeling-environmental-complexity-fall-2014/resources/mit12_086f14_soc/)_.
