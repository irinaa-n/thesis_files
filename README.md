Here we provide files used in master's thesis "EXPLAINING UNIVERSAL SEMANTIC PROPERTIES IN THE ADJECTIVAL/ADVERBIAL DOMAIN".

The work is motivated by the work of Futrell et al.(2020) ["What determines the order of adjectives in English? Comparing efficiency-based theories using dependency treebanks"](https://aclanthology.org/2020.acl-main.181/). 

In our study we:

1. Replicate results of Futrell et al.(2020) on adjectives in English language, including subjectivity.
2. Conduct a study on adjectives in Russian language (to see if results are consistent cross-linguistically). 
3. Conduct a study on adverb order in English and Russian (we continue by investigating in detail if the predictions made by these theories can generalize and be applied to explain the order of adverbs).

In our study we followed the procedure defined by the original study and following the notes the notes https://github.com/langprocgroup/adjorder. The subjectivity for English adjectives is also provided on the git hub page of the origina study.

For parsing the corpus with dependencies, we used Stanza parser, Qi et al. (2020) https://stanfordnlp.github.io/stanza/depparse.html

For clustering word in Russian we used embeddings from https://github.com/natasha/navec

## data 
1. We used a subsection of English and Russian Wikipedia, automatically annotated with dependencies (Stanza parser, Qi et al. (2020)).
   en/aan_counts and ru/aan_count are files with adjectives on which we perform analysis in English and Russian. 
   ru/clust_pairs are the cluster sof adjectives and nouns in Russian
3. Following Futrell et al. (2020) we additionally tested predictors on hand-parsed data from a subpart of English Universal Dependency corpus: GUM, EWT, Atis, LinES, ParTUT treebanks (Nivre et al., 2016).



