#  This is quick demo of how to generate test report with Allure Report

## Create a node project

Delete node_modules folder

## Install Protractor:

  npm install --save -dev protractor
  
## Install Jasmine Allure reporter

  npm install --save -dev jasmine-allure-reporter

## Install Allure commandline

  npm install --save -dev allure-commandline
  
## Run test

protractor ./conf/conf.js

## Generate report

allure server allure-results

the report will be open in your default browser.

## Happy Testing!!!
