# ntu-automate-star-wars(ENHANCED)
This is a modified version of the original ntu-automate-star-wars forked from ryskoss.

## Functionality
* **Automatically logs in and register courses**
* When STARs log you out, it will automatically quit and log in again 
* Continously clicks until registration begins
* Only works for Cores or prescribed and NOT UE at this point of time since it will not choose but just add

It will stop running only when all the courses have been registered (There are no courses saying "no more vacancies")

## prerequisites
* python
* pip
* **MUST DO:** Make sure all the cores or ger core or major pe that you need are **saved to plan 1 as default**. Try to remove UEs (Those need to choose ranks) 

## set up & run
1. Clone or Fork or download this github
2. Go to chrome settings and go to about chrome. Check chrome version
3. Go [here](https://chromedriver.chromium.org/downloads) and download chrome driver with correct version
4. Unzip the downloaded chromedriver and copy the directory it is saved in

## Run 
There are 2 ways to run. 
#### A) Use batch file
double click automateStars.bat file to run

#### B) use cmd
```
pip install -r requirements.txt
python automateStars.py
```
To run this **without opening up chrome physically** (virtually carried out), append argument `-bg` like shown below
```
python automateStars.py -bg
```

## Author
*Developed by Ko Seoyoon in 2020 June*
Feel free to fork and develop it further. Please credit original author.
