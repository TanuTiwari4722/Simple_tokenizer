# Simple_tokenizer

This project implements a custom, lightweight word-level tokenizer using only Python and regular expressions. It is designed to demonstrate how tokenization works under the hood, without relying on external NLP libraries.

**Features**

* Regex-based Tokenization: Splits text using punctuation and whitespace with support for complex patterns (e.g., handling "--" and punctuations).

* Vocabulary Building: Creates a sorted vocabulary from a text corpus and maps each token to a unique integer ID.

**Bidirectional Mapping**

encode(text) → Converts input text into a list of token IDs.

decode(ids) → Reconstructs original text from token IDs, handling punctuation spacing cleanly.

* Ignores Unknown Tokens: Tokens not in the vocabulary are skipped silently during encoding.

* Clean Preprocessing: Strips empty tokens and redundant whitespaces during tokenization.
