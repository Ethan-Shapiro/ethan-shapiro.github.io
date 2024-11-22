# Ethan Shapiro’s Portfolio

---

### League of Legends Champion Recommendation Engine

**Project overview:** As someone who has consistently struggled to make it past Diamond despite playing League of Legends for multiple years, I think it's time to see if I can get a leg up on the enemy team. One of the major ways to easily lose the game before it starts is to draft a bad team composition. If you're unfamiliar with League of Legends, it's essentially a game where two teams of 5 face off against each other with the objective of breaking into the other teams home and destroying it. I might have made it sound worse than it actually is... In any case, before the game actually starts each team gets to choose 5 characters out of over 160 and ban (not allow) the enemy team to choose 5. In total, that's 10 chosen champions with 10 banned champions, leaving over 150 champions to choose from (that's over 590 million different combinations of teams!) With so many choices, it's hard to always pick the right 5 in order to beat the enemy. This is where my model comes in.

Based off of previous 2022 paper called [DraftRec]([url](https://arxiv.org/pdf/2204.12750)), I'm using their model as inspiration to create a similar model with some improvements. I'm still collecting data, but so far I've been collecting data for over 4 months using an EC2 instance hitting various Riot API endpoints.

With the data I currently have, I've been exploring how to create a model that can accurately predict the winner of a match given stats of all the players in the game from their previous games and the champions each team picked. I hope to use models like these to get a preliminary understanding of how each champion affects the probability of winning a given game.

I either have made, am currently experimenting with, or plan to create the following models:
1. Basic Classification Models (Decision Trees, Logistic Regression, SVMs, etc.)
2. Basic Neural Networks (Feed Forward with Embeddings, One Hot Encodings, Increased Depth, etc.)
3. Transformer Neural Network - Match Win Prediction
4. Transformer Neural Network - Final Champion Selection Prediction
5. Transformer Neural Network - Any Stage Champion Selection Prediction

I'm currently working on both 1 and 2 to try and optimize the accuracy. Once I find that I can get a good enough accuracy with fairly basic models, I will move on to the Transformer based model to try and get more accuracy.

The ultimate outcome will be a new recommender system that takes into account enemy team's skill in addition to what it already accounts for. If you have ideas on the project or questions please feel free to send me an email!

<img src="images/Champ_Reco_league_Example.png?raw=true"/>
<img src="images/Draft Rec Model.png?raw=true"/>

***Technical Knowledge:*** Transformer Networks, Neural Networks, Data Cleaning, Feature Engineering

***Tools:*** Python, PyTorch, AWS EC2

![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=Jupyter)](https://github.com/m-carini/m-carini.github.io/tree/main/netflix)
![Open Slides](https://img.shields.io/badge/PPT-View_Slides-red?logo=microsoftpowerpoint)](docs/Netflix_Presentation_Notes.pptx)

---
### Steam Review Sentiment Analysis (Big Data)
**Project overview:** In this project, I worked with a 35GB Steam reviews dataset to sharpen my big data and NLP skills using PySpark. The primary focus was on practicing essential PySpark concepts like partitioning, groupbys, joins, and efficient computation techniques to handle large-scale data. I aimed to optimize calculations and improve processing speed, gaining valuable experience in managing big datasets.

I also explored natural language processing using PySpark NLP and John Snow Labs' NLP library. This involved cleaning the review data, performing entity recognition using pre-trained models, and conducting unsupervised sentiment analysis using TextBlob and clustering. These tasks helped me practice working with complex text data and extracting meaningful insights from unstructured reviews.

One of the main challenges I encountered was setting up PySpark locally due to compatibility issues with various package versions. After overcoming these versioning hurdles, I successfully ran the analysis and achieved my goal of applying both big data techniques and NLP in a real-world context. 
<img src="images/Steam_Pos_Word_Cloud.png?raw=true"/>
<img src="images/Steam_Reviews_Hist.png?raw=true"/>

**Technical Knowledge:** Big Data Processing, Natural Language Processing (NLP), Entity Recognition, Sentiment Analysis

**Tools:** Python, PySpark, PySpark NLP, John Snow Labs NLP, Steam Reviews Dataset (40GB)
[![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=github)](https://github.com/Ethan-Shapiro/SteamReviewSentiment)

---

### Soft Decision Trees Research Project 🌳

**Project overview:** In our final-year project, my team of two classmates and I (supervised by two professors) explored how soft decision trees (SDTs) can improve machine learning model interpretability while maintaining high performance. Unlike traditional decision trees, which make binary splits, SDTs use probabilistic decisions to handle ambiguity more effectively. Our research focused on applying feature learning techniques and leveraging the Neural Feature Matrix (NFM) to visualize and interpret the features learned by the model.

We tested our approach using datasets like MNIST and CelebA, demonstrating that SDTs could not only match the accuracy of neural networks but also offer insights into the decision-making process. On MNIST, we successfully replicated prior work, showing that SDTs could accurately classify digits and explain the decision paths. For the more complex CelebA dataset, the model identified key facial features, further validating SDTs' ability to handle real-world data. Finally, we combined our previous neural network with features learned from the SDTs and found the neural network improved its accuracy within the same amount of training epochs by 8%.

Our findings highlight the potential of SDTs to combine the flexibility of neural networks with the transparency of decision trees, improving overall accuracy in both regards. By making decision-making processes clearer, SDTs are promising for applications requiring interpretable AI, such as medical diagnoses or financial models. 

<img src="images/SDT_Example.png?raw=true"/>

**Technical Knowledge:** Matrix Calculus, Neural Networks, Soft Decision Trees, Feature Learning, Data Visualization, Neural Feature Matrix (NFM)

**Tools:** Python, PyTorch, MNIST, CelebA

[![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=github)](https://github.com/Ethan-Shapiro/Soft-Decision-Tree-Feature-Learning)
[![Open Website](https://img.shields.io/badge/Website-Open_Link-green)](https://ethan-shapiro.github.io/Soft-Decision-Tree-Feature-Learning/)
[![Open Paper](https://img.shields.io/badge/Research_Paper-View_Paper-2138EB?logo=googledrive)](https://drive.google.com/file/d/1JX0qreDo9ni1c6ET5OXIEipF0WAP-Xel/view)

---

### Fantasy League of Legends
**Project overview:** In my **Fantasy League of Legends** project, I aimed to integrate various skills learned in class and through personal study. I built a full-stack application where I used **Go** to develop a **CRUD backend** that facilitates API requests between the frontend and a prediction model. The frontend, designed with **Next.JS**, was deployed on **Firebase** as an interactive single-page application for users to select players and predict game outcomes.

For the prediction model, I collected data from the **RIOT API** and trained a **PyTorch** model in **Python**. I then deployed this model to an **AWS Lambda API** endpoint to predict match winners based on the selected players. To ensure reliability, I wrote test cases using **Cypress** for the frontend, **Testify** for the backend, and **PyTest** for the Lambda API endpoint. This project brought together everything from backend and frontend development to machine learning deployment, offering a full end-to-end experience.

**Technical Knowledge:** Data Collection (RIOT API), Machine Learning, API Development, Frontend/Backend Development

**Tools:** Python, PyTorch, AWS Lambda, Firebase, Next.JS, Go, Cypress, PyTest, Google Cloud Run

---

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
