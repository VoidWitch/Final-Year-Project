## Abstract

Malware threat actors frequently employ obfuscation techniques to manipulate execution traces and evade detection systems. To understand these emerging malware threats, robust behavioural representations are crucial for effective malware clustering.

This study evaluates the efficacy of Probabilistic Suffix Trees (PSTs) in generating sequence-based behavioural models for robust malware clustering under synthetic obfuscation and evaluates the framework’s ability to maintain accurate family-level clusters.

The findings reveals that while PSTs are able to yield a feasible, probabilistic representation of malware sequences, they are not able to reliably maintain family level taxonomy within clusters. Experimental results observed a non-monotonicity between distance correlation values and noise levels, indicating their inability to reliably withstand structural manipulation. 
It is concluded that the partial preservation of structure at lower stochastic noise rates suggests viability of using PSTs for behavioural modelling and clustering, though achieving a higher level of clustering robustness would require the incorporation of real obfuscated data for a more representative evaluation, and domain
expertise in situations where datasets are sparse and realistic modelling of clean or
obfuscated traces are required
