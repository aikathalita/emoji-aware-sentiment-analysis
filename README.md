\# Emoji-Aware Sentiment Analysis



Deep learning final project comparing CNN, BiLSTM, and Hybrid CNN-BiLSTM models for sentiment analysis using text and emoji data.



\## Overview



This project explores sentiment analysis on text data containing emoji representations. The objective is to compare the performance of CNN, BiLSTM, and Hybrid CNN-BiLSTM models in classifying sentiment from text and emoji-based inputs.



This project was developed as a final project for the Deep Learning course. The implementation was inspired by a research paper on Hybrid CNN-BiLSTM for text and emoji-based sentiment analysis.



\## Models Compared



| Model | Description |

|---|---|

| CNN | Extracts local text patterns and sentiment-related features |

| BiLSTM | Captures sequential context from text data |

| Hybrid CNN-BiLSTM | Combines CNN feature extraction with BiLSTM contextual learning |



\## Key Features



\- Text and emoji-based sentiment analysis

\- NLP preprocessing for Indonesian text

\- Emoji token handling as sentiment-related features

\- Deep learning model comparison

\- Evaluation using classification report and performance metrics



\## Tech Stack



| Category | Tools |

|---|---|

| Programming Language | Python |

| Deep Learning | TensorFlow, Keras |

| Data Processing | NumPy, Pandas |

| Machine Learning Utilities | Scikit-learn |

| Visualization | Matplotlib |

| Development Environment | Jupyter Notebook |



\## Repository Structure



```text

emoji-aware-sentiment-analysis/

├── notebooks/

│   └── sentiment\_analysis\_cnn\_bilstm\_hybrid.ipynb

├── references/

│   └── cnn\_bilstm\_text\_emoji\_reference.pdf

├── README.md

└── .gitignore

```



\## How to Run



Clone this repository:



```bash

git clone https://github.com/aikathalita/emoji-aware-sentiment-analysis.git

```



Move into the project directory:



```bash

cd emoji-aware-sentiment-analysis

```



Open the notebook:



```bash

jupyter notebook notebooks/sentiment\_analysis\_cnn\_bilstm\_hybrid.ipynb

```



Then run the notebook cells sequentially.



\## Dataset



The full dataset is not included in this repository due to size and privacy considerations.



\## Reference



The reference paper is included in the `references/` folder:



```text

references/cnn\_bilstm\_text\_emoji\_reference.pdf

```



\## Notes



This repository focuses on deep learning model experimentation and comparison for academic purposes.



\## Author



Thalita Aika Rahmani



