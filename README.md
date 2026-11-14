<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=300&color=0:0f2027,35:203a43,70:2c5364,100:00b09b&text=E-Commerce%20Test%20Automation&fontSize=48&fontColor=ffffff&fontAlignY=40&desc=Quality%20is%20not%20an%20accident.%20It%20is%20engineered.&descAlignY=62&descSize=18&animation=twinkling" width="100%" alt="E-Commerce Test Automation banner" />

<a href="https://github.com/jancirani-testing">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=3000&pause=900&color=00B09B&center=true&vCenter=true&width=760&height=60&lines=%F0%9F%9B%92+Automating+real+shopping+journeys;%F0%9F%A7%AA+Selenium+WebDriver+%2B+TestNG+%2B+Maven;%F0%9F%90%9B+Catch+defects+early%2C+ship+with+confidence;%F0%9F%93%8A+Clear+reports+%7C+Custom+listeners+%7C+Clean+structure" alt="Typing animation" />
</a>

<br/>

![Java](https://img.shields.io/badge/Java-8%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-WebDriver-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-Framework-FF7043?style=for-the-badge&logo=testng&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-Build_Tool-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-IDE-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white)

![Chrome](https://img.shields.io/badge/Chrome-Supported-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Firefox](https://img.shields.io/badge/Firefox-Supported-FF7139?style=flat-square&logo=firefoxbrowser&logoColor=white)
![Test Classes](https://img.shields.io/badge/Test_Classes-16-00b09b?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

![GitHub stars](https://img.shields.io/github/stars/jancirani-testing/ecommerce-test-automation?style=social)
![GitHub forks](https://img.shields.io/github/forks/jancirani-testing/ecommerce-test-automation?style=social)
![GitHub issues](https://img.shields.io/github/issues/jancirani-testing/ecommerce-test-automation?style=flat-square&color=ff7043)

<br/>

**[📌 Overview](#-project-overview)** •
**[✨ Features](#-key-features)** •
**[🧰 Tech Stack](#-technology-stack)** •
**[🧪 Coverage](#-test-coverage)** •
**[🏗️ Architecture](#%EF%B8%8F-project-architecture)** •
**[🚀 Installation](#-getting-started)** •
**[▶️ Execution](#%EF%B8%8F-test-execution)** •
**[📊 Reports](#-test-reports--results)**

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=gradient&customColorList=12,20,6" width="100%" alt="divider" />

## 📌 Project Overview

**E-Commerce Test Automation Framework** is a web UI automation project that verifies the **functionality, reliability, and usability** of an e-commerce application.

It automates real-world shopping scenarios and walks through the **complete customer journey**, from creating an account and discovering products to managing the cart and completing checkout.

Built with **Selenium WebDriver** and **TestNG**, the project demonstrates structured test organization, execution management, and reporting through a **custom TestNG listener**.

> 🎯 **Mission:** Catch defects early, validate critical user journeys, and build confidence in application quality through automation.

### 🗺️ The Customer Journey We Automate

```mermaid
flowchart LR
    A([🆕 Register]) --> B([🔐 Login])
    B --> C([🔎 Search & Browse])
    C --> D([🛒 Add to Cart])
    D --> E([🧾 View Cart])
    E --> F([💳 Checkout])
    F --> G([⭐ Review])
    G --> H([🚪 Logout])

    style A fill:#00b09b,stroke:#007f6e,color:#fff
    style B fill:#2c5364,stroke:#203a43,color:#fff
    style C fill:#43B02A,stroke:#2f7d1e,color:#fff
    style D fill:#FF7043,stroke:#c4491f,color:#fff
    style E fill:#ED8B00,stroke:#a86000,color:#fff
    style F fill:#C71A36,stroke:#8d1226,color:#fff
    style G fill:#7c4dff,stroke:#5530c9,color:#fff
    style H fill:#455a64,stroke:#263238,color:#fff
```

---

## 🎯 Project Goals

| | Goal |
|:-:|:--|
| 🤖 | Automate repetitive manual testing activities |
| 🧭 | Validate critical e-commerce business workflows |
| 🎯 | Improve test execution consistency and reliability |
| 🧹 | Organize test scripts for readability and maintenance |
| 📈 | Generate execution reports for result analysis |
| 💡 | Demonstrate practical Selenium and TestNG skills |

---

## ✨ Key Features

<table>
<tr>
<td width="50%" valign="top">

### 🛒 End-to-End Shopping Tests
- 🔎 Product discovery and search
- ➕ Add and remove cart items
- 🔢 Product quantity validation
- 💳 Checkout and order placement
- 🌟 Recommended product verification

</td>
<td width="50%" valign="top">

### 🔐 Account & Authentication
- 📝 User registration
- 🔑 Login functionality
- 🚪 Logout functionality
- 📬 Subscription verification
- 👤 Account-related workflows

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Automation Architecture
- 🌐 Selenium WebDriver integration
- 🧪 TestNG test execution
- 📦 Maven dependency management
- 🗂️ Organized Java test packages
- 🎧 Custom TestNG listener

</td>
<td width="50%" valign="top">

### 📊 Execution & Reporting
- ⚡ Automated test execution
- 🌐 TestNG HTML reports
- 📄 XML execution reports
- 🔄 Test lifecycle monitoring
- ✅ Execution result tracking

</td>
</tr>
</table>

---

## 🧰 Technology Stack

| Technology | Purpose |
|:--|:--|
| ☕ **Java 8+** | Programming language |
| 🌐 **Selenium WebDriver** | Browser automation |
| 🧪 **TestNG** | Test execution and management |
| 📦 **Apache Maven** | Build and dependency management |
| 🎧 **TestNG Listeners** | Test lifecycle monitoring |
| 💻 **Eclipse IDE** | Development environment |
| 🌍 **Chrome / Firefox** | Browser execution |

<details>
<summary><b>📚 Technology Resources (click to expand)</b></summary>
<br/>

- ☕ [Java Documentation](https://docs.oracle.com/en/java/)
- 🌐 [Selenium Documentation](https://www.selenium.dev/documentation/)
- 🧪 [TestNG Documentation](https://testng.org/doc/)
- 📦 [Apache Maven Guide](https://maven.apache.org/guides/)

</details>

---

## 🧪 Test Coverage

The suite spans **4 functional areas** with **16 test classes** plus shared framework components.

```mermaid
pie showData title Test Classes by Functional Area
    "🔐 Authentication (3)" : 3
    "🛍️ Product Discovery (4)" : 4
    "🛒 Cart & Checkout (5)" : 5
    "⭐ Engagement & Subscription (4)" : 4
```

<details open>
<summary><b>🔐 1. Authentication & Account Management</b></summary>
<br/>

| Test Class | Testing Scenario |
|:--|:--|
| `Register.java` | ✅ Verify user registration |
| `Login.java` | ✅ Validate login functionality |
| `LogOut.java` | ✅ Verify logout functionality |

</details>

<details open>
<summary><b>🛍️ 2. Product Discovery & Navigation</b></summary>
<br/>

| Test Class | Testing Scenario |
|:--|:--|
| `Search_product.java` | 🔎 Search for products |
| `View_category.java` | 🗂️ Verify product categories |
| `Verify_all_product_page.java` | 📃 Validate product listing page |
| `Recommended_items.java` | 🌟 Verify recommended products |

</details>

<details open>
<summary><b>🛒 3. Shopping Cart & Checkout</b></summary>
<br/>

| Test Class | Testing Scenario |
|:--|:--|
| `Add_toCart.java` | ➕ Add products to shopping cart |
| `Remove_cart.java` | ➖ Remove products from cart |
| `ViewCartProduct.java` | 🧾 Verify cart product details |
| `Product_quantity.java` | 🔢 Validate product quantity |
| `Place_order_Resister_checkout.java` | 💳 Verify order placement and checkout |

</details>

<details open>
<summary><b>⭐ 4. User Engagement & Subscription</b></summary>
<br/>

| Test Class | Testing Scenario |
|:--|:--|
| `Review_on_product.java` | ✍️ Submit product reviews |
| `Contact_us.java` | 📞 Verify contact functionality |
| `Verify_Subscription.java` | 📬 Validate subscription functionality |
| `verify_subscription_cartPage.java` | 🛒 Verify subscription on cart page |

</details>

<details open>
<summary><b>⚙️ 5. Framework Components</b></summary>
<br/>

| Component | Responsibility |
|:--|:--|
| `TestListener.java` | 🎧 Monitor TestNG test lifecycle |
| `Functionality.java` | 🧰 Shared test functionality |

</details>

> 📝 **Note:** Test coverage is based on the test classes currently included in the project.

---

## 🏗️ Project Architecture

The project follows a structured **Maven directory layout** that separates application code, test scripts, resources, and execution reports.

```mermaid
flowchart TB
    subgraph BUILD["📦 Build Layer"]
        M[pom.xml<br/>Maven]
    end
    subgraph RUN["▶️ Execution Layer"]
        X[testng.xml<br/>Suite config]
    end
    subgraph TEST["🧪 Test Layer"]
        T[package_pro<br/>16 test classes]
        F[Functionality.java<br/>Shared logic]
    end
    subgraph LISTEN["🎧 Listener Layer"]
        L[ITlisteners<br/>TestListener.java]
    end
    subgraph BROWSER["🌐 Browser"]
        W[Selenium WebDriver<br/>Chrome / Firefox]
    end
    subgraph REPORT["📊 Reporting Layer"]
        R[test-output<br/>HTML + XML]
    end

    M --> X --> T
    T --> F
    T --> W
    T -. events .-> L
    L --> R
    T --> R

    style BUILD fill:#C71A36,stroke:#8d1226,color:#fff
    style RUN fill:#FF7043,stroke:#c4491f,color:#fff
    style TEST fill:#43B02A,stroke:#2f7d1e,color:#fff
    style LISTEN fill:#7c4dff,stroke:#5530c9,color:#fff
    style BROWSER fill:#2c5364,stroke:#203a43,color:#fff
    style REPORT fill:#00b09b,stroke:#007f6e,color:#fff
```

<details>
<summary><b>📁 Full directory structure (click to expand)</b></summary>

```text
ecommerce-test-automation/
│
├── 📂 src/
│   │
│   ├── 📂 main/
│   │   └── 📂 java/
│   │       └── 📂 ITlisteners/
│   │           ├── 🎧 TestListener.java
│   │           └── 📄 package-info.java
│   │
│   └── 📂 test/
│       ├── 📂 java/
│       │   └── 📂 package_pro/
│       │       ├── ➕ Add_toCart.java
│       │       ├── 📞 Contact_us.java
│       │       ├── 🧰 Functionality.java
│       │       ├── 🚪 LogOut.java
│       │       ├── 🔑 Login.java
│       │       ├── 💳 Place_order_Resister_checkout.java
│       │       ├── 🔢 Product_quantity.java
│       │       ├── 🌟 Recommended_items.java
│       │       ├── 📝 Register.java
│       │       ├── ➖ Remove_cart.java
│       │       ├── ✍️ Review_on_product.java
│       │       ├── 🔎 Search_product.java
│       │       ├── 📬 Verify_Subscription.java
│       │       ├── 📃 Verify_all_product_page.java
│       │       ├── 🧾 ViewCartProduct.java
│       │       ├── 🗂️ View_category.java
│       │       ├── 🛒 verify_subscription_cartPage.java
│       │       └── 📄 package-info.java
│       │
│       └── 📂 resources/
│
├── 📊 test-output/              # Generated TestNG reports
├── 🎯 target/                   # Maven build output
├── 📦 pom.xml                   # Maven configuration
├── 🧪 testng.xml                # TestNG suite configuration
└── 📘 README.md                 # Project documentation
```

</details>

### 🔍 Architecture Highlights

| Layer | Description |
|:--|:--|
| 🧪 **Test Layer** | Individual Java test classes that validate application features |
| 🎧 **Listener Layer** | Handles TestNG lifecycle events through a custom listener |
| 🗃️ **Resource Layer** | A home for test data and configuration resources |
| 📦 **Build Layer** | Maven manages dependencies and build execution |
| 📊 **Reporting Layer** | TestNG generates execution reports after each run |

---

## 🚀 Getting Started

Follow these steps to set up and run the framework locally.

### 📋 Prerequisites

| Requirement | Version |
|:--|:--|
| ☕ Java JDK | 8 or above |
| 📦 Apache Maven | Compatible installed version |
| 💻 Eclipse IDE | Latest recommended |
| 🌍 Browser | Chrome / Firefox |
| 🔌 TestNG Plugin | For Eclipse execution |

### ⚡ Quick Setup

**1️⃣ Clone the repository**
```bash
git clone https://github.com/jancirani-testing/ecommerce-test-automation.git
```

**2️⃣ Navigate to the project**
```bash
cd ecommerce-test-automation
```

**3️⃣ Verify Java and Maven**
```bash
java -version
mvn -version
```

**4️⃣ Install project dependencies**
```bash
mvn clean install
```

**5️⃣ Import into Eclipse**

1. Open **Eclipse IDE**
2. Select **File → Import**
3. Choose **Existing Maven Projects**
4. Browse to the cloned repository
5. Select the project and click **Finish**
6. Right-click the project and select **Maven → Update Project**

---

## ▶️ Test Execution

Run the scripts from **Eclipse** or from the **Maven command line**.

<table>
<tr>
<td width="50%" valign="top">

### 💻 Option 1: Eclipse

1. Open the project in Eclipse
2. Locate `testng.xml`
3. Right-click the file
4. Select **Run As → TestNG Suite**
5. Watch results in the TestNG console

</td>
<td width="50%" valign="top">

### ⌨️ Option 2: Maven

```bash
# Run the configured suite
mvn test

# Clean build, then test
mvn clean test

# Build and package
mvn clean package
```

</td>
</tr>
</table>

> ⚠️ **Execution Note:** Test execution depends on the browser, application availability, and configuration used by the test scripts. Update the application URL, credentials, and browser settings before running where applicable.

### 🔄 What Happens During a Run

```mermaid
sequenceDiagram
    autonumber
    actor QA as 👩‍💻 Tester
    participant MVN as 📦 Maven
    participant NG as 🧪 TestNG
    participant L as 🎧 TestListener
    participant WD as 🌐 WebDriver
    participant APP as 🛍️ E-Commerce App

    QA->>MVN: mvn clean test
    MVN->>NG: Load testng.xml
    loop Every test class
        NG->>L: Test started
        NG->>WD: Launch browser
        WD->>APP: Perform user actions
        APP-->>WD: Page response
        WD-->>NG: Assertions
        NG->>L: Test passed / failed / skipped
    end
    NG-->>QA: Reports in test-output/
```

---

## 📊 Test Reports & Results

After execution, TestNG generates reports to help you analyze the outcome of each test.

```text
📁 test-output/
│
├── 🌐 index.html
├── 📧 emailable-report.html
├── 📄 testng-results.xml
└── 🗂️ other generated report files
```

| Report | Description |
|:--|:--|
| 🌐 `index.html` | TestNG execution summary |
| 📧 `emailable-report.html` | Email-friendly test execution report |
| 📄 `testng-results.xml` | Structured XML test results |

### 👀 View Your Results

1. ▶️ Execute the test suite
2. 📂 Open the `test-output/` directory
3. 🌐 Open `index.html` in your browser
4. ✅ Review **passed**, ❌ **failed**, and ⏭️ **skipped** tests

---

## 🔮 Future Enhancements

```mermaid
timeline
    title 🗺️ Framework Roadmap
    section Structure
        Page Object Model : Separate test logic from page interactions
        Data-Driven Testing : Multiple test data combinations
    section Reporting
        Extent Reports / Allure : Advanced execution reports
        Screenshot Capture : Evidence for failed tests
        Logging Framework : Better debugging and traceability
    section Scale
        Cross-Browser Testing : Wider compatibility coverage
        Parallel Execution : Faster test runs
        GitHub Actions : CI/CD pipeline
```

| Enhancement | Description | Status |
|:--|:--|:-:|
| 🧱 Page Object Model | Improve separation of test logic and page interactions | ![Planned](https://img.shields.io/badge/-Planned-orange?style=flat-square) |
| 📈 Extent Reports / Allure | Add advanced execution reporting | ![Planned](https://img.shields.io/badge/-Planned-orange?style=flat-square) |
| 🤖 GitHub Actions | Automate test execution through CI/CD | ![Planned](https://img.shields.io/badge/-Planned-orange?style=flat-square) |
| 🌍 Cross-Browser Testing | Expand browser compatibility coverage | ![Planned](https://img.shields.io/badge/-Planned-orange?style=flat-square) |
| ⚡ Parallel Execution | Reduce execution time | ![Planned](https://img.shields.io/badge/-Planned-orange?style=flat-square) |
| 🗃️ Data-Driven Testing | Support multiple test data combinations | ![Planned](https://img.shields.io/badge/-Planned-orange?style=flat-square) |
| 📸 Screenshot Capture | Capture screenshots for failed tests | ![Planned](https://img.shields.io/badge/-Planned-orange?style=flat-square) |
| 📝 Logging Framework | Improve debugging and execution traceability | ![Planned](https://img.shields.io/badge/-Planned-orange?style=flat-square) |

---

## 🤝 Contributing

Contributions, suggestions, and improvements are always welcome! 💚

```bash
# 1. Fork the repository, then create a branch
git checkout -b feature/your-feature-name

# 2. Commit your changes
git commit -m "Add: your feature description"

# 3. Push your branch
git push origin feature/your-feature-name
```

**4.** Open a **Pull Request** and describe your changes for review.

---

## 🐛 Issues & Feedback

Found a bug or have an idea to improve the framework?

- 🐞 Open an issue in the GitHub repository
- 📝 Describe the problem clearly
- 📎 Include relevant execution details or screenshots
- 💡 Suggest improvements whenever possible

Your feedback helps make the framework better!

---

## 👨‍💻 Author

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1200&color=00B09B&center=true&vCenter=true&width=420&height=45&lines=Jancirani" alt="Jancirani" />

**QA Automation Tester** &nbsp;|&nbsp; ☕ Java &nbsp;|&nbsp; 🌐 Selenium WebDriver &nbsp;|&nbsp; 🧪 TestNG

*Passionate about software quality, test automation, and building reliable testing solutions.*

<a href="https://github.com/jancirani-testing">
  <img src="https://img.shields.io/badge/GitHub-jancirani--testing-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" />
</a>

<br/><br/>

**🧪 Building better software, one automated test at a time.**

</div>

---

## 📄 License

This project is distributed under the **MIT License**. See the [LICENSE](LICENSE) file for more information.

---

<div align="center">

## ⭐ Like This Project?

If you find this automation framework useful, consider giving it a **Star ⭐** on GitHub.
Your support and feedback are appreciated!

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=160&section=footer&color=0:00b09b,50:2c5364,100:0f2027&animation=fadeIn" width="100%" alt="footer" />

**Made with ☕ Java, 🧪 Selenium & ❤️ for Quality Assurance**

</div>
