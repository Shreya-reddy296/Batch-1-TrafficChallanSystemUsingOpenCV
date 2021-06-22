# Batch-1-TrafficChallanSystemUsingOpenCV
TRAFFIC CHALLAN SYSTEM USING OPENCV

SOFTWARES REQUIREMENTS- 
Operating System : Windows 64 bit 
Pre-requisite Software : Python 3.8.0
IDE : IDLE
Python Modules : Pandas,Tkinter,Tesseract

HOW TO SETUP EXECUTION-
1)Firstly we need to execute main.py file which preprocesses the car with image processing techniques and extracts the text from license plate and sends that text to emailDelivery.py file.
2)Secondly, in emailDelivery.py it takes the license plate number and sends that number to receiver.py. It also imports smtb and ssl modules for sending aunthentic and secure mail.
3)Thirdly, receiver searches the mail-id of that particular person license_plate number in .csv file and sends him an email, stating to pay challan for wrong parking. 4)An email will be received by the receiver.

PREREQUISITES- Python Installation: Python: Version 3.8.0: Downloading:

Goto https://www.python.org/downloads/
Click the Download Python 3.8.0 button. The File named python-3.8.0.exe should start downloading into your standard download folder. The file should appear as: python-3.8.0.exe.
Move this file to a permanent location, so that you can install Python. Installing:
Double-click the icon labeling the File python-3.8.0.exe. 2.A Python 3.8.0 (64-bit) Setup pop-up window will appear.
Highlight the Install Now (or Upgrade Now) message, and then click it.
A new Python 3.8.0 (64-bit) Setup pop-up window will appear with a Setup Progress message and a progress bar. During installation, it will show the various components it is installing and move the progress bar towards completion.
Click the Close button. Python should now be installed.

DATABASE- A database is required with license plate registered mail-id's.

Required Libraries Installation: All the required libraries can be installed using pip installer

Go to command prompt and run the following commands
pip install opencv-python
pip install pandas
pip install tkinter
pip install pytesseract If the results are printed out without any errors, you have installed all libraries successfully.
