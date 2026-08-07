## NLP Assignment -1 U24AI038

Methodology
>The whole gujarati corpus is processed line by line. Each line first passes through sentence tokenizer and the tokenized sentences further passes through a word tokenizer and then the tokenized words and sentences are written in separate files. 

Sentence Tokenizer
> First all special patterns are recorded for the input text. Then sentences are tried splitting based on valid punctuation, if the valid punctuation occurs in special strings such as dates, decimals,etc. then it is extended instead of splitting.

Word Tokenizer
> Splitting all words based on whitespaces in tokenized sentences, last punctuation is handled separately.

Assignment Structure
> 
>- lab-1.ipynb : Contains the complete code for processing and tokenization using regex.
>- Summary.txt contains all evaluated metrics such as number of words, sentences, characters, average sentence length, average word length and ttr.
>- Uploaded first 5 parquet files of the complete compressed data

