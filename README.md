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

##Anti-Piracy Notice

Note that this project does NOT 'crack' the DRM. It simplys allows the user to use their own encryption key (fetched from Audible servers) to decrypt the audiobook in the same manner that the official audiobook playing software does.

Please only use this application for gaining full access to your own audiobooks for archiving/converson/convenience. DeDRMed audiobooks should not be uploaded to open servers, torrents, or other methods of mass distribution. No help will be given to people doing such things. Authors, retailers, and publishers all need to make a living, so that they can continue to produce audiobooks for us to hear, and enjoy. Don’t be a parasite.

This blurb is borrowed from the https://apprenticealf.wordpress.com/ page.



# Not My Code.

[inAudible-NG](https://github.com/inAudible-NG/audible-activator) #For audible activator
