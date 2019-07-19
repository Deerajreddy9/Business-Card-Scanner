# Business-Card-Scanner
update the outdated data present on card with present data from LinkedIn

# Documentation for Windows Code
# Description:
  The purpose of this project is to update the outdated information present on a visiting card by scanning the card and getting information from LinkedIn. 
Prerequisites:
•	Pytesseract
•	Tesseract OCR
•	Pillow
•	Selenium
•	Chrome WebDriver
•	PyMySQL
•	XAMPP Server


# Installation:
1.	Install pytesseract python package in command prompt by typing the following command.
								**pip install pytesseract

2.	Install tesseract OCR your preferred version from [here](https://digi.bib.uni-mannheim.de/tesseract/). Please don’t go with alpha version and download the version which we had from [here](https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-v4.1.0-elag2019.exe).

3.	Install pillow python package in command prompt by typing the following command.
								**pip install Pillow
4.	Install selenium python package in command prompt by typing the following command.
								**pip install selenium

5.	Install Chrome web driver and make sure that your chrome browser version matches with installing web driver version. You can download it from [here](http://chromedriver.chromium.org/downloads).

6.	Also in Fetch LinkedIn data please enter your LinkedIn email and password in order to fetch business card holder. 

7.	Install xampp webserver from [here](https://www.apachefriends.org/download.html). After installing start Apache and MySQL services and create a database in phpMyAdmin section and a table named persons with following columns. Or alternatively you can paste this SQL query in section and click go.

					CREATE TABLE persons (
					S_no int(10) NOT NULL AUTO_INCREMENT, 
					Name varchar(200), FName varchar(100),
					LName varchar(100), Company varchar(100),
					Position varchar(100), Mobile varchar(15),
					Website varchar(100), Email varchar(100),
					Linkedinid varchar(100), PRIMARY KEY (S_no)
					);
  
8.	Install pymysql python package in command prompt by typing the following command.
					**pip install PyMySQL

