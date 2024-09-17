# XSS Vulnerability Scanner
![cracker](https://github.com/user-attachments/assets/b22b8867-1081-4cac-9002-48955f12cc7d)



## Overview

This Python tool scans a target website for potential Cross-Site Scripting (XSS) vulnerabilities in HTML forms. It utilizes various payloads to test if user input fields are susceptible to XSS attacks. The results are then compiled into an HTML report.

## Features

- Scans HTML forms for XSS vulnerabilities.
- Uses a variety of XSS payloads.
- Generates an HTML report detailing the vulnerabilities found.
- Supports both GET and POST methods for form submissions.

## Prerequisites

- Python 3.x
- `requests` library
- `beautifulsoup4` library


You can install the required libraries using pip:

```bash
pip install requests beautifulsoup4
pip install pyfiglet
pip install requests beautifulsoup4 pyfiglet termcolor
##usage 
python xss_scanner.py
