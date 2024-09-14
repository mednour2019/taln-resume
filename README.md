#Text Summarization Using Natural Language Processing (NLP)
Technologies: NLP,python,pandas

Description
For a scholarship project, the goal is to develop a system that takes an input text and processes it using various Natural Language Processing (NLP) techniques such as stemming, lemmatization, and others. The system will then analyze the text to identify key phrases and assign weights to these phrases. Finally, it will generate a concise summary (resume) of the original text.

Key Features
Reading File in Python: Load and read the input text file using Python.
Regular Text Substitution: Replace special characters in the text with spaces to standardize the input.
Split Sentences: Divide the text into individual sentences for easier processing.
Tokenization of Words: Break down sentences into individual words (tokens).
Lemmatization of Words: Convert words to their base or root form using lemmatization.
Frequency Calculation of Words: Calculate the frequency of each word in the text.
Scoring of Each Word: Assign a score to each word based on its frequency and importance.
Weight of Sentences: Calculate the weight of each sentence based on the scores of the words it contains.
Identify Most Frequent Sentences: Select the most important sentences based on their weights.
Final Result: Summary Text: Generate the final summary (resume) of the text using the most important sentences.
