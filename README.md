# Robot-Framework
This repository contains my Robot Framework-projects. Some are demos based on courses and some are my own
projects for example VR. Both are great and fun ways to learn about automating with Robot!

## Installations for running robot-files: ##
- Python. 2.7.15 is a good version if Python is not already in computer. Run python --version on command line to check installation.
- Robot Framework. Easiest installation is to use PIP-packet manager. Depending on version this can be included on Python installation but can be installed separately. Installation command for Robot Framework is pip install robotframework.
- seleniumlibrary and selenium2library for automating browser. Commands: pip install robotframework-seleniumlibrary and pip install robotframework2-seleniumlibrary.
- Geckodriver for Firefox or Chromedriver for Chrome. Changing browser can be done by modifying a keyword in test case-file which contains opening browser. Just simply replace Firefox with Chrome or other way.

## Instructions for running Robot-files ##
- Navigate to folder containing Robot-files
- Syntax for running is robot -t testcasename testsuitename.
For example robot -t Search Friday VR.robot
