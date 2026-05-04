# Assignment ITPM

## Install prerequisites (one-time) 
1. Install Python 3.11 or Python 3.12
2. Install Google Chrome

## Set up the project environment 
1. Open the Command Prompt
2. In Command Prompt,Clone the repository:
          git clone https://github.com/rashmyshiraj/IT22192028_itpm_assignment.git
3. Navigate to the cloned folder:
          cd IT22192028-Assignment1

##  Install the required dependencies (one-time)
1. From the cloned directory in Command Prompt, run the following commands:
          • pip install -U pip 
          • pip install playwright openpyxl 
          • playwright install

## Run the Playwright script
1. From the cloned directory in Command Prompt, run the following commands:  
  • python IT22192028.py --excel "IT22192028.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
