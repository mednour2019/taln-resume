# Text Summarization Using Natural Language Processing (NLP)
# The project is in master Branch
# Description
For a scholarship project, the goal is to develop a system that takes an input text and processes it using various Natural Language Processing (NLP) techniques such as stemming, lemmatization, and others. The system will then analyze the text to identify key phrases and assign weights to these phrases. Finally, it will generate a concise summary (resume) of the original text.

![Screen Shot](https://prtfnour.vercel.app/images/portfolio/project21.jpg)

## Demo 

 - Text Original :![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/1.origintext.PNG)
- Regular Expression : ![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/2.cleaniing.PNG)
- Divide Senteces : ![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/3.TransfSentBySpacy.PNG)
- Split Senteces:![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/4.SplitSentce.PNG)
- Split to words: ![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/5.wordsspacy.PNG)
- Lemmatization :![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/6.lemma.PNG)
 - Frequenceis words:  ![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/7.frequencisWord.PNG)
- Score of each words: ![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/8.scoreeachword.PNG)
- Weight of each sentence: ![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/10.heightsenteces.PNG)
- most frequent sentences:![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/11.top5frequencies.PNG)
- Final Result :![Screen Shot](https://prtfnour.vercel.app/gallery-viewer/images/project21/12FinalResult.PNG)

## Features

- 🧩 Reading File in Python: Load and read the input text file using Python.
- 🧩 Regular Text Substitution: Replace special characters in the text with spaces to standardize the input.
- 🧩 Split Sentences: Divide the text into individual sentences for easier processing.
- 🧩 Tokenization of Words: Break down sentences into individual words (tokens).
- 🧩 Lemmatization of Words: Convert words to their base or root form using lemmatization.
- 🧩Frequency Calculation of Words: Calculate the frequency of each word in the text.
-  🧩Scoring of Each Word: Assign a score to each word based on its frequency and importance.
-  🧩Weight of Sentences: Calculate the weight of each sentence based on the scores of the words it contains.
-  🧩Identify Most Frequent Sentences: Select the most important sentences based on their weights.
-  🧩Final Result: Summary Text: Generate the final summary (resume) of the text using the most important sentences.




## Getting Started

### Prerequisites

- Python
-NLP
Pandas

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Mohamed Nour KHammeri - [@My-Web-Site](https://prtfnour.vercel.app) - mednour.khl@gmail.com

Project Link: [https://github.com/mednour2019/taln-resume](https://github.com/mednour2019/taln-resume)
