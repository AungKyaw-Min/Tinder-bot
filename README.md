Tinder bot
- download and install python3
- download and unzip chromedriver
Install pip,
https://bootstrap.pypa.io/get-pip.py
Open cmd, go to the path and write 
python get-pip.py
Install virtualenv, using the following command
py -m pip install --user virtualenv

Create a virtual environment,
py -m venv env

Activating a virtual environment
.\env\Scripts\activate

Install selenium 
pip install selenium

Put the chromedriver.exe inside env/Scripts/
and also create secrets.py with
username = ‘’
password = ‘’

run it with
python -i tinder_bot.py

