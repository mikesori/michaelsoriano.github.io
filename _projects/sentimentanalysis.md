---
title: "Sentiment Analysis Project"
excerpt: "This post contains the completed documentation for my Sentiment Analysis project. This project is seen as an experiment with Sentiment Analysis and R and should be taken as an incomplete work-in-progress."
collection: projects
---
Attached to this post is a link to the Google Colab notebook for the Sentiment Analysis project. Please feel free to experiment with this project. I will also be providing a link to a Google Drive folder with the materials to complete the Analysis. 

# Links for Download
- [Star Trek episode .txt](https://drive.google.com/drive/folders/1x-KcEcs4mqBE0MD9XUsQKnb4cIEj4WCd?usp=sharing)
- [Colab Notebook - Sentiment Analysis](https://colab.research.google.com/drive/1cxAWtJDLfy2NLXl4TxE6mAYBCAqNJGal?usp=sharing)

Below, I have provided the opening remarks found in the Colab Notebook.

# Introduction
This notebook serves as the preliminary documentation for a sentiment analysis project using Star Trek: The Next Generation scripts.

A typical Star Trek: The Next Generation script contains a teaser and four acts. While the ideal project seeks to investigate the structure of a Next Generation script, with careful attention paid to the affective and narratological structuration of individual acts, this smaller iteration of the project seeks to experiment with a basic sentiment analysis of Season 1---and a small selection of episodes from Season 2---of Star Trek: The Next Generation. Again, I consider this to be a small experiment with Sentiment Analyses of television scripts.

Star Trek is known for its imbrication with utopian speculative fiction. Utopia, in its broadest generic utility, is oft-associated with positivity, possibility, and futurity. This project posits a simple hypothesis using the sentiment analysis postive/negative binary: A Star Trek: The Next Generation script will conclude in Act IV with a positive affective valence. While this may seem for even the most casual Next Generation viewer to be self-evident, I hope to build upon this project to consider what fan communities have referred to as New Trek. New Trek includes recent serial streaming television programs as Star Trek Discovery and Star Trek Picard. In this later investigation, I aim to investigate the affective structuration of episodic and serial programming. Here, I posit that serial programming is incentivized to conclude "negatively" to entice viewers to return next week for "positive" narrative satisfaction. In this particular Sentiment Analysis, we will be conducting an analysis of Season 1 and select episodes from Season 2 of the program. As this project develops, I aim to conduct a broader scale analysis of the multple seasons of Star Trek: The Next Generation.

Again, the prior remarks look towards a future possibility for this project. As it stands, this notebook provides the preliminary technical schematics for reproducibility. Here, I detail the steps taken to "tidy" Star Trek: The Next Generation scripts and the initial results of my sentiment analysis.

## Disclaimer and Additonal Remarks
A final note: I have been having a difficult time using Anaconda (a software recommended by Jerry to produce a local installation of Jupyter notebook using an R kernel) so for the time being all of the materials will be pulled from my computer. The difficulty is that this makes replication difficult. To be clear, for these purposes I have simply attached my .txt files to a folder in "Content" titled "Star_Trek". In the "Star_Trek" folder there are individual folders for each episode of the series. This file system is organized as follows: "st.0XXX". The first "X" would function as the season number. The additional two "X's" are for episode number. For example, if I would like to analyze Season 1, Episode 18 of Star Trek I would look for "st.0118". Additionally, much of the information available here was completed with the help of Jerry Bonnel and the Tidy Text Mining textbook.

# Bibliography
- Abhishek, Kumar, et al. “Sentimental Analysis for Movie Reviews.” _International Journal of Advanced Research in Computer Sciences_, vol. 11, no. Special Issue 1, May 2020, p. 6.
- Ames, Melissa R. _Small Screen, Big Feels: Television and Cultural Anxiety in the 21st Century_. The University Press of Kentucky, 2020.
- Denis, Alexandre, et al. “Visualization of Affect in Movie Scripts.” _1st International Workship on Empathic Television Experiences_, HAL Open Science, 2015, p. 4, [https://hal.science/hal-01099668](https://hal.science/hal-01099668).
- Efros, Alexei, et al. _A Tool for Computational Analysis of Narrative Film_. UCB/EECS-2018-102, University of California, Berkeley, 7 Aug. 2018, p. 12, [https://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-102.pdf](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-102.pdf).
- Frangidis, Paschalis, et al. _Sentiment Analysis on Movie Scripts and Reviews: Utilizing Sentiment Scores in Rating Prediction_. IFIPICT, 2020, p. 8, [https://doi.org/10.1007/978-3-030-49161-1_36](https://doi.org/10.1007/978-3-030-49161-1_36).
- Green, Shiao-li. “Sentiment Analysis - A How-to Guide with Movie Reviews.” _Towards Data Science_, 20 Dec. 2019, [https://towardsdatascience.com/sentiment-analysis-a-how-to-guide-with-movie-reviews-9ae335e6bcb2](https://towardsdatascience.com/sentiment-analysis-a-how-to-guide-with-movie-reviews-9ae335e6bcb2).
- Haughton, Dominique, et al. _Movie Analytics: A Hollywood Introduction to Big Data_. Springer, 2015.
- Hołobut, Agata, and Jan Rybicki. “The Stylometry of FIlm Dialogue: Pros and Pitfalls.” _DHQ: Digital Humanities Quarterly_, vol. 14, no. 4, 2020, p. 23.
- House, Diane. “Television Script Format.” _Movie Outline_, [https://www.movieoutline.com/articles/television-script-format.html](https://www.movieoutline.com/articles/television-script-format.html). Accessed 16 Apr. 2023.
- Msnil, Grégoire, et al. _Ensemble of Generative and Discriminative Techniques for Sentiment Analysis of Movie Reviews_. [https://arxiv.org/abs/1412.5335](https://arxiv.org/abs/1412.5335). ICLR 2015.
- Rábay, Kristóf. “NLP on The Office Series.” _Towards Data Science_, 29 May 2020, [https://towardsdatascience.com/nlp-on-the-office-series-cf0ed44430d1](https://towardsdatascience.com/nlp-on-the-office-series-cf0ed44430d1).
- van Cranenburgh, Andreas. _An Empirical Evaluation of Sentiment Analysis on Movie Scripts_. [https://andreasvc.github.io/dhbenelux2020talk.pdf](https://andreasvc.github.io/dhbenelux2020talk.pdf). DHBenelux, University of Groningen.
