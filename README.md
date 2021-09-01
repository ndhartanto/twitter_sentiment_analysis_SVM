<!-- PROJECT LOGO -->
<p align="center">
  <h1 align="center">Text Mining Implementation for Sentiment Analysis of Indonesian Public Opinion on Trade Relations Between Indonesia and China With Naive Bayes and SVM Text Classification</h1>
</p>



<!-- TABLE OF CONTENTS -->
  <h2 style="display: inline-block">Table of Contents</h2>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>



<!-- ABOUT THE PROJECT -->
## About The Project

<p align="justify">
    The purpose of this research is to implement text mining for sentiment analysis of Indonesian public opinion on trade relations between Indonesia and China with Naïve Bayes and Support Vector Machine (SVM) text. The research begins with data crawling from Twitter; data cleansing; translating the text into English using GoSlate; sentiment analysis using VADER or TextBlob; data pre-processing with NTLK or SpaCy with or without lemmatization; splitting the data for training and testing using the Hold-Out method with 70:30 and 80:20 ratio; text classification with Naïve Bayes and SVM; and calculating the accuracy, precision, recall, and f-measure based on confusion matrix.
</p>

<p align="justify">
    The results showed that SVM text classification consistently has a higher accuracy rate than Naive Bayes. The combination that produces the highest level of accuracy is using VADER, SpaCy without lemmatization, and SVM with 80:20 training:testing ratio, resulting in 76.40% accuracy, 74.55% precision, 76.4% recall, and 74.48% F-measure.
</p>

![Poster][poster]

### Built With

This project was built using:

* [Twint](https://github.com/twintproject/twint)
* [nest_asyncio](https://github.com/erdewit/nest_asyncio)
* [goslate](https://pypi.org/project/goslate/)
* [pandas](https://pandas.pydata.org/)
* [NLTK](https://www.nltk.org/)
* [spaCy](https://spacy.io/)
* [NumPy](https://numpy.org/)
* [scikit-learn](https://scikit-learn.org/stable/)
* [seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)

<!-- CONTACT -->
## Contact

ndhartanto1@gmail.com

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<!-- MARKDOWN LINKS & IMAGES -->
[poster]: images/posterskripsi.jpg
