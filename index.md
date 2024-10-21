# Ethan Shapiro’s Portfolio

---

### League of Legends Champion Recommendation Engine

**Project overview:** In my Art of Forecasting course at UCI, we were assigned a Fortune 500 company and tasked to forecast their stock price on December 31st, 2021. I was assigned Netflix as my company.

The dataset I created included historic stock prices, historic Netflix subscribers, market index values, and competitor stock values all on a monthly basis. From there I created an ARIMA model and an ETS model based on historic stock prices. Next, I created a linear regression model using lagged index and competitor stock values. I investigated various timeframes for lagging and picked the one with the best MAPE. In doing that, I found the lagged DirecTV stock value fit a near perfect negative line (image below). The final linear model performed at 0.869 R-squared. Lastly, I created a rolling 12-month average model, where I again studied various rolling values and 12 gave the best MAPE.  

The outcome is an ensemble model based on weighted MAPE. At the time of my prediction, Netflix stock was trading at $553.41. From my model, I predicted the stock value to increase 33.22% to $690.11

<img src="images/netflix_img.png?raw=true"/>
<img src="images/netflix_img2.png?raw=true"/>

***Technical Knowledge:*** Transformer Networks, Neural Networks, Data Cleaning, Feature Engineering

***Tools:*** Python, PyTorch, AWS EC2

[![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=Jupyter)](https://github.com/m-carini/m-carini.github.io/tree/main/netflix)
[![Open Slides](https://img.shields.io/badge/PPT-View_Slides-red?logo=microsoftpowerpoint)](docs/Netflix_Presentation_Notes.pptx)

<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
### Flight Delay Prediction (Big Data)
[Project 2 Title](/pdf/sample_presentation.pdf)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
### Steam Review Sentiment Analysis (Big Data)
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---

### Soft Decision Trees
[Project 3 Title](http://example.com/)
<img src="images/dummy_thumbnail.jpg?raw=true"/>

[![Open Code](https://img.shields.io/badge/Jupyter-Open_Files-red?logo=github)](https://github.com/m-carini/m-carini.github.io/tree/main/netflix)
[![Open Website](https://img.shields.io/badge/Website-Open_Link-2138EB)](https://ethan-shapiro.github.io/Soft-Decision-Tree-Feature-Learning/)
[![Open Paper](https://img.shields.io/badge/Research_Paper-View_Paper-green?logo=googledrive)](https://drive.google.com/file/d/1JX0qreDo9ni1c6ET5OXIEipF0WAP-Xel/view)

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
