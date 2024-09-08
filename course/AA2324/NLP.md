# Natural Language Processing (NLP)

## Descrizione del corso


**Description:** Il corso ha lo scopo di introdurre gli ultimi progressi ottenuti nel settore dell'elaborazione del linguaggio naturale (NLP). Il corso è un corso avanzato di NLP. Il leitmotiv del corso affronta tecniche per costruire rappresentazioni semantiche del testo che possono essere utilizzate in molteplici applicazioni "intelligenti". Seguendo gli ultimi progressi in NLP, il corso coprirà principalmente gli approcci di Deep Learning in NLP (Recurrent Neural Network, Long Short-Term Memory, Transformers, BERT, GPT2), sebbene vengano introdotte alcune tecniche di base come Latent Semantic Analysis (LSA) o word2vec (word embeddings).

## Preview
- A preview of the course slides can be found at [github.com/iacopomasi/NLP](https://github.com/iacopomasi/NLP)
- The slides can be played at [github.com/iacopomasi/NLP#material-1](https://github.com/iacopomasi/NLP#material-1)
by clicking on launch binder icon [![Binder](https://mybinder.org/badge_logo.svg)](https://github.com/iacopomasi/NLP#material-1)

##  🎯 Obiettivi

- Introduzione all’elaborazione del linguaggio naturale da un punto di vista di apprendimento automatico
- Conoscenza sulle tecniche di apprendimento in NLP (self-supervised NLP, NLP with supervision)
- Develop awareness of the mathematical tools behind.
- Conoscenza su sistemi avanzati di NLP che usando Deep Learning quali: RNN, Transformers, GPT2 (modello alla base di chatGPT)
- Sviluppare il pensiero critico nell’utilizzo dell’apprendimento automatico e su come si valutano questi algoritmi.
- Mostra alcune implementazioni di algoritmi di NLP (laboratorio)


## 📖 Syllabus


| When                       | Topic                                                                          	 | Notebook                                    | Self Eval/Colab  |
|----------------------------|-----------------------------------------------------------------------------------|---------------------------------------------|------------------| 
| **Word Embedding**          |                                                                                	 |                                             |				  |
| Lunedi mat                  | Intro to NLP, Distributional Semantics and Latent Semantic Analysis (LSA)        | `2_01_lsa_intro_word2vec`                   |				  |
| Lunedi pom                  | Learning word embedding with word2vec (application of word2vec)                	 | `2_01_lsa_intro_word2vec`    			   |  [![Self - Eval](https://img.shields.io/badge/Self-Eval-2ea44f)](https://www.dropbox.com/scl/fi/3dv0pa3bnxfmph2k3rqo5/NLP_self_eval_01.pdf?rlkey=2xm1zdghnbbni3r2k4uywjrfz&dl=0-)   |
| 					          |                                                                                	 |                                             |				  |
| Martedi mat                 | Scaling word2vec (negative sampling, hierarchical softmax)                     	 | `2_02_word2vec_neural_nets`                 |				  |
| **Recurrent Models**        |                                                                                	 |                                             |				  |
| Martedi pom                 | Deep learning for Sequence Processing (Recurrent Neural Net - RNN)             	 | `2_03_seq_processing`					   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hducyxe1RCvc1Z-fDtzLlQ1pGz4_s2Zk?usp=sharing) |
| 					          |                                                                                	 |                                             |				  |
| Mercoledi mat               | Deep learning for Sequence Processing (Long Short-term Memory - LSTM)          	 | `2_03_seq_processing`					  |
| Mercoledi pom               |                                                                                	 | ` 2_04_from_rnn_to_nmt`				   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GQDSuxrwq1BiNfF43MSmXd1TFdJk1One?usp=sharing) 				  |
| 					          |                                                                                	 |                                             |				  |
| Giovedi mat                 | From RNN to Neural Machine Translation (NMT)                                   	 | `2_04_from_rnn_to_nmt`                      |	[![Self - Eval](https://img.shields.io/badge/Self-Eval-2ea44f)](#)   |
| **Transformers, Pre-training**|                                                                                 |                                             |				  |
| Giovedi pom                 | Transformers, BERT, GPT2, Pre-training (foundations to understand OpenAI chatGPT)| `2_05_transformers_bert`                    |				  |
| 					          |                                                                                	 |                                             |				  |
| **Multimodal NLP**          |                                                                                  |                                             |				  |
| Venerdi mat                 | Implementing a Transformers and miniGPT                                       	 |  `2_05_transformers_bert` 			       |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) 				  |
| Venerdi pom                 | CLIP, ChatGPT (foundations to understand OpenAI Dall-E) + Final Evaluation          	 | `2_06_clip_diffusion`                       | [![Self - Eval](https://img.shields.io/badge/Self-Eval-2ea44f)](#)   |


## Binder

| Notebook                               | Binder Link                                                                                                                                    |
|---------------------------------------- |----------------------------------------------------------------------------------------------------------------------------------------------- |
| `2_01_lsa_intro_word2vec.ipynb`         | [![2_01_lsa_intro_word2vec](https://mybinder.org/badge_logo.svg) ](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/AA2324/2_01_lsa_intro_word2vec/2_01_lsa_intro_word2vec.ipynb)
| `2_02_word2vec_neural_nets.ipynb`         | [![2_02_word2vec_neural_nets](https://mybinder.org/badge_logo.svg) ](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/AA2324/2_02_word2vec_neural_nets/2_02_word2vec_neural_nets.ipynb)
| `2_03_seq_processing.ipynb`         | [![2_03_seq_processing](https://mybinder.org/badge_logo.svg) ](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/AA2324/2_03_seq_processing/2_03_seq_processing.ipynb)
| `2_04_from_rnn_to_nmt.ipynb`         | [![2_04_from_rnn_to_nmt](https://mybinder.org/badge_logo.svg) ](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/AA2324/2_04_from_rnn_to_nmt/2_04_from_rnn_to_nmt.ipynb)
| `2_05_transformers_bert.ipynb`         | [![2_05_transformers_bert](https://mybinder.org/badge_logo.svg) ](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/AA2324/2_05_transformers_bert/2_05_transformers_bert.ipynb)
| `2_06_clip_diffusion.ipynb`         | [![2_06_clip_diffusion](https://mybinder.org/badge_logo.svg) ](https://mybinder.org/v2/gh/iacopomasi/NLP/HEAD?urlpath=/tree/course/AA2324/2_06_clip_diffusion/2_06_clip_diffusion.ipynb)

