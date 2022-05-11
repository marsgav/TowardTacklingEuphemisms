# TowardTacklingEuphemisms

Martha Gavidia

This repository contains the notebooks used for the paper: “Toward Tackling Euphemisms in Natural Language Processing”

1) MGEuphemisms_Autophrase.ipynb

The code base comes from Searching for PETs: Using Distributional and Sentiment-based Methods for Finding Potentially Euphemistic PETs

Lee P., Gavidia M., Feldman A. and J. Peng. “Searching for PETs: Using Distributional and Sentiment-Based Methods to Find Potentially Euphemistic Terms”. In Proceedings of the 2nd Workshop on Understanding Implicit and Underspecified Language, NAACL 2022, Seattle

The changes in this notebook come at the phrase extraction stage, where Lee et. all use Phrases for finding phrases within text, this notebook experiments with Autophrase. Used in conjunction with spacy's PhraseMatcher, the algorithm is then run with this new phrase extraction method.

2) Parrot_Paraphraser.ipynb

This notebook contains paraphrasing experiments for a subtask within the algorithm to find potentially euphemistic terms as outined in the aforementioned paper.
