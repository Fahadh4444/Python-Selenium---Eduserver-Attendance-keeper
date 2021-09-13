# Eduserver Attendence Keeper Using Python Selenium
Hey guys, Nowadays it has become hard to mark attendance in Eduserver, due to our negligence or some other works we have, someties we miss it in just seconds. I have a solution for that, this repo contains Python code that automates marking attendence in Eduserver.

### **After downloading this repo all have to do some steps in order to run it properly**

- Install selenium package in our pc
- using the command in cmd terminal or in GIT Bash `pip install selenium`
- Then you have to download the web driver for chrome. Follow this link to [download it.](https://sites.google.com/a/chromium.org/chromedriver/)
  
  `NOTE: Download Chrome webdriver which supports your PC's Chrome browser(by check your browser current version).`
- After unzipping the downloaded folder, copy chromewebdriver.exe, paste somewhere in PC except in C drive and copy its path(address).
- Now open our repo in the code editor to make some changes in the code

    ![https://github.com/ShyamKumar1/Python-Selenium---Eduserver-Attendance-keeper/raw/main/requiredChanges.PNG](https://github.com/ShyamKumar1/Python-Selenium---Eduserver-Attendance-keeper/raw/main/requiredChanges.PNG)

- Change path to path where you pasted web driver and add "\chromedriver.exe" at the end if required.
- Fill your username in place of username as shown in the photo below.
- Do it same for your password too.

### **Now your code is ready to run, add an action of running it in the windows task scheduler [Keeper.py](https://github.com/ShyamKumar1/Python-Selenium---Eduserver-Attendance-keeper/blob/main/Keeper.py) file.**

To know how to add a task to the task scheduler in windows follows this [link.](https://youtu.be/n2Cr_YRQk7o)

This helps you at least relax in between classes without hurriedly marking attendance😎😎😎

### **How does it work?**

- It opens up the chrome browser and gets you to eduserver login page.
- Then fill the form and log in to it.
- Now it checks for the first attendance link and opens it.
- If we have to Submit attendance option then opens it and mark attendance and closes itself, else it refreshes the page every 5 seconds and checks for the Submit attendance option.
