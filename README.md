# English-to-French Translation Chatbot

## Introduction
This project is a simple English-to-French translation chatbot built using Hugging Face Transformers. The chatbot translates English sentences into French automatically using a pre-trained NLP model.

Instead of training a translation model from scratch, this project uses the pre-trained model:

Helsinki-NLP/opus-mt-en-fr

Users can enter English sentences and receive French translations interactively.


## Features

- Translate English text into French
- Interactive chatbot interface
- Uses pre-trained NLP models
- Real-time translation responses
- Simple implementation using Python


## Technologies Used

- Python
- Hugging Face Transformers
- PyTorch
- SentencePiece
- Google Colab


## Model Used

Pre-trained translation model:

Helsinki-NLP/opus-mt-en-fr


## Installation

Install required libraries:

```bash
pip install transformers sentencepiece torch
```

## Usage

Run the notebook in Google Colab or Jupyter Notebook.

Execute all cells and enter English text when prompted.

Example:

Input:

```text
Hello, how are you?
```

Output:

```text
Bonjour, comment allez-vous ?
```

Type:

```text
exit
```

to stop the chatbot.

---

## Project Structure

```text
English_to_French_Translation_chatbot.ipynb
README.md
```


## Author

CHENYIYUE 
UPM Computer Science Student
