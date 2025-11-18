🔐 Project Title

Detecting Data Leaks via SQL Injection

📌 1. Introduction

SQL Injection (SQLi) is one of the most dangerous web vulnerabilities that leads to data leaks, unauthorized access, and complete database compromise.
This mini project demonstrates how SQL queries can be analyzed and categorized as Safe or Unsafe before execution, preventing data exposure.

This is a Local Detection Tool (No cloud deployment needed).

🎯 2. Objectives
	•	Detect SQL Injection attempts in user-given queries
	•	Prevent chances of data leaks by identifying malicious patterns
	•	Categorize attacks (UNION, DROP, INFORMATION_SCHEMA, etc.)
	•	Provide a simple frontend + backend demonstration
	•	Educate beginners on SQL injection risks

🧠 3. Background/Theory

✔ What is SQL Injection?
A technique where attackers manipulate SQL queries to:
	•	Steal data
	•	Delete tables
	•	Bypass authentication
	•	Extract database structure
	•	Cause time delays
  
✔ Why SQLI causes Data Leaks?
Because attackers can use:
	•	UNION SELECT to read private data
	•	INFORMATION_SCHEMA to expose database structure
	•	OR 1=1 to bypass login
	•	DROP TABLE to destroy data
	•	WAITFOR DELAY to test vulnerabilities
This project detects these patterns.

🧪 11. Testing Summary
	•	All common SQL injection patterns tested
	•	Multiple-line queries supported
	•	Complex queries detected accurately
	•	Frontend and backend communication verified

	SCREENSHOTS
	<img width="1294" height="1080" alt="image" src="https://github.com/user-attachments/assets/0c445aaf-2d2d-4a21-85c9-11b72f9d8b8f" />
	<img width="1284" height="1080" alt="image" src="https://github.com/user-attachments/assets/6309e622-34f1-45a9-94fb-757fc540eb93" />




  🏁 13. Conclusion

This project successfully implements a working system that detects SQL injection attempts and prevents possible data leaks.
It is simple, accurate, and demonstrates backend + frontend integration effectively.

AUTHOR:
Geethanjali M
