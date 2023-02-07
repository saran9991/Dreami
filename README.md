# Dreami    

View the live app hosted at: [www.dreami.day](https://www.dreami.day).


## Project Description
Thus far the act of interpreting dreams has only been performed by human beings. The end product of our project is a trained model that automatically generates texts of dream interpretations. On the platform we present here, we collect data on dream-texts, relevant background information, the state the dreamer woke up in, texts of dream interpretations, and ratings of those interpretations. We use the data to train a transformer model ( **OpenAI's GPT-3** ) to generate highly rated texts of dream interpretations. 

Human computation can be defined as "[…]the idea of using human effort to perform tasks that computers cannot yet perform, usually in an enjoyable manner".  In a human computation system, humans and computers work hand in hand to achieve a goal that neither one of them can achieve individually. To our knowledge, there is no publicly available natural-language- generation model for interpreting dreams. 
Our platform is a human computation system for the following reasons: 
* The human mind produces dreams during sleep. 
* Dreamers translate their dreams into written texts and post the texts on our platform. 
* They provide information on their current life situation and wakeup-state. 
* Other users read those texts, think about proper interpretations, and post those as texts on the platform. 
* The dreamers rate the interpretations with respect to helpfulness and the degree of insight gained. 
* Users trigger the generation of automatic dream interpretations, read those interpretations and rate them. 
* Users flag too offensive or undignified interpretations our model might generate.

## Installation
To run this project and run it in your system, follow these steps:

### 1. Clone the repository
Clone this repository using 
```
git clone https://gitlab.lrz.de/shyam/dreami.git
```

### 2. Install the requirements
Change the working directory to the project folder and install the libraries mentioned in requirements.txt using
```
pip install -r requirements.txt
```

### 3. Run the program
Run the main.py file using the command:
```
python main.py
```

### 4. View the website launched
On running the program, the website is launched on localhost at port 5000. This can be viewed by visiting http://127.0.0.1:5000/


## Authors and acknowledgment
* Website: Elma Elza Thomas & Shyam Shankar Hemachandran Rani
* AI model: Dario Nališ & Sarandeep Singh
