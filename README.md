<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0f2027,45:203a43,100:00b09b&text=E-Commerce%20Test%20Automation&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Quality%20is%20not%20an%20accident.%20It%20is%20engineered.&descAlignY=58&descSize=16&animation=fadeIn" width="100%" />

<br/>

E-Commerce Test Automation Framework
Automated testing. Reliable shopping journeys. Better software quality.

A Java-based UI automation framework built with Selenium WebDriver, TestNG, and Maven, designed to validate essential e-commerce workflows through automated end-to-end testing.

<br/>

![Java](https://img.shields.io/badge/Java-8%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-WebDriver-43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![TestNG](https://img.shields.io/badge/TestNG-Testing_Framework-FF7043?style=for-the-badge) ![Maven](https://img.shields.io/badge/Maven-Build_Tool-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white) ![IDE](https://img.shields.io/badge/IDE-Eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white)

<br/>

![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/ecommerce-test-automation?style=social) ![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/ecommerce-test-automation?style=social) ![GitHub issues](https://img.shields.io/github/issues/YOUR_USERNAME/ecommerce-test-automation)

<br/>

Overview • Features • Tech Stack • Test Coverage • Architecture • Installation • Execution • Reports

</div>

📌 Project Overview

E-Commerce Test Automation Framework is a web UI automation project developed to verify the functionality, reliability, and usability of an e-commerce application.

The framework automates real-world shopping scenarios, covering the complete customer journey — from creating an account and discovering products to managing the shopping cart and completing checkout.

Built using Selenium WebDriver and TestNG, the project demonstrates practical automation testing concepts, structured test organization, execution management, and reporting through custom TestNG listeners.

The primary objective is simple:

Catch defects early, validate critical user journeys, and build confidence in application quality through automation.
🎯 Project Goals
Automate repetitive manual testing activities.
Validate critical e-commerce business workflows.
Improve test execution consistency and reliability.
Organize test scripts for better readability and maintenance.
Generate execution reports for test result analysis.
Demonstrate practical Selenium and TestNG automation skills.
✨ Key Features

<table>
<tr>
<td width="50%">

🛒 End-to-End Shopping Tests
Product discovery and search
Add and remove cart items
Product quantity validation
Checkout and order placement
Recommended product verification

</td>
<td width="50%">

🔐 Account & Authentication
User registration
Login functionality
Logout functionality
Subscription verification
Account-related workflows

</td>
</tr>
<tr>
<td width="50%">

⚙️ Automation Architecture
Selenium WebDriver integration
TestNG test execution
Maven dependency management
Organized Java test packages
Custom TestNG listener

</td>
<td width="50%">

📊 Execution & Reporting
Automated test execution
TestNG HTML reports
XML execution reports
Test lifecycle monitoring
Execution result tracking

</td>
</tr>
</table>

🧰 Technology Stack

The framework combines industry-standard automation technologies to create a structured and maintainable testing environment.

Technology	Purpose
☕ Java 8+	Programming language
🌐 Selenium WebDriver	Browser automation
🧪 TestNG	Test execution and management
📦 Apache Maven	Build and dependency management
🎧 TestNG Listeners	Test lifecycle monitoring
💻 Eclipse IDE	Development environment
🌍 Chrome / Firefox	Browser execution
Technology Resources
Java Documentation
Selenium Documentation
TestNG Documentation
Apache Maven Guide
🧪 Test Coverage

The project covers multiple functional areas of an e-commerce application.

1. 🔐 Authentication & Account Management
Test Class	Testing Scenario
Register.java	Verify user registration
Login.java	Validate login functionality
LogOut.java	Verify logout functionality
2. 🛍️ Product Discovery & Navigation
Test Class	Testing Scenario
Search_product.java	Search for products
View_category.java	Verify product categories
Verify_all_product_page.java	Validate product listing page
Recommended_items.java	Verify recommended products
3. 🛒 Shopping Cart & Checkout
Test Class	Testing Scenario
Add_toCart.java	Add products to shopping cart
Remove_cart.java	Remove products from cart
ViewCartProduct.java	Verify cart product details
Product_quantity.java	Validate product quantity
Place_order_Resister_checkout.java	Verify order placement and checkout
4. ⭐ User Engagement & Subscription
Test Class	Testing Scenario
Review_on_product.java	Submit product reviews
Contact_us.java	Verify contact functionality
Verify_Subscription.java	Validate subscription functionality
verify_subscription_cartPage.java	Verify subscription on cart page
5. ⚙️ Framework Components
Component	Responsibility
TestListener.java	Monitor TestNG test lifecycle
Functionality.java	Shared test functionality

Note: Test coverage is based on the test classes currently included in the project.

🏗️ Project Architecture

The project follows a structured Maven directory layout to separate application code, test scripts, resources, and execution reports.

text
ecommerce-test-automation/
│
├── src/
│   │
│   ├── main/
│   │   └── java/
│   │       └── ITlisteners/
│   │           ├── TestListener.java
│   │           └── package-info.java
│   │
│   └── test/
│       ├── java/
│       │   └── package_pro/
│       │       ├── Add_toCart.java
│       │       ├── Contact_us.java
│       │       ├── Functionality.java
│       │       ├── LogOut.java
│       │       ├── Login.java
│       │       ├── Place_order_Resister_checkout.java
│       │       ├── Product_quantity.java
│       │       ├── Recommended_items.java
│       │       ├── Register.java
│       │       ├── Remove_cart.java
│       │       ├── Review_on_product.java
│       │       ├── Search_product.java
│       │       ├── Verify_Subscription.java
│       │       ├── Verify_all_product_page.java
│       │       ├── ViewCartProduct.java
│       │       ├── View_category.java
│       │       ├── verify_subscription_cartPage.java
│       │       └── package-info.java
│       │
│       └── resources/
│
├── test-output/              # Generated TestNG reports
│
├── target/                   # Maven build output
│
├── pom.xml                   # Maven configuration
│
├── testng.xml                # TestNG suite configuration
│
└── README.md                 # Project documentation

🔍 Architecture Highlights
Test Layer: Contains individual Java test classes responsible for validating application features.
Listener Layer: Handles TestNG execution lifecycle events through a custom listener.
Resource Layer: Provides a location for test data and configuration resources.
Build Layer: Maven manages project dependencies and build execution.
Reporting Layer: TestNG generates execution reports after test runs.
🚀 Getting Started

Follow these instructions to set up and execute the automation framework locally.

📋 Prerequisites

Make sure the following tools are installed:

Requirement	Version
Java JDK	8 or above
Apache Maven	Compatible installed version
Eclipse IDE	Latest recommended
Browser	Chrome / Firefox
TestNG Plugin	For Eclipse execution
1. Clone the Repository
bash
git clone https://github.com/YOUR_USERNAME/ecommerce-test-automation.git

2. Navigate to the Project
bash
cd ecommerce-test-automation

3. Verify Java Installation
bash
java -version

4. Verify Maven Installation
bash
mvn -version

5. Install Project Dependencies
bash
mvn clean install

6. Import into Eclipse
Open Eclipse IDE.
Select File → Import.
Choose Existing Maven Projects.
Browse to the cloned repository.
Select the project and click Finish.
Right-click the project and select Maven → Update Project.
▶️ Test Execution

You can execute the automation scripts using either Eclipse IDE or the Maven command line.

Option 1: Execute Through Eclipse
Open the project in Eclipse.
Locate testng.xml.
Right-click the file.
Select Run As → TestNG Suite.
Monitor the execution results in the TestNG console.
Option 2: Execute Through Maven

Run the complete configured test suite:

bash
mvn test


Perform a clean build and execute tests:

bash
mvn clean test


Build and package the project:

bash
mvn clean package


Execution Note: Test execution depends on the browser, application availability, and configuration used by the test scripts. Update the required application URL, credentials, and browser settings before execution where applicable.

📊 Test Reports & Results

After execution, TestNG generates reports that help analyze the outcome of automated test cases.

📁 Report Location
text
test-output/
│
├── index.html
├── emailable-report.html
├── testng-results.xml
└── other generated report files

📈 Available Reports
Report	Description
index.html	TestNG execution summary
emailable-report.html	Email-friendly test execution report
testng-results.xml	Structured XML test results
View Your Test Results
Execute the test suite.
Navigate to the test-output/ directory.
Open index.html in your browser.
Review passed, failed, and skipped test cases.
🔮 Future Enhancements

The framework provides a foundation for further improvements in automation architecture, execution efficiency, and reporting.

Enhancement	Description	Status
Page Object Model	Improve separation of test logic and page interactions	Planned
Extent Reports / Allure	Add advanced execution reporting	Planned
GitHub Actions	Automate test execution through CI/CD	Planned
Cross-Browser Testing	Expand browser compatibility coverage	Planned
Parallel Execution	Reduce execution time	Planned
Data-Driven Testing	Support multiple test data combinations	Planned
Screenshot Capture	Capture screenshots for failed tests	Planned
Logging Framework	Improve debugging and execution traceability	Planned
🤝 Contributing

Contributions, suggestions, and improvements are always welcome!

If you would like to improve this project:

1. Fork the repository

2. Create a new branch

bash
git checkout -b feature/your-feature-name


3. Commit your changes

bash
git commit -m "Add: your feature description"


4. Push your branch

bash
git push origin feature/your-feature-name


5. Open a Pull Request

Describe your changes and submit them for review.

🐛 Issues & Feedback

Found a bug or have an idea to improve the framework?

Open an issue in the GitHub repository.
Describe the problem clearly.
Include relevant execution details or screenshots.
Suggest improvements whenever possible.

Your feedback helps make the framework better!

👨‍💻 Author

<div align="center">

Jancirani

QA Automation Tester | Java | Selenium WebDriver | TestNG

Passionate about software quality, test automation, and building reliable testing solutions.

<br/>

<a href="https://github.com/jancirani-testing">
<img src="https://img.shields.io/badge/GitHub-jancirani--testing-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

Building better software, one automated test at a time.

</div>

📄 License

This project is distributed under the MIT License.

See the LICENSE file for more information.

<div align="center">

⭐ Like This Project?

If you find this automation framework useful, consider giving it a Star ⭐ on GitHub.

Your support and feedback are appreciated!

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:00b09b,50:203a43,100:0f2027" width="100%" />

Made with ☕ Java, 🧪 Selenium & ❤️ for Quality Assurance

</div>
