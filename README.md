# DEMOQA Automation
[DEMOQA](https://demoqa.com/) is a basic demo site, provided by [toolsqa.com](https://www.toolsqa.com/) to learn and practice Selenium.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Illustrations](#illustrations)
* [Setup](#setup)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
- The main task of this project is to automate the [demoqa.com](https://demoqa.com/) site, which contains different kinds of training modules like contact forms, menus to select, buttons to click, etc.
- Project intended to test the quality of the site.
- The purpose of this project is to improve automation and manual testing skills.
- It is the final project of the [IT Bootcamp](https://itbootcamp.rs/) course, to test our acquired knowledge.


## Technologies Used
- Java (JDK) - version 18.0.1
- Selenium - version 4.2.1
- TestNG - version 7.5
- Project Lombok - version 1.18.24


## Illustrations
Below are video recordings of test executions:

1. Elements Section tests

![ElementsTests](https://user-images.githubusercontent.com/105938336/174457890-bddfbe42-7073-4a8f-9740-112c873723ab.gif)

2. Alerts And Windows tests

![AlertsAndWindowsTests](https://user-images.githubusercontent.com/105938336/174458071-54638ba9-656b-4553-916b-073dbd6c4c8f.gif)


## Setup
- Install JDK
- Install and use IntelliJ (Community Edition)
- ChromeDriver is located in ./FinalProject/driver-lib/chromedriver.exe

- Dependencies that are used in the project are listed in ./FinalProject/pom.xml file:
```java
<dependency>
    <groupId>org.seleniumhq.selenium</groupId>
    <artifactId>selenium-java</artifactId>
    <version>4.2.1</version>
</dependency>
<dependency>
    <groupId>org.testng</groupId>
    <artifactId>testng</artifactId>
    <version>7.5</version>
</dependency>
<dependency>
    <groupId>org.projectlombok</groupId>
    <artifactId>lombok</artifactId>
    <version>1.18.24</version>
    <scope>provided</scope>
</dependency>
```


## Acknowledgements
- This project is based on knowledge that I gained throughout [IT Bootcamp](https://itbootcamp.rs/) course.
- Many thanks to the [IT Bootcamp](https://itbootcamp.rs/) team and my colleagues, for the incredible experience. 


## Contact
Created by [Milan Corluka](https://www.linkedin.com/in/milan-%C4%87orluka-95633323a/) - feel free to contact me!
