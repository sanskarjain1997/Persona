# Persona
It is the solution of the problem from IBM Hack Challenge - "Help me with my mood".
In this project, we analyse the tweets and Instagram posts of an user of previous 24 hours or more,
and perform sentiment analysis using IBM Watson Tone Analyzer. Then our algorithm provides media recommendations based on the
mood of the user to improve his/her mental health. Our algorithm is equipped with reinforcement learning which
opens a path for enhanced customized experience in future access. This is a Social-media Health Analysis and Display Engine (SHADE). Its main aim is to eliminate any negative state of mind that might have adverse effect on user's daily life.

Pre-requisities:

  Python and its packages :
  
    1. Flask
    2. Keras
    3. IBM-Tone-Analyzer
    4. Bcrypt
    5. json
    6. SQLAlchemy
    7. BeautifulSoup
    8. Python twitter REST APIs
    9. numpy
    
  Web Technologies:
  
    1. HTML
    2. CSS
    3. Bootstrap
    4. JavaScript

First install all the required packages by using following commands:

```
pip install --upgrade keras
pip install --upgrade flask
pip install --upgrade bcrypt
pip install --upgrade json
pip install --upgrade python-twitter
pip install --upgrade wastson-developer-cloud
pip install --upgrade beautifulsoup4
pip install --upgrade flask-bcrypt
pip install --upgrade flask-sqlalchemy
pip install --upgrade flask-wtf
pip install --upgrade numpy
```

Now run the flask app to host the website locally. Usually, hosting address is : 
```
127.0.0.1:5000
```
![LoginPage](./Screenshots/LoginPage.PNG)

Open the broswer (Chrome or Firefox is recommended) and enter the above the address as URL.
Here, you will get Login page. Enter the details to go to your dashboard. If you are using this
app for the first time, do registration first. Enter the following address to register as new user:

```
127.0.0.1:5000/register
```

![RegistrationPage](./Screenshots/RegistrationPage.PNG)


Once you get into the dashboard, you can set the time period for analyzing your tweets and instagram posts. Also, you can see
your twitter username and Instagram username at left hand side. A Big Juicy Red Button, saying "See Suggestions", is at the mid-bottom and a one-line phrase/quote is at right hand side, which is given in accordance to the prominent mood of the user.

![Dashboard](./Screenshots/Dashboard.PNG)


### Phrases/Quotes corresponding to dominant emotion
```
For Anger : Calm Down.
For Sadness : Its been a long day, I suppose.
For Joy : Nice day. isn't it?
For Tentative : Go with what your heart says.
For Fear : Don't be scared. Everythings gonna be alright
For Confident : You are looking an inch taller.
For Analytical : Its good to be analytical.
```

When you'll click on the "See Suggestion" button, you will get redirected to our recommendation page. Here, all the Videos, Quotes, Memes, Images, Songs, Articles, Stories which are suitable for the user are listed in a simple format. 

![RecommendationPage](./Screenshots/RecommendationPage.PNG)
