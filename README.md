
# Accidents and traffic management in real time in Tunisia






## License
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)



## Contributing

Contributions are always welcome!




## Installation

Make sure to install the dependencies for react using npm or axios. As well as a nodeJs runtime environment in order to execute it.

```bash
  npm i

```
For python dependencies , make sure to install the relevent dependencies using pip or pip3. 

pip install selenium

pip install beautifulsoup4

pip install pymongo

pip install flask


## Deployment

This app runs on port 5000. start the data recuperation first by running the Twitter scrapping and then the press scrapping. 

```bash
  python recupDeTwit.py
  python recupDeSite.py
```
For twitter, in order to scrap , you should use an account of your own (it's hard to detect it as a robot ,at least for me this code never blocked my account because it simulates human behavior)
add your email and password in the code of twitter
if the scrapping page moved to providing name of the account, replace that in the code too.


in order to run the frontend run the react app with 

```bash
  npm start
```

to run the backend python make sure to activate the flask virtual environment and then run the backend. Make sure that you have mongodb installed. 

```bash
venv\Scripts\activate
python app.py
```


## Screenshots
<img src="/img/db_event.png" width="580"/>

## Optimizations

For Optimizations and future steps , it would be great to do extractions from the tweets or the texts of the websites to extract keywords.
These keywords can be implemented and linked to a google map in order to have a real time google map of problems in roads. 

