# Tani Bayesian Phylogenetics
This repository contains the data used in the 2022 Honours thesis ‘Borrowed traits and dubious dates: A Bayesian phylogenetic analysis of the Tani subbranch of the Trans-Himalayan family’ by Alice Dolin. 

The xlsx file contains all the language data and the binary presence-absence morphemic cognacy matrices. Each sheet contains a different variation on the dataset. Since the name of each cognate set does not affect the analysis, the ‘morpheme’ row uses a rough orthographic approximation, although it is clear from the cognate judgements which morpheme it refers to. The actual lists of word forms employ the common orthography used in Tani language research, which is mostly IPA but with double vowels to represent long vowels.

Each folder is for one of the dataset variations. The folder contains the nexus file, fasta file, xml file, log file, original trees file, and annotated trees file. The nexus file and fasta file contain the cognacy matrix and can be used to rerun the analysis. The xml file displays all the model choices and model parameter values, as well as the cognacy matrix. The remaining files can be used to observe all the results.

The ‘original’ folder contains the files for the main set of results with the binary covarion, relaxed lognormal, and birth-death model.\
The ‘calmsea’ folder contains the files for the dataset that contained only the meanings from the original dataset that appeared in the CALMSEA list.\
The ‘calmsea_swadesh’ folder contains the files for the dataset that contained only the meanings from the original dataset that appeared in the CALMSEA list or the Swadesh-200 list.\
The ‘nonrepeated’ folder contains the files for the dataset that did not contain common repeated morphemes.\
The ‘relaxed’ folder contains the files for the dataset that had the relaxed cognacy requirement, where any uncertain cognacy judgements were encoded as cognate.\
The ‘strict’ folder contains the files for the dataset that had the strict cognacy requirement, where any uncertain cognacy judgements were encoded as non-cognate.\
Within the ‘original’ folder there are three more folders.\
The ‘1500’ folder contains the files for when the Tani MRCA prior was calibrated to be 1500 ± 50 years ago rather than 1000 ± 50 years ago.\
The ‘ctmc’ folder contains the files for when the substitution model was changed to a continuous time Markov chain model.\
The ‘pseudo_dollo’ folder contains the files for when the substitution model was changed to a pseudo-Dollo model.\

