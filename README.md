![image](https://logodix.com/logo/44715.png)

# Project Title 
Data mining project - Checkpoint #1

#  Scope
In this step we web scrape data of 100 restaurants from OpenTable website.

main URL: https://www.opentable.com/m/best-restaurants-in-america-for-2017/

We create a main class 'Restaurant', and for each one of the methods is a feature we extract from the restaurant link 
where HTTP requests are done by requests library and then we parse HTML pages using BeautifulSoup library.

# Authors 
Ariela Strimling and Areej Eweida

## Installation
[This file](https://github.com/arstrim/project/blob/master/requirements.txt) should be downloaded to later install it like:
```
pip install -r requirements.txt
```
---
Notes:
When scrapping from scratch,please delete all content of the folder data. Do not delete the folder data
Future work: check if the path exists of every folder in the project

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
