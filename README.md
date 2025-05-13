# 🔍 Admin CP Finder 🔍

## 🛡️ Overview
Admin CP Finder is a powerful tool designed to discover admin control panels of websites. It systematically checks for common admin panel paths based on different web technologies.

## ✨ Features
- 🌐 Support for multiple web technologies:
  - PHP
  - ASP
  - ASPX
  - CFM
  - JavaScript
  - CGI
  - BRF
- 🚀 Fast scanning capability
- 🔍 Pattern recognition for login pages
- 💪 Customizable timeout settings

## 🔧 Installation

### Requirements
- Perl
- LWP::UserAgent module
- HTTP::Request module

### Setup
1. Install Perl if not already installed
2. Install required modules:
```
cpan install LWP::UserAgent
cpan install HTTP::Request
```

## 🚀 Usage
1. Run the script:
```
perl adminfinder.pl
```
2. Enter the target website URL (without `http://`)
3. Select the website technology (PHP, ASP, ASPX, CFM, JS, CGI, BRF)
4. Wait for results to be displayed

## 📋 Output
The tool will display:
- Found admin panels (if any)
- Failed attempts

## ⚠️ Disclaimer
This tool is for educational purposes only. Always obtain proper authorization before scanning any website. Unauthorized scanning may be illegal in some jurisdictions.

## 👨‍💻 Author
Swoxy

## 📜 License
This project is available for personal use only. 
