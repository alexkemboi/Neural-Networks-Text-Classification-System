<h2 align="center">Ontology-Based Text Classification Using LSTM</h2>

### Table of Contents
[Introduction](#introduction)  
[Technologies Used](#technologies-used)  
[Dataset](#dataset)  
[Process - Flow](#process-flow)  
[Installation](#installation)  
[Implementation](#implementation)  
[Testing API](#testing-api)  
[References](#references)  

---

<h3 align="left">Ontology-Based Text Classification Using LSTM</h3>

<p align="center">
  <img width="600" src="https://user-images.githubusercontent.com/74568334/140572521-72125b9d-69c1-442e-9b74-ef60ce6a8b2e.png">
</p> 

<h3 align="left">Introduction</h3>

<p style= 'text-align: justify;'> 
This project focuses on **ontology-based text classification** using a **Long Short-Term Memory (LSTM)** model. The goal is to categorize text into predefined classes based on structured knowledge from **DBpedia**. Ontology-based learning improves classification accuracy by integrating contextual knowledge into the model.  
</p>

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/74568334/140572780-58814fa5-52aa-4b52-bd1c-cfa70dc0ba65.jpeg">
</p> 

---

<h2 align="center">Technologies Used</h2>

```
1. IDE - Pycharm  
2. LSTM - Deep Learning Classification Model  
3. GPU - P-4000  
4. Google Colab - For Training and Analysis  
5. Flask - REST API Development  
6. Postman - API Testing  
7. Gensim - Word2Vec Embeddings  
```

<p style= 'text-align: justify;'>  
🔑 **Prerequisites**  
All dependencies and required libraries are listed in **requirements.txt**  
Ensure you have **Python 3.6** installed.  
</p>

---

<h2 align="center">Dataset</h2>

<p style= 'text-align: justify;'>  
The dataset is derived from **DBpedia 2014**, consisting of 14 distinct ontology classes.  
Each class contains **40,000 training samples** and **5,000 testing samples**, totaling **560,000 training** and **70,000 testing** samples.  
Each record has three columns: **Class Index (1-14), Title, Content**  
</p>

For Dataset, click [here](#).

---

<h2 align="center">Process - Flow of This Project</h2>

<p align="center">
  <img width="1000" src="https://user-images.githubusercontent.com/74568334/140583675-fdc5484d-1886-4e2f-906e-2c1e8c187e29.png">
</p> 

---

<h2 align="center">🚀 Installation</h2>

1. Clone the repo

```
git clone https://github.com/alexkemboi/Neural-Networks-Text-Classification-System.git
```
2. Change directory to the cloned repo

```
cd Text-Classification-Using-LSTM
```
3. Create and activate a virtual environment

```
pip install virtualenv
virtualenv lstm_env
source lstm_env/bin/activate  # On Mac/Linux
lstm_env\Scriptsctivate  # On Windows
```

4. Install dependencies

```
pip install -r requirements.txt
```

---

<h2 align="center">💡 Implementation</h2>

Run the following command to start the API:

```
python app.py
```

Once running, copy the provided **IP address**, paste it into your browser, and test classification.

---

<h2 align="center">📂 Project Structure</h2>

<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/74568334/140577934-92f60e0d-c905-478e-be62-638bd6a7ad82.png">
</p> 

---

<h3 align="left">Testing API</h3>

<p align="center">
  <img width="600" src="https://user-images.githubusercontent.com/74568334/140582438-f649af76-ef70-4e79-ba2f-cd63267c7bf2.png">
</p> 

---

<h2 align="center">References</h2>
This project was adapted from publicly available resources, including [DBpedia](https://www.dbpedia.org/) and open-source GitHub repositories.
