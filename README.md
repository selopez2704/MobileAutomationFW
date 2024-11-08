# Mobile Automation

This project is a mobile automation framework developed in Java using Appium, Selenium, TestNG, Cucumber, Lombok, and Allure. It is designed to facilitate automated testing of mobile applications while following best development and design practices.

## Technologies Used

- **Java**: The primary programming language.
- **Appium**: Tool for automating mobile applications.
- **Selenium**: Framework for automation.
- **TestNG**: Testing framework for Java.
- **Cucumber**: Tool for behavior-driven development (BDD).
- **Lombok**: Library to reduce boilerplate code.
- **Allure**: Tool for generating test reports.


## Installation

### Prerequisites

1. **Java JDK**: Ensure you have Java JDK 17 or higher installed.
2. **Maven**: You need Maven to manage project dependencies.
3. **Node.js**: Install Node.js to run Appium.
4. **Appium**: Install Appium via NPM:
   ```bash
   npm install -g appium   
   ```

**Device Setup:** Ensure you have emulators or real devices configured and accessible.   



## Compile and Run Tests

**Install Dependencies:**
   ```bash
   mvn clean install 
   ```


**Run Tests:** To run tests with TestNG:
   ```bash
   TODO
   ```
**Generate Allure Reports:** To generate and open the Allure report:
   ```bash
   allure:serve
   ```


## Key Implementations

### Use of PageFactory
The Page Object Model pattern is used along with PageFactory to encapsulate the logic for interacting with the UI, improving maintainability and code readability.

### Element Management
Wait methods and screenshot capture are implemented to facilitate debugging and improve the stability of tests.

### Allure Annotations
Allure annotations are used to generate detailed reports that include information about test execution, steps taken, and screenshots in case of failures.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
