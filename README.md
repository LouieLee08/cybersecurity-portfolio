# cybersecurity-portfolio
Welcome to my cybersecurity portfolio! This repository highlights my projects, technical skills, and career aspirations in the exciting field of cybersecurity.

---

## About Me
Hello! My name is Pei Jiaxiang, and I am a student majoring in cyber security at the University of Malaya. I am passionate about learning cybersecurity and exploring how to secure systems and networks. Although I am new to this field, I am eager to grow my skills through hands-on projects and professional guidance.Thank you.
![My Profile Photo](Me.jpg)
---

## Technical Skills
Here are the technical skills and tools I have acquired so far in my cybersecurity journey:

- **Tools & Platforms:**  
  Nmap, Wireshark, Metasploit, Kali Linux, VirtualBox
- **Programming Languages:**  
  Python, C, SQL
- **Networking Concepts:**  
  TCP/IP, DNS, Firewalls, VPNs, Proxy Servers
- **Operating Systems:**  
  Linux, Windows

---

## Certifications and Training
I am currently focusing on building my foundational knowledge in cybersecurity. While I don't yet hold professional certifications, I have completed hands-on learning and challenges on the following platforms:

- **Hack The Box:**  
  - Completed several beginner to intermediate-level machines, focusing on penetration testing and privilege escalation.  
  - Learned how to exploit common vulnerabilities in web applications, misconfigured services, and network protocols.  

- **TryHackMe:**  
  - Completed modules such as "Pre-Security," "Complete Beginner," and "Introduction to Web Hacking."  
  - Gained practical experience in areas like reconnaissance, exploitation, and post-exploitation techniques.  
  - Earned badges for completing challenges like "Advent of Cyber" and "OWASP Top 10."

### Planned Certifications
I plan to pursue the following certifications in the near future:
- CompTIA Security+  
- Certified Ethical Hacker (CEH)  
- Offensive Security Certified Professional (OSCP)

## Project Experience

### 1. Automated Vulnerability Scanning with Shodan and Telegram Integration

- **Objective:**  
  Build an automated vulnerability scanning tool using the Shodan API to identify exposed services on the internet, analyze their vulnerabilities, and send real-time notifications through Telegram.

- **Tools Used:**  
  - Programming Language: Python  
  - Libraries: `shodan`, `requests`, `logging`, `datetime`, `pandas`, `plotly.express`, `streamlit`  
  - APIs: Shodan API, Telegram Bot API  

- **Methodologies:**  
  1. **Shodan Vulnerability Scanning:**  
     - Used the Shodan API to scan specific IP addresses for open ports, services, and known vulnerabilities (e.g., CVEs).  
     - Extracted detailed information about each service, such as port number, service type, and CVSS scores for vulnerabilities.  
  2. **Severity Classification:**  
     - Classified vulnerabilities into severity levels (e.g., CRITICAL, HIGH, MEDIUM) based on their CVSS scores.  
     - Implemented a helper function to dynamically assess severity levels and generate a detailed report.  
  3. **Telegram Integration:**  
     - Integrated Telegram Bot API to send vulnerability reports to a designated chat, splitting long messages into manageable parts.  
     - Used Markdown formatting to make the reports visually clear and concise.  
  4. **Streamlit-Based Dashboard:**  
     - Built an interactive UI using Streamlit for users to input configuration details such as Shodan API key, target IP address, and Telegram credentials.  
     - Visualized vulnerability severity distribution with dynamic pie charts and metrics using Plotly.

- **Results:**  
  - Successfully scanned the target IP (`58.71.197.116`) and identified vulnerabilities, including:  
    - Outdated FTP services on port 21 with known CVE vulnerabilities.  
    - Misconfigured services exposing sensitive data.  
  - Sent real-time vulnerability reports to Telegram, enabling quick action or remediation.  
  - Created a user-friendly dashboard to allow non-technical users to perform scans and review results interactively.

- **Key Features:**  
  - Automated classification of vulnerabilities based on CVSS scores.  
  - Real-time notifications via Telegram with detailed vulnerability descriptions and suggestions.  
  - Interactive vulnerability visualization with distribution charts and severity metrics.  

- **Key Learnings:**  
  - Gained hands-on experience with Shodan's API and query syntax to programmatically analyze exposed services.  
  - Learned to integrate external services (like Telegram) with Python for real-time notifications.  
  - Enhanced UI/UX design skills by building a Streamlit-based interface to simplify user interaction.  
  - Improved understanding of vulnerability scoring systems like CVSS and their practical application in security assessments.

---

#### **Example Shodan Query Syntax**
During the project, I used Shodan's advanced query syntax to filter results effectively. Some key examples include:

---

## Career Objective
As an aspiring cybersecurity professional, my ultimate goal is to specialize in penetration testing and vulnerability assessment. I aim to become a Certified Ethical Hacker (CEH) and pursue advanced certifications like the Offensive Security Certified Professional (OSCP). My long-term vision is to work in a dynamic, collaborative environment where I can contribute to securing critical infrastructures and preventing cyber threats.

---

## Contact Information
Feel free to reach out to me for collaboration, project discussions, or career opportunities:

- **Email:** a1265968926@gmail.com  
