---
layout: default
---

![Java](https://img.shields.io/badge/Java-8+-blue?logo=java) ![Kotlin](https://img.shields.io/badge/Kotlin-1.5+-blueviolet?logo=kotlin) ![Gradle Plugin](https://img.shields.io/badge/Gradle-Plugin-brightgreen?logo=gradle) ![CWE](https://img.shields.io/badge/CWE-Standards-orange) ![CVSS](https://img.shields.io/badge/CVSS-Severity-red)
[![OSV.dev](https://img.shields.io/badge/OSV.dev-Vulnerability%20Database-blue)](https://google.github.io/osv.dev/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE) 

<!-- ## **Introduction**

**Delveline** is a Code Vulnerability Analyzer for Java and Kotlin that supports best practices in security and risk management.  
By aligning with ISO/IEC 27001 principles, Delveline helps raise security awareness and improve software development security. -->

## **Example Report**

- In Html Format

<img width="100%" src="https://github.com/delvelin/blog/blob/master/_posts/delvelin-report-html.png?raw=true"/>

- In Console Log

<img width="100%" src="https://github.com/delvelin/blog/blob/master/_posts/delvelin-report-console-1.png?raw=true"/>

<img width="100%" src="https://github.com/delvelin/blog/blob/master/_posts/delvelin-report-console-2.png?raw=true"/>


<!-- ![delvelin process](https://github.com/delvelin/blog/blob/master/_posts/delvelin-diagram-hi-res-compress.png?raw=true)

<a href="https://delvelin.github.io/blog/how-it-works/" class="btn">Read more</a> -->

<!-- ## **Features**

### **1. Security-Oriented Focus**
- **Delveline** excels as a security analysis tool, offering the ability to detect vulnerabilities such as:
    - Non-thread-safe data structures (e.g., `HashMap`, `ArrayList`, `StringBuilder`, etc) in multi-threading scenarios.
    - Hardcoded sensitive data like API tokens, passwords, private keys, etc.
    - Command Injection.
    - SQL Injection.
    - XSS vulnerabilities.
    - Weak Cryptographic such as MD5 or SHA-1 are considered vulnerable because they can be easily cracked..
    - Dependency Vulnerability Detection (OSV.dev).

  **OSV.dev**, backed by Google, provides an extensive database for detecting known vulnerabilities (CVEs) in dependencies and libraries used in your project. This enables **Delveline** to identify outdated or vulnerable dependencies more effectively.

- **Coming soon (open contribution)**
    - Insecure Http connection : Because unencrypted HTTP connections for sensitive data communication can cause data to be leaked or intercepted by third parties.
    - Reflection Class Vulnerability: Reflection can cause vulnerabilities if it allows access or modification of sensitive classes and methods without adequate controls.
    -  Insecure Deserialization

### **2. Industry Standards and Vulnerability Scoring**
We leverage:
- [CWE (Common Weakness Enumeration)](https://cwe.mitre.org/data/slices/699.html): A global standard for identifying and categorizing vulnerabilities.
- [CVSS (Common Vulnerability Scoring System)](https://www.first.org/cvss/calculator/3.0): A framework for scoring the severity of vulnerabilities.
- [OSV (Open Source Vulnerabilities)](https://google.github.io/osv.dev/): A comprehensive database for open-source vulnerability information.
- **ISO/IEC 27001 Alignment**: Supporting security awareness and risk management practices aligned with global information security standards.

> **Disclaimer**: Delveline may not identify all vulnerabilities but serves as a powerful first step in securing your codebase.


<!-- ### **3. Runtime-Assisted Static Analysis**
- **Delveline** employs a unique **runtime-assisted static analysis** approach, allowing static analysis to be supplemented by runtime data, making it more adaptive than purely static tools. -->

<!-- ### **3. Flexible integration**
- **Delveline** can be installed as a Gradle plugin or used as a Java/Kotlin library.


## **License**
This project is licensed under [MIT License](LICENSE).

---

## **Contributing**
Contributions are welcome! Feel free to submit issues or pull requests for new features or improvements.

This project is still a work in progress, and your contributions are highly valuable in helping us improve and refine it.

If you find this project useful and would like to support its development, we would greatly appreciate your donations. Your generosity will go a long way in ensuring the growth and sustainability of this initiative.

Thank you for your support!

- 📧 Email: bazeniancode@gmail.com
- 🌐 [GitHub Repository](https://github.com/hangga/delvelin)  -->
