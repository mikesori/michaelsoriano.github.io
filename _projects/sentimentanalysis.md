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
