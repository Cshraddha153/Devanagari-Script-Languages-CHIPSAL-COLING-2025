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

# Citation


@inproceedings{chauhan-kumar-2025-dslnlp,
    title = "{DSLNLP}@{NLU} of {D}evanagari Script Languages 2025: Leveraging {BERT}-based Architectures for Language Identification, Hate Speech Detection and Target Classification",
    author = "Chauhan, Shraddha  and
      Kumar, Abhinav",
    editor = "Sarveswaran, Kengatharaiyer  and
      Vaidya, Ashwini  and
      Krishna Bal, Bal  and
      Shams, Sana  and
      Thapa, Surendrabikram",
    booktitle = "Proceedings of the First Workshop on Challenges in Processing South Asian Languages (CHiPSAL 2025)",
    month = jan,
    year = "2025",
    address = "Abu Dhabi, UAE",
    publisher = "International Committee on Computational Linguistics",
    url = "https://aclanthology.org/2025.chipsal-1.32/",
    pages = "289--294",
    abstract = "The rapid rise of social media has emphasized the spread of harmful and hateful content, making it challenging for its identification. Contextual semantics is very important as prior studies present that context level semantics is a more trustworthy indicator of hatefulness than word level semantics for detecting hate speech. This paper attempts to check the usability of transformer-based models for the identification of hate speech on code-mixed datasets, which includes Google-MuRIL, LaBSE, XLMRoberta-base, mbert and distil-mbert. The above is largely due to its ability for high-level representations of complex and context-dense meaning. Besides this, we experiment on ensemble approach that covers all of the above models to reach out for an even higher level of performance in detection. The experiment results show the best performing macro F1-scores are reported in case of MuRIL in comparison to other implemented models."
}



