# Detecting-ASD-with-NLP-and-Deep-Learning
Detecting ASD with NLP and Deep Learning

Autism Spectrum Disorder diagnosis is a long and challenging process. It involves analyzing many developmental aspects of the patient before making a final decision. Thanks to the emergence of Artificial Intelligence techniques in the past years, it is now possible to automate and accelerate some of the diagnosis steps. In this study, we refer to various forms of data from the Talkbank database and use Natural Language Processing and other Deep Learning Techniques to detect Autism Spectrum Disorder. This section presents the methodology we followed in our project along with the obtained results. 
Recently, Machine Learning techniques have been found useful by health professionals to diagnose different diseases early and effectively. In fact, ML algorithms use various and large data to learn patterns and detect abnormalities within the human body and/or behavior. In this context, we are attempting to detect autism spectrum disorder using Deep Learning techniques such as Natural Language Processing, relying principally on abnormal speech patterns among children.


In this study, we used data from Talkbank, which is a large open-source multilingual corpus dedicated to researchers around the world to analyze human communication. Two databases of this corpus were useful for our project: CHILDES and ASDbank, as they contain transcripts of typically developing children and children with ASD as well as their information. 
183 transcripts were retrieved from the Talkbank website, containing, each, a dialogue between a child, their parent, and/or an investigator recorded during a one-hour free toy play session. We used the python library Selenium as a web scraping tool to get 97 TD¹ transcripts and 86 ASD² transcripts. These transcripts were first cleaned then tokenized to be later fed to our recurrent neural network. 

The first notebook is for scraping data from the open source database: talkbank (https://www.talkbank.org/), using Selenium.

This notebook is for training an tensorflow model that classifies transcripts to predict if a child has ASD from their speech patterns.
