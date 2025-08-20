# Feature Extraction Techniques and Word Embeddings for Text-Based Sarcasm Detection

This repository contains the LaTeX source files and compiled PDF, as well as Python experiment notebooks for the paper, prepared as final the project for my *Deep Learning* class.

You can read the full paper [here](docs/paper.pdf).

## Abstract
Detecting sarcasm in text is a complex challenge that has significant implications for natural language processing.
This paper investigates various machine learning and deep learning approaches to sarcasm detection, focusing on models with ***Term Frequency-Inverse Document Frequency (TF-IDF)*** and ***Bag-of-Words (BoW)*** representations, as well as ***Long Short-Term Memory (LSTM)*** networks utilizing ***GloVe*** and ***Word2Vec*** embeddings. 

My results demonstrate that *TF-IDF-based* models achieve a favorable balance between accuracy and misclassification rates, while *LSTM* models exhibit promising performance, with *Word2Vec* outperforming *GloVe* embeddings.
The results highlight the importance of model selection and feature representation in sarcasm detection models.
I wish for this to provide baseline benchmarks for future research aimed at improving the computational understanding of sarcastic expressions.

## Citation
If you want to cite this paper in your work, please use the following:
```bibtex
@misc{Uifalean2025SarcasmClassifiers,
  title       = {Feature Extraction Techniques and Word Embeddings for Text-Based Sarcasm Detection},
  author      = {Paul-Adrian Uifalean},
  year        = {2025},
  institution = {Babes-Bolyai University},
  note        = {Deep Learning course project},
  url         = {https://github.com/paulicuu/sarcasm-classifiers}
}
```

## License
The paper is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

The source code and notebooks are licensed under the [MIT License](https://opensource.org/license/MIT).
