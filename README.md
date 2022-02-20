# TokSeg
Multilngual tokenizer and sentence segmenter supporting 20 languages


Usage:

```python3
from tokseg import Split

sp = Split()

text = 'Some random text in any language'

lang = 'en'

# lang is the 2 characters ISO 639 language code

tokens = sp.tokenize(text, lang)

sentences  = sp.segment(text, lang)


```
