# DEPI Project: Penetration Testing Report on Metasploitable2

This project provided a comprehensive overview of penetration testing processes and methodologies by focusing on **Metasploitable 2**, a deliberately vulnerable virtual machine designed for security training purposes. Through systematic phases—footprinting, scanning, vulnerability assessment, and exploitation—we identified and exploited critical vulnerabilities in widely-used services such as Apache Tomcat, Samba, MySQL, and others.

### Key Findings
1. **Critical Vulnerabilities**: Services such as Apache Tomcat, Samba, and PostgreSQL presented high-risk vulnerabilities that could lead to unauthorized remote access or system compromise.
2. **Misconfigurations**: Weak or default credentials were prevalent, highlighting the need for strict authentication practices.
3. **Exploitation Success**: We successfully gained shell access on the system through several vectors, including FTP and SSH brute-forcing, showcasing real-world attack methods.

### Lessons Learned
- **Importance of Updates**: Regular updates to software and operating systems are crucial to addressing known vulnerabilities.
- **Need for Strong Credentials**: Default credentials and weak password policies pose significant risks and must be avoided.
- **Segmentation and Access Control**: Limiting network exposure and access to trusted IPs can mitigate many attacks.

### Future Recommendations
To further secure environments such as Metasploitable 2, organizations should:
- Transition to secure protocols (e.g., HTTPS, SFTP).
- Disable unnecessary services and ports.
- Implement monitoring and logging mechanisms to detect unauthorized activities.

This project serves as a hands-on demonstration of the potential impacts of vulnerabilities in unprotected systems and underscores the critical role of proactive security measures in maintaining robust cybersecurity defenses.

---

## Team Members
- Shady Mohamed Abdel Gawad
- Hussein Al-Yamnii Zain Al-Deen
- Ziad Alaa
- Mohamed Ashraf Mohamed Lotfy
- Omar Ahmed Badr
- Abdel Rahman Ahmed Abdel Hamid
