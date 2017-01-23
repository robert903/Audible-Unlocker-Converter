# Audible-Unlocker-Converter
## Decrypts audible audiobooks aax to m4a or any format


#Quick Setup

Python 2 is required along with Selenium, Requests, ChromeDriver, and Google Chrome.


- pip install requests  # use "easy_install" if pip is missing
- pip install selenium


Download and extract the correct ChromeDriver zip file from [Here](https://sites.google.com/a/chromium.org/chromedriver/downloads) to this folder.

Download Google Chrome from https://www.google.com/chrome/ and install it on your computer.

#usage 

- python audible-activator.py --debug #this starts in debug mode so you can manually enter your email and password to pass robot check

- COPY RESULTING ACTIVATION BYTES FROM CONSOLE

- Goto audible library. change to ENHANCED and download aax.

- RUN --- ---        ./ffmpeg -y -activation_bytes ACTIVATION_BYTES -i audiobook.aax -c:a copy -vn audiobook.m4a

