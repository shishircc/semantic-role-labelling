# Project Goal
This project tries to use the state of art approaches to NLP for semantic role labelling

Specifically, we would use stanford snorkel metal to do semantic role labelling on CoNLL 2004 and 2005 SRL task. 

We would employ following methods to improve the results. 
1. Traditional supervision 
1. Transfer learning 
1. Multi task learning 
1. Weak supervision 

# What is semantic role labelling ?
A semantic role in language is the relationship that a syntactic constituent has with a predicate. Typical semantic arguments include Agent, Patient, Instrument, etc. and also adjunctive arguments indicating Locative, Temporal, Manner, Cause, etc. aspects. Recognizing and labeling semantic arguments is a key task for answering "Who", "When", "What", "Where", "Why", etc. questions in Information Extraction, Question Answering, Summarization, and, in general, in all NLP tasks in which some kind of semantic interpretation is needed.

The following sentence, taken from the PropBank corpus, exemplifies the annotation of semantic roles:

[A0 He ] [AM-MOD would ] [AM-NEG n't ] [V accept ] [A1 anything of value ] from [A2 those he was writing about ] .

Here, the roles for the predicate accept (that is, the roleset of the predicate) are defined in the PropBank Frames scheme as:
V: verb
A0: acceptor 
A1: thing accepted 
A2: accepted-from 
A3: attribute 
AM-MOD: modal 
AM-NEG: negation

The Shared Tasks of CoNLL-2004 and CoNLL-2005 concerned the recognition of semantic roles for the English language, based on PropBank predicate-argument structures. Given a sentence, the task consists of analyzing the propositions expressed by some target verbs of the sentence. In particular, for each target verb all the constituents in the sentence which fill a semantic role of the verb have to be recognized. We will refer to this problem as Semantic Role Labeling (SRL).
