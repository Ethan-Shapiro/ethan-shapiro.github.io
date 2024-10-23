# Ethan Shapiro’s Portfolio

---

### League of Legends Champion Recommendation Engine

**Project overview:** As someone who has consistently struggled to make it past Diamond despite playing League of Legends for multiple years, I think it's time to see if I can get a leg up on the enemy team. One of the major ways to easily lose the game before it starts is to draft a bad team composition. If you're unfamiliar with League of Legends, it's essentially a game where two teams of 5 face off against each other with the objective of breaking into the other teams home and destroying it. I might have made it sounds worse than it actually is... In any case, before the game actually starts each team gets to choose 5 characters out of over 160 and ban (not allow) the enemy team to choose 5. In total, that's 10 chosen champions with 10 banned champions, leaving over 150 champions to choose from (that's over 590 million different combinations of teams!) With so many choices, it's hard to always pick the right 5 in order to beat the enemy. This is where my model comes in.

Based off of previous 2022 paper called ![DraftRec]([url](https://arxiv.org/pdf/2204.12750)), I've rewritten the model updating all previous code as well as collected new data taking almost 6 months of time and over 50GB of space. 

The outcome will be a new recommender system that takes into account enemy team's skill in addition to what it already accounts for. At the current time I'm training the DraftRec model to get baselines and will be enhancing the model after.

<img src="images/netflix_img.png?raw=true"/>
<img src="images/netflix_img2.png?raw=true"/>

***Technical Knowledge:*** Transformer Networks, Neural Networks, Data Cleaning, Feature Engineering

***Tools:*** Python, PyTorch, AWS EC2

![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=Jupyter)](https://github.com/m-carini/m-carini.github.io/tree/main/netflix)
![Open Slides](https://img.shields.io/badge/PPT-View_Slides-red?logo=microsoftpowerpoint)](docs/Netflix_Presentation_Notes.pptx)

---
### Flight Delay Prediction (Big Data)

**Project overview:** In my Art of Forecasting course at UCI, we were assigned a Fortune 500 company and tasked to forecast their stock price on December 31st, 2021. I was assigned Netflix as my company.

The dataset I created included historic stock prices, historic Netflix subscribers, market index values, and competitor stock values all on a monthly basis. From there I created an ARIMA model and an ETS model based on historic stock prices. Next, I created a linear regression model using lagged index and competitor stock values. I investigated various timeframes for lagging and picked the one with the best MAPE. In doing that, I found the lagged DirecTV stock value fit a near perfect negative line (image below). The final linear model performed at 0.869 R-squared. Lastly, I created a rolling 12-month average model, where I again studied various rolling values and 12 gave the best MAPE.  

The outcome is an ensemble model based on weighted MAPE. At the time of my prediction, Netflix stock was trading at $553.41. From my model, I predicted the stock value to increase 33.22% to $690.11

<img src="images/netflix_img.png?raw=true"/>
<img src="images/netflix_img2.png?raw=true"/>

---
### Steam Review Sentiment Analysis (Big Data)
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Soft Decision Trees Research Project 🌳

**Project overview:** In our final-year project, my team of two classmates and I (supervised by two professors) explored how soft decision trees (SDTs) can improve machine learning model interpretability while maintaining high performance. Unlike traditional decision trees, which make binary splits, SDTs use probabilistic decisions to handle ambiguity more effectively. Our research focused on applying feature learning techniques and leveraging the Neural Feature Matrix (NFM) to visualize and interpret the features learned by the model.

We tested our approach using datasets like MNIST and CelebA, demonstrating that SDTs could not only match the accuracy of neural networks but also offer insights into the decision-making process. On MNIST, we successfully replicated prior work, showing that SDTs could accurately classify digits and explain the decision paths. For the more complex CelebA dataset, the model identified key facial features, further validating SDTs' ability to handle real-world data. Finally, we combined our previous neural network with features learned from the SDTs and found the neural network improved its accuracy within the same amount of training epochs by 8%.

Our findings highlight the potential of SDTs to combine the flexibility of neural networks with the transparency of decision trees, improving overall accuracy in both regards. By making decision-making processes clearer, SDTs are promising for applications requiring interpretable AI, such as medical diagnoses or financial models. 

<img src="images/SDT_Example.png?raw=true"/>

***Technical Knowledge:*** Transformer Networks, Neural Networks, Data Cleaning, Feature Engineering

***Tools:*** Python, PyTorch, AWS EC2
<img src="images/dummy_thumbnail.jpg?raw=true"/>

[![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=github)](https://github.com/Ethan-Shapiro/Soft-Decision-Tree-Feature-Learning)
[![Open Website](https://img.shields.io/badge/Website-Open_Link-green)](https://ethan-shapiro.github.io/Soft-Decision-Tree-Feature-Learning/)
[![Open Paper](https://img.shields.io/badge/Research_Paper-View_Paper-2138EB?logo=googledrive)](https://drive.google.com/file/d/1JX0qreDo9ni1c6ET5OXIEipF0WAP-Xel/view)

---

### Fantasy League of Legends
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

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
