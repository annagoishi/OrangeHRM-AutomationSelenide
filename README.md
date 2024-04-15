### OrangeHRM Test Automation

#### Overview
This project aims to automate testing scenarios for the OrangeHRM application using Selenium WebDriver and Selenide. OrangeHRM is a HR management system, and this test suite covers various functionalities including login, dashboard, and side panel navigation.

#### Prerequisites
- Java Development Kit (JDK)
- Selenium WebDriver
- Selenide
- ChromeDriver (for Chrome browser)

#### Setup
1. Ensure you have JDK installed on your system.
2. Download ChromeDriver and specify its path in the project configuration.
3. Import the necessary libraries.
4. Clone this repository to your local machine.

#### Test Cases
1. **Login Test**
    - Test successful login with valid credentials.
    - Test login with an invalid password.
    - Test login with a non-existing user.

2. **Dashboard Test**
    - Test if the dashboard header is displayed after successful login.

3. **Side Panel Test**
    - Test if all links in the side panel are displayed.
    - Test searching for a specific link in the side panel.
    - Test expand and collapse functionality of the side panel.

