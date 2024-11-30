---
layout: documentation
title: Getting started
order: 1
permalink: /docs
---

{% include toc.md %}

<img src="https://github.com/hangga/delvelin/blob/main/doc/delvelin-soft-black.webp?raw=true" 
alt="Delvelin Scan Demo" width="260">

![Java](https://img.shields.io/badge/Java-8+-blue?logo=java) ![Kotlin](https://img.shields.io/badge/Kotlin-1.5+-blueviolet?logo=kotlin) ![Gradle Plugin](https://img.shields.io/badge/Gradle-Plugin-brightgreen?logo=gradle) ![CWE](https://img.shields.io/badge/CWE-Standards-orange) ![CVSS](https://img.shields.io/badge/CVSS-Severity-red)
[![OSV.dev](https://img.shields.io/badge/OSV.dev-Vulnerability%20Database-blue)](https://google.github.io/osv.dev/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE) 

**Delveline** is a Code Vulnerability Analyzer for Java and Kotlin that supports best practices in security and risk management.  
By aligning with ISO/IEC 27001 principles, Delveline helps raise security awareness and improve software development security.


![Delvelin Scan Demo](https://github.com/hangga/delvelin/blob/main/doc/delvelin-scan.gif?raw=true)

[//]: # (## **Features**)

[//]: # (- Detects vulnerabilities using the CWE classification.)

[//]: # (- CVE vulnerability detection.)

[//]: # (- Supports Java and Kotlin codebases.)

[//]: # (- Configurable output formats: `LOG`, `JSON`, and `HTML`.)

[//]: # (- Easy integration as a Gradle plugin.)

[//]: # ()
[//]: # (---)

## Key Features

- **ISO/IEC 27001 Alignment**: Delveline supports best practices in security awareness and risk management.
- **CWE and CVSS Integration**: Identify and prioritize vulnerabilities using industry standards.
- **Dependency Scanning with OSV.dev**: Detect known CVEs in libraries and dependencies.
- **Thread-Safety Detection**: Highlight unsafe structures in multi-threading scenarios.

## Advantages

### **1. Security-Oriented Focus**
- **Delveline** excels as a security analysis tool, offering the ability to detect vulnerabilities such as:
    - Non-thread-safe data structures (e.g., `HashMap`, `ArrayList`) in multi-threading scenarios.
    - Hardcoded sensitive data like API tokens, passwords, or private keys.
    - XSS vulnerabilities through regex pattern analysis on code strings.
    - Detection aligned with **OWASP ASVS**, **CWE**, and **OSV.dev** standards.

  **OSV.dev**, backed by Google, provides an extensive database for detecting known vulnerabilities (CVEs) in dependencies and libraries used in your project. This enables **Delveline** to identify outdated or vulnerable dependencies more effectively.

### **2. Industry Standards and Vulnerability Scoring**
- **Delveline** integrates **CWE (Common Weakness Enumeration)** as a reference for defining vulnerabilities.
- It also uses **CVSS (Common Vulnerability Scoring System)** for severity scoring and prioritization of fixes.
- By incorporating **OSV.dev**, it adds another layer of detection by identifying known CVEs in project dependencies.


[//]: # (### **4. Multi-Platform Execution Support**)

[//]: # (- **Delveline** can be executed in various ways:)

[//]: # (    - As a standalone Java library.)

[//]: # (    - Through a **Gradle Plugin**, enabling seamless integration into build pipelines.)

[//]: # (    - As an **IntelliJ IDEA Plugin**, providing direct IDE integration without additional configuration.)

[//]: # (---)

### **3. Runtime-Assisted Static Analysis**
- **Delveline** employs a unique **runtime-assisted static analysis** approach, allowing static analysis to be supplemented by runtime data, making it more adaptive than purely static tools.


### **4. Target Audience**
- **Delveline** is designed for projects requiring deep security analysis.

[//]: # (---)

[//]: # (**Conclusion:**  )

[//]: # (**Delveline** stands out if your project needs:)

[//]: # (- Comprehensive security analysis based on industry standards.)

[//]: # (- Identification of vulnerable dependencies through **OSV.dev** and CVE detection.)

[//]: # (- Detection of thread-safety and runtime issues.)

[//]: # (- Flexible integrations &#40;Gradle, IntelliJ, Kotlin DSL&#41;.)

## **How it Works**
We leverage:
- [CWE (Common Weakness Enumeration)](https://cwe.mitre.org/data/slices/699.html): A global standard for identifying and categorizing vulnerabilities.
- [CVSS (Common Vulnerability Scoring System)](https://www.first.org/cvss/calculator/3.0): A framework for scoring the severity of vulnerabilities.
- [OSV (Open Source Vulnerabilities)](https://google.github.io/osv.dev/): A comprehensive database for open-source vulnerability information.
- **ISO/IEC 27001 Alignment**: Supporting security awareness and risk management practices aligned with global information security standards.

> **Disclaimer**: Delveline may not identify all vulnerabilities but serves as a powerful first step in securing your codebase.


{% include abbreviations.md %}
