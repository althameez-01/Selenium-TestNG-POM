# E-Commerce Web Automation Testing

A web automation testing project developed using **Selenium WebDriver, Java, and TestNG** to automate and validate key functionalities of an e-commerce web application.
The project follows the **Page Object Model (POM)** design pattern to create a structured, reusable, and maintainable automation framework.


## Project Overview

This project focuses on automating functional test scenarios for an e-commerce website. Selenium WebDriver is used to interact with web elements, while TestNG is used for test execution, assertions, and test organization.
The automation suite validates important user workflows such as login, product search, product selection, cart operations, and checkout.

### Key Objectives

- Automate repetitive manual test cases
- Validate important e-commerce workflows
- Identify functional issues through automated testing
- Improve test execution efficiency
- Create reusable and maintainable automation scripts
- Generate test execution reports



## Technologies & Tools

 **Java** - Programming Language 
 **Selenium WebDriver** - Web Automation 
 **TestNG** - Testing Framework 
 **Gradle** - Build & Dependency Management 
 **Page Object Model (POM)** - Framework Design Pattern 
 **IntelliJ IDEA** - Development Environment 
 **Allure Report** - Test Reporting 
 **Git & GitHub** - Version Control 

## Application Under Test

The automation tests are executed against:

**Envo E-Commerce Demo Website**

[Envo E-Commerce](https://envothemes.com/envo-ecommerce/)

> This is a third-party/demo website used for automation testing practice.



##  Test Scenarios

The automation suite covers the following scenarios:

###  Login

- Verify login with valid credentials
- Verify login with invalid credentials
- Validate login error messages
- Verify required field validations

###  Product Search

- Search for a product
- Verify search results
- Select a product from search results

###  Shopping Cart

- Add product to cart
- Verify product details in cart
- Update product quantity
- Remove product from cart
- Verify cart total

###  Checkout

- Verify checkout workflow
- Validate required checkout fields
- Verify order details

###  Logout

- Verify successful logout
- Verify user session behavior



##  Testing Types

The project includes:

- **Functional Testing**
- **Regression Testing**
- **Smoke Testing**
- **Positive Testing**
- **Negative Testing**
- **UI Testing**
- **End-to-End Testing**



##  Framework Architecture

The project follows the **Page Object Model (POM)** design pattern.

```text
E-Commerce-Automation
│
├── src
│   ├── main
│   │   └── java
│   │       └── pages
│   │           ├── LoginPage.java
│   │           ├── HomePage.java
│   │           ├── ProductPage.java
│   │           ├── CartPage.java
│   │           └── CheckoutPage.java
│   │
│   └── test
│       └── java
│           └── tests
│               ├── LoginTest.java
│               ├── ProductTest.java
│               ├── CartTest.java
│               └── CheckoutTest.java
│
├── testng.xml
├── build.gradle
└── README.md
