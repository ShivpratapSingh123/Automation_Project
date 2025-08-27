# E-commerce Automation TestNG

This project automates an e-commerce website by creating test suites using **Selenium WebDriver** and the **TestNG** testing framework.

## Key Automated Modules

The following core modules have been automated:
* **SignUp**
* **Login**
* **Search**
* **Cart**
* **Checkout**

A total of **51 key test cases** have been written, covering both positive and negative scenarios for each module. A state-transition flow of test cases is designed to simulate a user's journey of buying a product from the site.

The automation script is configured to take a screenshot at the point of failure for any failed test cases.

You can view the detailed test cases in the [Excel file](https://docs.google.com/spreadsheets/d/1Bf8-4S0s5-1u2K2C2b2n5F2z1_q_h-4Q/edit?usp=sharing).

## Technology Stack

* **Tool:** Selenium WebDriver
* **IDE:** IntelliJ IDEA
* **Build Tool:** Gradle
* **Language:** Java
* **Testing Framework:** TestNG
* **Reporting:** Allure

## Prerequisites

1.  Install **JDK 11**, **Gradle**, and **Allure**.
2.  Configure environment variables for JDK 11, Gradle, and Allure.
3.  Clone or unzip this project to your local machine.
4.  Open the project folder in IntelliJ IDEA.
5.  Double-click on `build.gradle` and open the project.
6.  Wait for the project to build successfully.

## How to Run the Automation Script

1.  Open the **Terminal** within your IDE.
2.  Run the following command to execute the test suite:
    ```
    gradle clean test
    ```
3.  Selenium will open the browser and begin the automation process.
