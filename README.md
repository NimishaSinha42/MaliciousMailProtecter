# MaliciousMailProtecter
Email Management System with Security Features
Overview
A Flask-based application that fetches and manages emails securely. It scans attachments for malware, detects malicious patterns, and classifies emails as Spam or Ham to enhance security against phishing and malware attacks.

Key Features
Fetch emails via IMAP and filter by date range.
Scan attachments (PDF, Python, Bash, Java, etc.) for malicious content.
Identify dangerous file extensions and double extensions.
User-friendly web interface for managing emails and viewing results.
Technology Stack
Backend: Flask (Python)
Libraries: imaplib, PyPDF2, email
Frontend: HTML templates
How to Run
Clone the repository and install dependencies:
git clone https://github.com/your-username/Email-Management-System.git  
pip install -r requirements.txt
Run the app:
python app.py  
Access it at http://localhost:8080 and manage your emails securely.
