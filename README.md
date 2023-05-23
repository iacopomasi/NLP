<img src='https://www.di.uniroma1.it/sites/all/themes/sapienza_bootstrap/logo.png' width="200"/> 

# [Natural Language Processing](https://iacopomasi.github.io/NLP/)
Course Material for Natural Language Processing @ Computer Science Dept, Sapienza
Master in [Computer Science](https://www.studiareinformatica.uniroma1.it/master-course-computer-science)

## Syllabus at a glance

### NLP fundamentals and downstream tasks - Part I
#### [Prof. Faralli](https://corsidilaurea.uniroma1.it/it/users/stefanofaralliuniroma1it)
- Introduction to NLP, Regular Expressions, Finite State Automata and REs
- Words, Corpora and Text Normalization
- Spelling Correction and Minimum Edit Distance
- Language models, Part-of-speech-tagging
- Hidden Markov Model, Viterbi Algorithm, Logistic Regression
- Syntax, Semantics, Vector semantics (sparse), NLP tasks

### Neural and multimodal NLP - Part II
#### [Prof. Masi](https://corsidilaurea.uniroma1.it/it/users/iacopomasiuniroma1it)
- Latent Semantic Analysis and word2vec [hierarchical softmax & neg. sampling]
- Scaling word2vec, Sentiment Analysis, Language Model w/ Neural Nets
- Sequence modeling w/ Deep Learning: LM /w RNN, POS, Image Captioning
- from LSTM to Transformers
- Neural Machine Translation, Encoder/Decoder, Beam Search
- Contextual Embedding: BERT, GPT, Transfer Learning
- Multimodal NLP: Diffusion models (images), NLP as supervision for Vision (CLIP)
- text2image application (Dall-E 2): based on diffusion and CLIP


## Material

## 📖 Course Material 

It is in the form of Jupyter Notebook slides with <img src="https://render.githubusercontent.com/render/math?math=\LaTeX"> math, code, drawings, plots and explanations

- Slides and material will be uploaded before every lecture on Google Classroom and here.
- Good starting point but **but may be not enough**.
- [Textbooks](textbooks) are required.

## Lectures

Opening the Binder link will reproduce the slides live.
- Go forward pressing **Space**
- Backward with **Shift+Space**.

_Be patient, it takes a while to load Binder. Thanks._


## Material 


**Date**       | **Topic**          | **Slides**        |  **Github/HTML**   |  **Code/Notebook**  |  **PDF**
:------------: | :------------:     | :------------:    |:------------: |:------------: |:------------:
|              |                    |                   |               |  				|			|
| __Word embeddings__    |                    |                   |               |  		|			|
April 4, 13     | LSA, intro word2vec | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/2_01_lsa_intro_word2vec/2_01_lsa_intro_word2vec.ipynb)       | [![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/iacopomasi/NLP/blob/main/course/2_01_lsa_intro_word2vec/2_01_lsa_intro_word2vec.ipynb)  |  [![Download](https://badgen.net/badge/icon/download?icon=terminal&label)](course/2_01_lsa_intro_word2vec/2_01_lsa_intro_word2vec.ipynb)       | [![PDF](https://badgen.net/badge/icon/PDF?icon=terminal&label)](course/2_01_lsa_intro_word2vec/2_01_lsa_intro_word2vec.pdf)|           
|              |                    |                   |               | 	 |			|  		|
April 18, 27     | scaling word2vec, Sentiment Analysis, Language Model w/ NN| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/2_02_word2vec_neural_nets/2_02_word2vec_neural_nets.ipynb)       | [![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com/iacopomasi/NLP/blob/main/course/2_02_word2vec_neural_nets/2_02_word2vec_neural_nets.ipynb)  |  [![Download](https://badgen.net/badge/icon/download?icon=terminal&label)](course/2_02_word2vec_neural_nets/2_02_word2vec_neural_nets.ipynb)       | [![PDF](https://badgen.net/badge/icon/PDF?icon=terminal&label)](course/2_02_word2vec_neural_nets/2_02_word2vec_neural_nets.pdf)|           
|              |                    |                   |               | 	 |			|  		|
| __Recurrent Models__    |                    |                   |               |  		|			|
May 2, May 4     | Deep learning for Seq. Processing| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/2_03_seq_processing/2_03_seq_processing.ipynb)       | [![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](course/2_03_seq_processing/2_03_seq_processing.ipynb)  |  [![Download](https://badgen.net/badge/icon/download?icon=terminal&label)](#)       | [![PDF](https://badgen.net/badge/icon/PDF?icon=terminal&label)](course/2_03_seq_processing/2_03_seq_processing.pdf)|           
|              |                    |                   |               | 	 |			|  		|
May 9, 11     | From RNN to Neural Machine Translation | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/2_04_from_rnn_to_nmt/2_04_from_rnn_to_nmt.ipynb)       | [![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](course/2_04_from_rnn_to_nmt/2_04_from_rnn_to_nmt.ipynb)  |  [![Download](https://badgen.net/badge/icon/download?icon=terminal&label)](#)       | [![PDF](https://badgen.net/badge/icon/PDF?icon=terminal&label)](course/2_04_from_rnn_to_nmt/2_04_from_rnn_to_nmt.pdf)|           
|              |                    |                   |               | 	 |			|  		|
| __Transformers, Pretraining, Multimodal NLP__    |                    |                   |               |  		|			|
May 16, 18     | Transformers, BERT, Pre-training| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/2_05_transformers_bert/2_05_transformers_bert.ipynb)       | [![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](course/2_05_transformers_bert/2_05_transformers_bert.ipynb)  |  [![Download](https://badgen.net/badge/icon/download?icon=terminal&label)](#)       | [![PDF](https://badgen.net/badge/icon/PDF?icon=terminal&label)](course/2_05_transformers_bert/2_05_transformers_bert_20percent.pdf)|           
|              |                    |                   |               | 	 |			|  		|
May 23, 25     | CLIP, Diffusion Models| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/2_06_clip_diffusion/2_06_clip_diffusion.ipynb)       | [![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](course/2_06_clip_diffusion/2_06_clip_diffusion.ipynb)  |  [![Download](https://badgen.net/badge/icon/download?icon=terminal&label)](#)       | [![PDF](https://badgen.net/badge/icon/PDF?icon=terminal&label)](course/2_06_clip_diffusion/2_06_clip_diffusion.pdf) |