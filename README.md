# Translator-text-to-text-
This model can be used for translation and text-to-text generation.    


How to Get Started With the Model
from transformers import AutoTokenizer, AutoModelForSeq2SeqLM

tokenizer = AutoTokenizer.from_pretrained("Helsinki-NLP/opus-mt-ru-en")

model = AutoModelForSeq2SeqLM.from_pretrained("Helsinki-NLP/opus-mt-ru-en")


Training
Training Data
Preprocessing
Pre-processing: Normalization + SentencePiece

Dataset: opus

Download original weights: opus-2020-02-26.zip

Test set translations: opus-2020-02-26.test.txt


Model Type: Transformer-align
Language(s):
Source Language: Russian
Target Language: English
License: CC-BY-4.0
Resources for more information:
GitHub Repo
