## Setup of Webdriverio Test automation framework

**Install npm dependencies**

```
Navigate to the project folder and execute;
$ npm install
```

## Starting the server for fancycars.ca

```
$ npm start
```


## Setup of Test automation fraemwork

**Install npm dependencies**

```
Navigate to the project folder and execute;
$ npm install
```


## Execute Tests:
1) Execute wdio config.js using below command;
npx wdio .\test\config\wdio.local.conf.js


## Allure Reports:
1) Install command line Allure report
https://repo.maven.apache.org/maven2/io/qameta/allure/allure-commandline/

2) To generate and open the results in browser, exceute below commands from commandline;

$ allure generate <directory-with-results>
$ allure open <directory-with-report>

## Page Object Model:

1) test / config -> includes webdriverio configurations required for browsers and mobile devices
2) test / pages -> page object definitions and page actions
3) test / specs -> test cases
4) test / reports -> Allure reporter
5) utilities -> common utilities required for the automation framework

## Miscellaneous

1) babel config -> used for backward compatibility for old browsers / environment
2) grunt file
