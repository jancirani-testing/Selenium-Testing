Overview
This is a Selenium WebDriver + TestNG automation framework built to validate the complete shopping journey of an e-commerce web application — from browsing and product search through to cart management, checkout, registration, and subscriptions. The framework follows the Page Object Model (POM) and uses custom TestNG listeners for enhanced test execution reporting.

✨ Key Features
🧩 Page Object Model architecture for clean, maintainable test code
🎧 Custom TestNG Listener (TestListener.java) for lifecycle hooks, logging, and reporting
🛒 Full shopping-flow coverage — search, cart, checkout, and order placement
👤 Account management tests — registration, login, logout, subscriptions
⭐ Product interaction tests — reviews, recommendations, quantity updates, categories
📝 Auto-generated TestNG HTML/XML reports after every run
🔧 Maven-managed dependencies and build lifecycle

🛠 Tech Stack
Category	Technology
Language	Java 8+
Test Framework	TestNG
Build Tool	Maven
Browser Automation	Selenium WebDriver
Execution Hooks	Custom TestNG Listeners
IDE	Eclipse
🧪 Test Coverage
Module	Covers
🔐 Auth & Account	Login, LogOut, Register, Verify_Subscription, verify_subscription_cartPage
🛍️ Product Discovery	Search_product, View_category, Verify_all_product_page, Recommended_items
🛒 Cart & Checkout	Add_toCart, Remove_cart, ViewCartProduct, Product_quantity, Place_order_Resister_checkout
⭐ Engagement	Review_on_product, Contact_us
⚙️ Core Utilities	Functionality, TestListener (ITlisteners)
📂 Project Structure
ecommerce-test-automation/
├── src/
│   ├── main/java/
│   │   └── ITlisteners/
│   │       ├── TestListener.java        # Custom TestNG execution listener
│   │       └── package-info.java
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
│       └── resources/                   # Test data / config files
├── test-output/                         # TestNG execution reports (generated)
├── target/                              # Compiled build output (git-ignored)
├── pom.xml                              # Maven dependencies & build config
└── testng.xml                           # TestNG suite configuration
✅ Prerequisites
Java JDK 8+
Maven
Eclipse IDE with TestNG and EGit plugins
Chrome/Firefox browser with a matching WebDriver version
🚀 Getting Started
Clone the repository

git clone https://github.com/<your-username>/ecommerce-test-automation.git
cd ecommerce-test-automation
Import into Eclipse File > Import > Existing Maven Projects → select the cloned folder

Resolve dependencies Right-click the project → Maven > Update Project

Configure environment Update base URL, credentials, and browser settings in the relevant config file as needed

▶️ Running Tests
Option 1 — Via Eclipse Right-click testng.xml → Run As → TestNG Suite

Option 2 — Via Maven CLI

mvn test
💡 TestListener.java hooks into test execution to provide enhanced logging and reporting throughout the run.

📊 Test Reports
After execution, TestNG automatically generates reports in the test-output/ directory:

test-output/index.html — interactive summary report
test-output/emailable-report.html — shareable summary report
🗺 Roadmap
 Integrate CI/CD pipeline (GitHub Actions / Jenkins)
 Add cross-browser parallel execution
 Extend reporting with Extent/Allure reports
 Add Dockerized execution environment
🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository
Create a feature branch (git checkout -b feature/your-feature)
Commit your changes (git commit -m 'Add some feature')
Push to the branch (git push origin feature/your-feature)
Open a Pull Request
📄 License
This project is licensed under the MIT License.
