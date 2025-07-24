# ICS2203 Statistical Language Processing - Speech Phoneme Project
Author: Miguel Baldacchino

📅 Date: May 2025

--- 

# Speech Phoneme Classifier

Vowel phoneme classifier using k-NN on formant features extracted from ABI-1 Corpus.

---

## 🔍 Overview

- Manual feature extraction of formant frequencies (F1, F2, F3) from audio samples using Ocenaudio.
- Building a k-Nearest Neighbour (k-NN) classifier to classify vowel phonemes based on formant features.
- Evaluating classifier performance across multiple accents, genders, and vowel classes.
- Analyzing confusion matrices and F1 scores for model performance.
- Experimenting with different values of k and distance metrics.

---

## Dataset

- Subset of the ABI-1 Corpus (Accents of the British Isles)
- Includes 14 accents, 10 male and 10 female speakers each
- Words designed to elicit vowel sounds (e.g., "heed", "hid", "head", etc.)

---

## 🛠️ Requirements

- Python 3.x
- scikit-learn (for train_test_split, k-NN, metrics)
- Ocenaudio (for feature extraction)


---

*ICS2203 Statistical NLP Assignment 2025, University of Malta*
