 <h1 align="center" id="title">🌾 ArogyaKrishi</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6b22e194-0e53-41a1-a33c-0a0b204e8999" alt="image">
</p>


<p align="center"><img src="https://socialify.git.ci/Blacksujit/ArogyaKrishi/image?forks=1&amp;issues=1&amp;language=1&amp;name=1&amp;owner=1&amp;pulls=1&amp;stargazers=1&amp;theme=Auto" alt="project-image"></p>

### Problem statement ID: SIH - 1638 

Theme - Agri&amp;tech Background: Crop diseases can devastate yields leading to significant financial losses for farmers. Early detection and timely intervention are crucial for effective management. Description: Develop an AI-driven system that analyzes crop images and environmental data to predict potential disease outbreaks. This system will provide farmers with actionable insights and treatment recommendations to mitigate risks. Expected Solution: A mobile and web-based application that utilizes machine learning algorithms to identify crop diseases and suggest preventive measures and treatments based on real-time data.


### Our Approach :

1.) Divided  the problem statement into chunks and piecies .

2.) begain the searching with the each segement in the research papaers , you can visit [kaggle](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset) , and [UCI Machine learning Datasets](https://archive.ics.uci.edu/dataset/486/rice+leaf+diseases) , for the references and datasets,

3.) Then for the inspiration purpose we look for the several projects and repositories  available on the github and internet , you can visit , these repositories , [repo1](https://github.com/Blacksujit/Crop-Disease-Detection) , and 
 [repo2](https://github.com/Blacksujit/Green-Points) , [repo3
](https://github.com/Blacksujit/Harvestify).

4.) For the innovation and ideas , we have used [claude.ai](https://claude.ai/new) , [perlexity](https://www.perplexity.ai/) , [gpt](https://openai.com/index/gpt-4/) , [research papaers](https://paperswithcode.com/) 

5.) Determine what are the common Problem faced by the indian farmers and also researched about that for reference visit ,[ here](https://www.jiva.ag/blog/what-are-the-most-common-problems-and-challenges-that-farmers-face) , and how we can automate and mitigate it with the help of the Tech and innovation to an optimum level , such thtat the farmers life will be easier,

6.) After  we have then searched for some common agricultural practices followed and weather forecast analysis report in the past years, which will help us to analyse why the things have become  more complex for the crops to survive in the extreme consitions you can visit for the [data](https://www.nber.org/digest/202406/weather-forecasts-and-farming-practices-india)   

7.) After all the informationa has exhausted we have then move towards the most crucial part which is user behaviour , becuase it is the only thing where our product will ipmact and also , we were aware of how seamlessly we can onboard our user will create an , visibility and viability and easily accessibility of our product . so thouroughly researched about , how familier the indian farmer behaviour is  using tech , whether it is mobile application or it is and web application , we thaught every aspect in terms of the language barrier to UI complexity to the navigation e, every nity , greety is tackled so we couldn't miss out anything , for the same we have researched about the things [here](https://www.sciencedirect.com/science/article/abs/pii/S0959652624010795)

8.) At last we have iterated on our approach to look out if any breaches our setback is there or not  , if it is then we have to restart the things from scratch but there wasnt , after all these brainstorming with the team  and other things we were ready to move to the POC stage with  our idea.

9.) so thats all these was our approach for the problem statement .


### Project Structure:

```

Arogya_Krishi_MVP/
|
│
├── app.py                          # Main application file
├── requirements.txt                # List of dependencies
├── .env                            # Environment variables
│
├── models/                         # Directory for machine learning models
│   ├── RandomForest.pkl            # Crop recommendation model
│   ├── DenseNet121v2_95.h5        # Soil type prediction model
│   ├── SoilNet_93_86.h5           # SoilNet model
│   └── plant_disease_model.pth     # (if applicable) Disease prediction model
│
├── utils/                          # Utility functions and classes
│   ├── disease.py                  # Disease-related utilities
│   ├── fertilizer.py               # Fertilizer-related utilities
│   └── model.py                    # Model-related utilities (e.g., ResNet9)
│
├── uploads/                        # Directory for uploaded files
│   └── (user-uploaded images)      # Images uploaded by users
│
├── static/                         # Static files (CSS, JS, images)
│   ├── css/                        # CSS files
│   ├── js/                         # JavaScript files
│   └── images/                     # Images used in the application
│
│──── templates/                      # HTML templates for rendering
│    ├── index.html                  # Main page
│    ├── signup.html                 # Signup page
│    ├── login.html                  # Login page
│    ├── dashboard.html              # User dashboard
│    ├── crop.html                   # Crop recommendation page
│    ├── fertilizer.html              # Fertilizer suggestion page
│    ├── disease.html                # Disease prediction page
│    ├── disease-result.html         # Result page for disease prediction
│    ├── crop-result.html            # Result page for crop prediction
│    └── try_again.html              # Error handling page
│
│
│────.gitattributes
│
│────.gitignore
│
│────README.md
│
│────crop-disease-detection.ipynb
│
│────config.py
│
│
│────crop_prediction_based_on_numeric_value.ipynb
│
│
│────notebooks/
│        
│──── instance/         
│        │──── farmers_database.db
│
│
│-----images/
│
│──── data/
│          ...csv files
│
│──── Data_Preprocessed/
          .....cleaned_data
 
```
### <h2>🚀 Demo</h2>

<p>Experience ArogyaKrishi in action: <a href="https://youtu.be/yBajAQB9Kas?si=ilwix0wwiN533UYi" target="_blank">Watch the Demo</a></p>
  
  
<h2>🧐 Features  (ArogyaKrishi Comes with) :</h2>

Here're some of the project's best features:

*   Multi Crop Disease Prediction
*   Fertilizer Recommendation
*   Realtime Crop Disease Analysis Dashboard
*   Soil Type Classification
*   Farmer Data Tracking
*   Weather Analysis's and Report
*   Multilingual Support
*   Google IO translate in your language
*   Chat bot support assistance multilingual's
*   Farmer Management
*   Fertilizer Recommendations Based On Soil

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the Project</p>

```
git clone https://github.com/Blacksujit/ArogyaKrishi.git
```

<p>2. Train The Models</p>

```
run crop_prediction_based_on_numerical_value.ipynb
```

<p>3. save the Pretrained Models</p>

```
model/
```

<p>4. create the dotenv File at root of Project</p>

```
.env
```

<p>5. Add Your API Key</p>

```
OPEN_WEATHER_APIKEY=YOUR_WEATHER_API_KEY
```

<p>6. Run the Project</p>

```
python app.py 
```

<h2>🍰 Contribution Guidelines:</h2>

We are Open For Contributions please follow  
contributions.md for contributing in our Project  

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Flask
*   Machinery Learning
*   Python
*   transformers
*   deep learning
*   neural networks
*   pretrained Models
*   HTML
*   CSS
*   Javascript
*   SCSS
*   SQL-alchemy

<h2>🛡️ License:</h2>

This project is licensed under the MIT

 
