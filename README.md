[![Build Status](https://travis-ci.org/VickySteeves/personal-website.svg?branch=master)](https://travis-ci.org/VickySteeves/personal-website)

# Nikola-Site

To install Nikola on other computers:

````
virtualenv venv -p `which python3.5`
source venv/bin/activate
pip install 'Nikola[extras]'
````

Navigate to the folder with this repo. To start the site:
````
nikola build
nikola serve -b
````
