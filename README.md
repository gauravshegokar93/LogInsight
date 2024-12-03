LogInsight: Comprehensive Log Analysis Script
Overview:
LogInsight is a robust Python script designed to analyze server log files, providing critical insights into system activity and security. It caters to cybersecurity professionals and developers, helping to uncover patterns, monitor endpoint usage, and identify potential security threats like brute-force attacks.

Key Features:

Count Requests per IP Address

Extracts all IP addresses from the log file.
Analyzes and ranks IPs based on request frequency, displaying results in descending order.
Identify Frequently Accessed Endpoints

Tracks and displays the most accessed endpoints in the log file.
Includes usage counts for a detailed overview.
Detect Suspicious Activity

Identifies signs of brute-force login attempts using status codes (401) or failure messages.
Flags IPs surpassing a configurable threshold (default: 10 failed attempts).
Output and Usability:

Saves the analysis to a CSV file (log_analysis_results.csv), featuring detailed sections for IP activity, endpoint frequency, and suspicious activity detection.
Requirements:

Python 3.7+
Libraries: collections, re, csv
Applications:
LogInsight is ideal for system administrators, cybersecurity experts, and developers aiming to secure systems and optimize performance through efficient log analysis.
