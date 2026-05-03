# Assignment ITPM

## Install prerequisites (one-time) 
1. Install Python 3.11 or Python 3.12
2. Install Google Chrome

## Set up the project environment 
1. Open the it22192028 zip folder 
2. Save the ZIP file to your D: drive and extract it
3. Open the Command Prompt
4. In Command Prompt, navigate to the extracted folder by typing the following command: cd /d D:\it22192028

##  Install the required dependencies (one-time)
1. From the current directory in Command Prompt (i.e., D:\it22192028), run the following 
commands: • pip install -U pip 
          • pip install playwright openpyxl 
          • playwright install

## Run the Playwright script
1. From the current directory in Command Prompt (i.e., D:\it22192028), run the following 
commands:  
  • cd /d D:\IT22192028
  • python IT22192028.py --excel "IT22192028.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
