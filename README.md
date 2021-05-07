# Aggregator_Project
This is a website that is used for scraping the data from three different websites: Tapaz, Amazon, Aliexpress respectively. It is divided several directories.
Most of the codes are in app directory. The website is written as an integration: a monolitic website and its scrapping part. All the work that does scrapping part, is done inside the FrameWork directory.

FrameWork directory:
  1) web_engine.py file holds the the class that will be inherited in the webdriver.py .
  2) filter.py and sort.py, as their names indicate are filtering and sorting the data .
  3) Eventually, in webscrapping.py file, the results are displayed

app directory:
  1) It consists of several directories including FrameWork.
  2) FrameWork.png file is an UML diagram according to which, the project will be created.
  3) __init__.py file brings everything together.
  4) errors.py file will give more tidy results when something crashes in the program.
  5) forms.py is used for registration part, login part, and edit profile part of the website.
  6) routes.py is for displaying monolitic website.
  7) models.py is a model user with his or her posts and profile.
templates directory:
  This directory holds files related to front-end part of the website. 
