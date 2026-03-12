# CyberSpy – Phishing & Cyber Attack Detection System

## Overview

CyberSpy is a web-based cybersecurity application developed using **Python and Django** that analyzes uploaded data and identifies potential cyber threats.
The system detects different types of **network and phishing-related attacks** by analyzing patterns, keywords, and dataset indicators.

The platform also includes **secure file sharing, threat analysis, and attack reporting features**.

---

## Features

* User registration and login system
* Secure file sharing between users
* Cyber attack detection based on dataset analysis
* Threat classification and ranking
* Attack analytics and visualization
* Inbox and messaging system
* Feedback system for users

---

## Attack Detection

The system analyzes uploaded content and classifies potential cyber threats into categories such as:

* IP Fragment Attack
* TCP Based Attack
* UDP Based Attack
* SYN Flood Attack
* Slowloris Attack
* NTP Amplification Attack
* Ping of Death Attack
* HTTP Flood Attack
* Layer Based Attack

If no malicious patterns are detected, the system labels the data as **Unlabeled Data**.

---

## Technologies Used

* Python
* Django Framework
* MySQL Database
* Regular Expressions (Regex)
* HTML / CSS
* CSV Dataset Analysis

---

## System Architecture

The application follows a **Django MVC architecture**:

* **Views** – Handle request processing and attack detection logic
* **Models** – Manage database interactions for users, files, and attack data
* **Templates** – Render user interfaces and results

Uploaded data is analyzed using pattern matching and compared with dataset indicators to determine potential cyber attacks.

---

## Dataset

The system uses a dataset containing network attack indicators and keywords associated with different cyber attacks.
The dataset is processed and analyzed to identify patterns that match known attack behaviors.

---

## Key Functional Modules

### User Management

* User registration
* Login authentication
* Profile management

### File Sharing

* Users can send files to other users
* Inbox system for receiving files
* Reply system for communication

### Attack Detection

* File content analysis
* Pattern matching using keyword detection
* Classification of potential cyber attacks

### Data Analysis

* Labeled and unlabeled attack data
* Visualization of attack frequency using charts

---

## Installation

1. Clone the repository

```bash
[git clone https://github.com/yourusername/CyberSpy.git](https://github.com/JaisonPJoy/CyberSpy-Phishing-and-Cyber-Attack-Detection-System.git)
```

2. Navigate to the project directory

```bash
cd CyberSpy
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Configure the MySQL database in Django settings.

5. Run the Django development server

```bash
python manage.py runserver
```

6. Open the application in your browser

```
http://127.0.0.1:8000
```

---

## Future Improvements

* Implement machine learning models for more accurate threat detection
* Add real-time email phishing analysis
* Improve attack classification using AI techniques
* Enhance visualization dashboards for cyber attack trends

---

## Author

Jaison P Joy
