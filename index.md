# Ethan Shapiro’s Portfolio

---

# League of Legends Match Outcome Prediction  

## **Project Overview**  
Predicting the outcome of a **League of Legends** match before it starts is a challenging problem. The goal is to analyze player and champion statistics to determine **win probabilities** and understand the key factors that contribute to a team's success.  

This project would be a first stpe to improving **matchmaking balance**, which in turn can give a more enjoyable player experience by making games feel more competitive. This project was inspired by the **DraftRec** paper ([DraftRec](https://arxiv.org/pdf/2204.12750)), but with modifications tailored to win prediction rather than draft recommendations.

## **Dataset Overview**  
- **Match History Data**: 400,000+ matches, focusing on player picks, bans, and game results.  
- **Player Performance Data**: 12M+ matches, capturing in-game stats like kills, deaths, and gold earned.  
- **Feature Engineering**: Normalization, Z-scoring, and role-based differences to improve model predictions.  

## **Best Performing Models**  
### **1️⃣ Logistic Regression (Baseline Model)**  
- **Accuracy: 56.04%**  
- Performed better than more complex models like **Random Forest** and **XGBoost**, suggesting strong **linear relationships** in the data.  

### **2️⃣ Final Hybrid Neural Network**  
- **Accuracy: 57.34%**  
- Combined a **deep learning component** (role-based strength modeling) with a **linear component** (team stat differences), outperforming both methods individually.  

## **Key Findings**  
✅ **Linear relationships matter** – Logistic Regression outperformed many non-linear models.  
✅ **Role-based skill differences are important** – Player strength in specific roles significantly impacts outcomes.  
✅ **More complexity isn't always better** – The most complex transformer models underperformed.  
✅ **Hybrid models are effective** – Combining neural networks with traditional models improved accuracy.  

## **Lessons Learned**  
🔹 **Start simple** – Establishing a baseline made it easier to measure real improvements.  
🔹 **Plan data collection carefully** – Fetching match history **scaled exponentially**, making early prototyping crucial.  
🔹 **Evaluate models beyond a single metric** – Looking at raw precision, recall, and accuracy helped identify true performance gains.  

## **Technical Knowledge & Tools**  
✅ **Technical Skills**: Machine Learning, Neural Networks, Data Cleaning, Feature Engineering  
✅ **Tools Used**: Python, PyTorch, Riot API, AWS EC2, Scikit-Learn  

For more details, refer to the PowerPoint! 🚀  


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
