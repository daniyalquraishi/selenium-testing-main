

# Web Automation Testing using Selenium & Cucumber (Boiler-plate)
📩 Contact us: daniyalqureshi212@gmail.com

---

## Overview

A robust Selenium-based test automation framework built with Java, TestNG, and Cucumber.

## Features

- Page Object Model design pattern
- Multi-browser support (Chrome, Firefox, Edge, Safari)
- Parallel test execution
- Headless mode support
- Grid execution capability
- Cloud platform integration (BrowserStack, LambdaTest)
- Extent Reports integration
- Environment-based configuration
- Screenshot capture on test failure

## Prerequisites

- Java JDK 17 or higher
- Maven 3.8.x or higher
- Chrome/Firefox/Edge browser installed
- Selenium Grid (optional, for grid execution)
- BrowserStack/LambdaTest account (optional, for cloud execution)

## Running Tests

### Basic Execution

```bash
mvn clean test -Denv=qa -Dbrowser=chrome -Dbrowser.mode=normal
```

### Headless Mode
```bash
mvn clean test -Denv=qa -Dbrowser=chrome -Dbrowser.mode=headless
```

### Different Environments
```bash
mvn clean test -Denv=staging
mvn clean test -Denv=production
```

### Grid Execution
```bash
mvn clean test -Denv=qa -Dgrid.enabled=true
```

## Reports

Test execution reports can be found in:
- Extent Reports: `test-output/ExtentReport_<timestamp>.html`
- Cucumber Reports: `target/cucumber-reports/`

## Configuration

Environment-specific configurations are stored in `src/test/resources/config/` directory.

## Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details. Mention TestSquad on LinkedIn :)

## Support

Need help implementing this framework or looking for custom automation solutions? Contact TestSquad:

- 
## 👤 Author
*Daniyal Qureshi*  
[🔗 LinkedIn Profile](https://www.linkedin.com/in/daniyalquraishi/)
📧 Email: daniyalqureshi212@gmail.com
💼 Services: Mobile Testing, Automation Solutions, QA Consulting


