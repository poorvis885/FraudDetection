**FraudShield++** : Financial Fraud Detection System (C++ DSA Project)



**Overview**


A C++ & DSA-based system to detect suspicious financial transactions, fraud rings, and card cloning. Uses Trie & Graph algorithms to analyze transaction patterns.



**Features**


Suspicious transaction detection based on amount thresholds.


Fraud ring detection using DFS in transaction graph.


Card cloning detection using Trie data structure.


Real-time transaction monitoring with CSV and SQL logging.


Interactive CLI with transaction history and alerts.




**Technologies Used**


Language: C++ (DSA concepts)


Data Structures: Trie, Graph (DFS), Vector, HashMap


External: CSV parsing, system call to Python-SQL connector


Database: Python-based SQL insertion script


CLI Menu-based user interface


**Installation Guide**


Clone repo: git clone (https://github.com/poorvis885/FraudDetection)


Compile: g++ fraudshield.cpp -o fraudshield


Run: ./fraudshield


Ensure transactions.csv exists with header or use option 1 to add entries.


Ensure insert_to_sql.py exists to sync with database (optional).

**How to Use**

Run FraudShield++.


Add new transactions via CLI.


View suspicious transactions.


Detect fraud rings.


Check manual card cloning.


View all transaction history.

**Future Enhancements**

Add ML-based anomaly detection.


Implement REST API for real-time integration.


Add user authentication for system access.


GUI-based dashboard (Qt / Electron).

**License**
MIT License. This project is the intellectual property of Poorvi Shrivastava.

🔗 **Connect with me**: https://www.linkedin.com/in/poorvi-shrivastava-4a34a9256/

