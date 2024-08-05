# Webscraping projects

Python programs to scrape information from Google maps and LinkedIn.


## Tech Stack

- `Python`
- `Selenium`
- `BeautifulSoup`
- `SQLite3`
## Action plan

- Connecting to the drivers using 'webdriver' component of Selenium
- Inspecting the html document of webpage to locate the elements 
- Using BeautifulSoup to parse and scrape the required fields 
- Creating a tabular representation of the info using SQLite3 database  


## Project 1: Scraping restaurants info from Google maps

Creating a robust and adaptable python program to scrape specific fields from Google maps for the input query
## Features

- Automates the browser and searches for the query 'restaurants near me'
- Scrapes info on the name, address, contact number and map location of the restaurants
- Output data is stored a SQLite3 database for future analysis

## Snapshot of inspecting the html elements
![image](https://github.com/user-attachments/assets/65f8697a-df74-4a22-bbdd-38b7ac0b2c33)

## Variables

The following variables could be altered as per requirements:

`search query - eg. 'restaurants near me'`

`number of expected results - eg. restaurants count -10`


## Snapshot of output
![3](https://github.com/user-attachments/assets/b8f82e43-2326-40b3-8a37-d96ca6d15ada)





## Project 2: Scraping profiles info from LinkedIn
Creating a Python program to scrape contact information from LinkedIn profiles
## Features
- Signs in to the LinkedIn profile and searches for the query
- Scrapes the contact info of profiles from n number of pages as per requirements
- Contact info is automatically stored in database 
## Variables
The following variables could be altered as per requirements:

`sign in credentials`

`search query`

`number of pages to scrape`

## Snapshot of output
![4](https://github.com/user-attachments/assets/b67a1d47-3765-4391-a1d7-4d1e470b5f1c)



## Key learnings

Figuring out scraping functions for complex html elements with no ID, same class name or tag

eg. Scraping using unique attributes:

![image](https://github.com/user-attachments/assets/981f4ec7-1d93-400a-9d20-c068f265f237)

## Scope for optimization
- Exploring modules like ChromeDriverManager() or required browser driver managers to fit the program and run the driver in any device
- Optimizing the runtime of the program using Implicit time functions or 'expected_conditions' module to wait for the webpage to load
- Implementing exception handling with informative messages
- Probing credentials module in python
 
