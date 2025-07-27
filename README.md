# Cyber Blitz - Advanced Web Vulnerability Scanner

([https://via.placeholder.com/150](https://static.wikia.nocookie.net/cybernations/images/b/bd/JaegarFamily.png/revision/latest?cb=20110115010616)) 

Cyber Blitz is a powerful, comprehensive web vulnerability scanner designed to identify security issues in web applications. With a modern UI inspired by professional security tools like Burp Suite, it provides a complete suite of scanning capabilities for security professionals and developers.

## Features

- **Comprehensive Vulnerability Detection**:
  - XSS (Cross-Site Scripting)
  - SQL Injection
  - LFI/RFI (Local/Remote File Inclusion)
  - RCE (Remote Code Execution)
  - SSRF (Server-Side Request Forgery)
  - XXE (XML External Entity)
  - IDOR (Insecure Direct Object Reference)
  - CSRF (Cross-Site Request Forgery)
  - SSTI (Server-Side Template Injection)

- **Professional Tools**:
  - Intruder for parameter fuzzing
  - Repeater for manual request testing
  - Decoder for encoding/decoding
  - Comparer for analyzing differences
  - Database extractor for SQLi exploitation

- **Reporting**:
  - Multiple export formats (JSON, CSV, HTML, PDF, SARIF)
  - Detailed vulnerability information
  - Scan history and database storage

- **Authentication Support**:
  - Basic Auth
  - Cookies
  - Bearer Tokens
  - OAuth
  - JWT

## Installation

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Dependencies

Install the required dependencies using pip:

```bash
pip install -r requirements.txt
