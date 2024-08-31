# Enhancing Open-Source Project Security: A Comprehensive Source Code Analysis and Vulnerability Assessment

## Abstract
Open-source software, despite its widespread use, can harbor security vulnerabilities that expose users to risks. This project presents an in-depth security analysis of OpenMRS, an open-source medical records system. We used static and dynamic analysis tools—SonarQube, Codacy, and Semgrep—to uncover vulnerabilities such as SQL injection, Path Traversal, Hardcoded Sensitive Value Exposure, Server-Side Request Forgery, Insecure Session Management and many others. This project outlines our methodology, findings, and remediation strategies, aiming to enhance security practices within the open-source community.

## Introduction
Open-source projects drive innovation and provide accessible technology solutions. However, their security remains a significant concern due to potential flaws that can compromise integrity and reliability. This project aims to address these concerns by conducting a thorough source code analysis of OpenMRS-Core to identify and mitigate vulnerabilities. The goal is to bolster the security infrastructure of open-source software and promote proactive security measures.

## Methodology

### Projects and Tools

**Open Source Project: OpenMRS-Core**  
OpenMRS-Core is a patient-centric medical record system platform designed for healthcare providers. It relies on Java, Maven, Git, and Docker for its build and deployment processes. Our analysis focuses on enhancing the security of OpenMRS-Core to safeguard sensitive patient information.

**Static Analysis Tools**  
We employed the following tools to perform comprehensive static analysis:
- **SonarQube**: Provides in-depth metrics and actionable insights to improve code quality and security.
- **Codacy**: Delivers reports on code quality, including security vulnerabilities and coding style violations.
- **Semgrep**: Offers pattern-based detection of vulnerabilities and potential code issues.

## Experimental Results

### Vulnerabilities Detected
- XML External Entity (XXE) Vulnerability
- Path Traversal
- SQL Injection
- Hardcoded Sensitive Values Exposure
- Server-Side Request Forgery (SSRF)
- Session Management Vulnerability
- TransformerFactory DTDs Not Disabled
- Dynamic Construction of Class/Method Names - Reflection Injection

For each of the identified vulnerabilities, we documented the instances found within the codebase. Each vulnerability was analyzed in terms of its definition, potential impact, and associated risks. Comprehensive mitigation strategies were provided to address and remediate these issues effectively.

## Conclusion
Our project demonstrated the effectiveness of static analysis tools in identifying and mitigating security vulnerabilities. By applying SonarQube, Semgrep, and Codacy to the OpenMRS-Core project, we uncovered various vulnerabilities and gained insights into the strengths and weaknesses of each tool. This work underscores the importance of integrating rigorous security testing in the development cycle to enhance the security of open-source software.

