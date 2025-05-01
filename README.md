# Shared task on Natural Language Understanding of Devanagari Script Languages at CHIPSAL@COLING 2025

This repository contains the code and models used for the Shared Task on Natural Language Understanding of Devanagari Script Languages at CHIPSAL@COLING 2025. The task addresses key challenges in processing Devanagari-scripted languages, focusing on language identification, hate speech detection, and target identification.


# Subtask A: Devanagari Script Language Identification

Objective: Classify a given sentence written in Devanagari script into one of five languages: Nepali, Marathi, Sanskrit, Bhojpuri, or Hindi.
Importance: Accurate language identification is crucial in multilingual settings, enabling downstream NLP tasks.

# Subtask B: Hate Speech Detection in Devanagari Script Language

Objective: Detect whether a given monolingual sentence (in Nepali or Hindi) contains hate speech.
Dataset: Annotated corpus with binary labels (hate speech vs. non-hate speech).
Significance: Effective hate speech detection helps in monitoring and moderating harmful content online.

# Subtask C: Target Identification for Hate Speech in Devanagari Script Language

Objective: Given a hateful sentence in Devanagari script, classify the target of the hate speech as:
 1. Individual
 2. Organization
 3. Community
Relevance: Understanding the specific targets of hate speech is essential for content moderation and policy-making.

#  Models Used

We experimented with various transformer-based models and an ensemble approach:

 1. Google-MuRIL
 2. LaBSE
 3. XLM-RoBERTa-base
 4. mBERT
 5. Distil-mBERT
 6. Ensemble Model (Majority Voting across models)

# Research Paper

For more details on the methodology, dataset, and results, refer to our paper:

**Paper Link**: https://aclanthology.org/2025.chipsal-1.32/
