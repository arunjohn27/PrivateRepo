# PrivateRepo
For personal use
This Automation Framework used is Robot Framework using Python, 
Robot Framework is a generic open source automation framework for acceptance testing, acceptance test driven development (ATDD), and robotic process automation (RPA). ... The core framework is implemented using Python, supports both Python 2 and Python 3, and runs also on Jython (JVM), IronPython (. NET) and PyPy.

Prerequisites For running Robot Framework, 

you need to have Python installed in the system(version 3.8)

Install Robot Framework library,SeleniumLibrary from Cmd

Install browser driver, here chrome driver from link : https://chromedriver.chromium.org/downloads which aligns with your chrome browser version and place the file in Python\Python38-32\Scripts\ folder

Set the System Environemnt variable Path of Python and Python/Scripts as: C:\Users\%user%\AppData\Local\Programs\Python\Python38-32\Scripts\
and 
C:\Users\%user%\AppData\Local\Programs\Python\Python38-32\

and run the command : robot --outputdir \Test_Automation\Results Propine_TestSuite.txt from the terminal ensuring the current location of terminal is in the TestScripts folder to execute the script
