# Auto-typer
Automatically takes the 1 minute typing test at https://thetypingcat.com/typing-speed-test/1m . Current final max wpm: 64


![alt-text](https://i.imgur.com/1bS3t9y.png)


![alt-text](https://i.imgur.com/OgrTBJh.png)

The tool makes use of Selenium to scrape data directly from the website in an automated chrome driver environment and then feeds the data to the driver which takes the input and performs the typing test.

## Requirements:
  - Jupyter Notebook
  - Selenium
  - Chrome Webdriver (included in repository)
  - Python 3.x
  
## Usage:
The script is completely automated. All it needs is manually execution of the jupyter cells. Here's some steps:
  - Create session in jupyter notebook from commandline
  - Open the ipynb file
  - Execute each cell one by one from top to bottom
  - Wait for the execution to get results

## Notes:
  - To install selenium, simply ```pip install selenium```
  - Chrome driver will pop an external automated window. Do not close that.
  
## To-do:
  - Increase wpm by changing the algorithm
  - Remove the delay between paragraphs that slows down the typing
  - Grab final wpm and display it in jupyter
