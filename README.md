# Imoh Effiong | Software Quality Assurance Portfolio

Welcome! This repository contains my hands-on Quality Assurance (QA) projects, featuring end-to-end testing methodologies across **Manual Testing**, **API Testing**, **UI Test Automation**, and **Performance & Load Testing**.

---

## 🛠 Tools & Technologies
- **Manual & Functional Testing:** Test Strategy, Test Case Design, Defect Tracking, Boundary Value Analysis, RTM
- **API Testing & Automation:** Postman, REST APIs, Newman CLI, JavaScript, JSON
- **UI Automation:** Playwright (TypeScript/JavaScript)
- **Performance & Load Testing:** Apache JMeter, Headless CLI Testing, APDEX Score Analysis, SLA Assertions, HTML Dashboard Reports
- **Defect Management & Tools:** Jira, GitHub Issues, Severity/Priority Categorization

---

## 📁 Repository Structure

- [📂 `Manual_testing/`](./Manual_testing/) - Test plans, test cases (`.csv`), defect logs, and execution summary reports
- [📂 `API_testing/`](./API_testing/) - Postman collections (`.json`), environment configurations, and Newman test execution reports
- [📂 `Automation-playwright/`](./Automation-playwright/) - Playwright end-to-end automated test scripts
- [📂 `Performance_testing_jmeter/`](./Performance_testing_jmeter/) - JMeter test plans (`.jmx`), visual aggregate/summary reports, execution logs (`.jtl`), and multi-tier interactive HTML performance dashboards

---

## 📌 Projects

### 1. 📋 [SauceDemo Manual Testing Project](./Manual_testing/)
End-to-end functional, boundary, negative testing, and bug tracking for an e-commerce web application.

* 📋 **[Test Case Suite](./Manual_testing/sausedemo_testcase.csv)**
* 📊 **[Test Execution Summary & Metrics](./Manual_testing/TEST_SUMMARY.md)**
* 🐛 **[GitHub Defect Tracker](https://github.com/fredo134/QA-Manual-Testing-Portfolio/issues)**

---

### 2. 🚀 [ReqRes REST API Testing Suite](./API_testing/)
Automated REST API test suite built for the **ReqRes API**, covering full CRUD operations (`GET`, `POST`, `PUT`, `DELETE`), custom status assertions, schema validations, dynamic variables, and execution reporting via Newman.

* 📄 **[Postman Collection](./API_testing/collections/ReqRes_API_Suite.postman_collection.json)**
* ⚙️ **[Environment File](./API_testing/environments/ReqRes_Environment.postman_environment.json)**
* 📊 **[Newman HTML Test Report](./API_testing/reports/index.html)**

---

### 3. ⚡ [Performance Testing with JMeter](./Performance_testing_jmeter/)
API baseline performance and endpoint latency load testing using Apache JMeter.

* 🖼️ **[Aggregate Report (`Aggregate_report.png`)](./Performance_testing_jmeter/Aggregate_report.png)**
* 🖼️ **[Summary Report (`Summary_report.png`)](./Performance_testing_jmeter/Summary_report.png)**
* 📄 **[Baseline Load Test Script (`performance_loadtest.jmx`)](./Performance_testing_jmeter/performance_loadtest.jmx)**

---

### 4. 📈 [Restful-Booker Multi-Tier Load & SLA Testing](./Performance_testing_jmeter/Restful-Booker%20API%20Performance%20/)
Multi-tier concurrent user scaling test targeting the **Restful-Booker Hotel Booking API** (`https://restful-booker.herokuapp.com/`). Validates authentication workflows, dynamic variable extraction, and transactional booking operations under 50, 100, and 250 concurrent virtual users in non-GUI CLI mode[cite: 1, 2].

* 📄 **[Restful-Booker Multi-Tier Plan (`testplan.jmx`)](./Performance_testing_jmeter/Restful-Booker%20API%20Performance%20/testplan.jmx)**
* 📊 **[50 VUs HTML Report Bundle (`html_report_50.zip`)](./Performance_testing_jmeter/Restful-Booker%20API%20Performance%20/html_report_50.zip)**
* 📊 **[100 VUs HTML Report Bundle (`html_report_100.zip`)](./Performance_testing_jmeter/Restful-Booker%20API%20Performance%20/html_report_100.zip)**
* 📊 **[250 VUs HTML Report Bundle (`html_report_250.zip`)](./Performance_testing_jmeter/Restful-Booker%20API%20Performance%20/html_report_250.zip)**
* 📝 **[Performance Strategy & Findings Documentation (`README.md`)](./Performance_testing_jmeter/Restful-Booker%20API%20Performance%20/README.md)**
