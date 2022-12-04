# Keylogger Using Python

Keylogger is a program with which we monitor keystrokes. These keystrokes will be stored in a log file. We can record sensitive information like username and password using this keystroke. The Python script will do the following:
- Listen to keystrokes in the background.
- Whenever a key is pressed and released, we add it to a global string variable.
- Every N minutes, report the content of this string variable either to a local file (to upload to FTP server or use Google Drive API) or via email.

# Usage
```
sudo apt-get update
sudo apt-get install python3
sudo apt-get install python3-pip
pip install keyboard
pip install secure-smtplib

git clone https://github.com/mrinalprakash45/Keylogger
python3 keylogger.py
```


