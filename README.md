# 🔐 Malicious IP Intelligence System

## 📌 Description
This project detects and classifies IP addresses as Safe, Suspicious, or Malicious using threat intelligence APIs.

## 🚀 Features
- Checks IP reputation using AbuseIPDB API
- Classifies IP addresses based on risk score
- Reads IPs from file
- Saves output in CSV format

## 🛠 Technologies Used
- Python
- Requests Library
- AbuseIPDB API

## 📂 Project Structure
- ip_checker.py → Main script
- ips.txt → Input file
- output.csv → Output file

## ▶️ How to Run
1. Install Python
2. Install requests:
   pip install requests
3. Add your API key in code
4. Run:
   python ip_checker.py

## 📸 Output Example
8.8.8.8 → Safe  
185.220.101.1 → Malicious  

## 📚 Learning Outcome
- API integration
- Cybersecurity basics
- Threat intelligence usage
