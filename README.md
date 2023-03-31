# EMI-Calculator-AppAutomation-with-Selenium-Appium

## Project scenerio:
If an user take loan (?) tk from a bank with interest of (?)% and
want to give (?) tk per month as EMI (installment) and processing fee (?)%,
how many time period it will take to complete the loan? Take the values from dataset and assert the monthly EMI,
total interest, processing fee amount and total payment from the result view.

For solve this question, create a dataset using following values:

Amount | Interest | EMI | Processing Fee | Monthly EMI | Total Interest | Processing Fee | Total Payment | Period (Year) | Period (Month)

100000 | 6 | 2000 | 2% | 2000 | 15361.08 | 2000 | 115361.08 | 4 | 10

200000 | 8 | 5000 | 2% | 5000 | 33391.61 | 4000 | 233391.61 | 3 | 11

250000 | 7 | 8000 | 1.5% | 8000 | 26804.51 | 3750 | 276804.51 | 2 | 11

50000 | 10 | 1000 | 5% | 1000 | 14949.12 | 2500 | 64949.12 | 5 | 5

## Technology and Tool Used:
- Selenium Webdriver
- Intellij idea
- Android Studio
- Appium Inspector
- Java
- Gradle
- TestNG
- Allure

## How to run this project:
- Clone this project
- Open Android Studio and Open the APK file:
- Set required configuration
- Hit this command in cmd for checking the connectivity with emulator : ```adb devices```
- Open Appium Server with following command: ```appium -p 4723```
- Open Appium Inspector
- Open Intellij Idea
- Hit the following command into the terminal: ```gradle clean test```
- For generating Allure Report use these commands: ```allure generate allure-results --clean -o allure-report``` and ```allure serve allure-results```

## Prerequisites:
- Install Android Studio latest version
- Install Appium Inspector
- JDK 8 or higher
- Configure GRADLE_HOME and set allure path
- Start Appium server

## Allure Report Screenshots:
![emi1](https://user-images.githubusercontent.com/96409251/229148959-98ae368a-2fe2-4605-9b56-61efc326bd91.png)
![emi2](https://user-images.githubusercontent.com/96409251/229149053-9dde8492-e167-45a9-93a0-bf45576ec8af.png)
![emi3](https://user-images.githubusercontent.com/96409251/229149119-73dba2f2-8ebb-4de5-b354-ea595fc69e6a.png)

## Gradle report Screenshots:
![emi4](https://user-images.githubusercontent.com/96409251/229149876-f8ebb635-43ff-4d31-9952-49e38e074e79.png)

## Video Output:
https://drive.google.com/drive/my-drive





