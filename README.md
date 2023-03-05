# DemoShopTestSite

This is the tests for the "https://shop.demoqa.com/" site
The tests preformed were on my personal computer running
OS: Microsoft Windows 10 Education Version: 10.0.19044 Build 19044
Browser: Google Chrome Version 110.0.5481.178

This repository has:
1. An excel file with the smoke tests alongside positive and negative tests testing the basic functionalities of a website
2. An excel file with the bugs I've found while testing
3. A DemoShopSite.side file that contains the automation testing for the smoke testing

Steps to run the automation test : 


1.Having the latest version of node.js installed.
  If you don't have it installed you can get the latest version from https://nodejs.org/en/
  
2. After making sure you have node installed you need to have the selenium side runner installed which can be installed with a simple command of "npm install selenium-     side-runner"

3. After selenium side runner you need to install the chrome drive which you can do with the command "npm install chromedriver"

4. Once all the steps above are followed you can run the tests by running the command "selenium-side-runner /path/to/filename.side"



There is a SmokeTest.java file with the code for the automation test in case anyone needs to look in to that.

All the tests are ranked on severity too, P0 being the most critical severity and going up to signify less severity on the site tested.
