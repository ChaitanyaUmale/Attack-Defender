# Attack-Defender
Prevents HID attack/keystroke attack performed by a pre-programmed physical thumb drive ie. Rubber Ducky.

#How it works
The software detects and blocks the Rubber Ducky before any severe damage to the system.
Alerts the administrator via an email with the log file.
The log file contains the registered keystrokes of the Rubber Ducky.
The blocked keyboard can be unblocked by pressing a combination of hot keys ie. 'esc + e + m'.

#Instructions
Change the sender's email address in the 'mailto.py' file with the organization's email id.
The email id to be put into the source code has to have third party access enabled and multi-factor authorization disabled.
Change the email id of the Administrator in file 'detect_keys.py'. Replace the 'admin@axample.com' with the Administrator's email ID.
You can change the hot keys to unblock the keyboard in the source code.

#Note
Press and hold the combination of the keys to unblock the keyboard.
