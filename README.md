
# OrangeHRM : Performance & Security Testing

## 📌 Project Overview
This project was part of a **Software Testing and Quality Assurance (STQA) project, focused on evaluating the **performance** and **security** of the OrangeHRM application, an open-source HR management system.  

The project aimed to:  
- Assess **system scalability and performance** under varying loads.  
- Identify and analyze **security vulnerabilities**.  
- Provide **recommendations** for performance optimization and security improvements.  

---

## 🛠️ Tools & Technologies
- **Performance Testing**: Apache JMeter  
- **Security Testing**: Burp Suite, Wireshark  
- **Test Environment**: OrangeHRM deployed on Linux server, client machines on Windows 11  

---

## 🔬 Testing Methodology
### Performance Testing
- Conducted **load, stress, spike, and endurance testing** using Apache JMeter.  
- Measured **response time, throughput, and error rates** under different user loads (10–700).  

### Security Testing
- Performed tests with **Burp Suite & Wireshark** including:  
  - SQL Injection  
  - Cross-Site Scripting (XSS)  
  - Cross-Site Request Forgery (CSRF)  
  - Authentication & Authorization bypass  
  - Session Management & Man-in-the-Middle (MITM) attacks  
  - File Upload/Download vulnerabilities  

---

## 📊 Key Findings
- OrangeHRM handled **moderate traffic efficiently**, but showed degradation at higher loads (550+ concurrent users).  
- Identified **CSRF and XSS vulnerabilities** requiring mitigation.  
- Session management and encryption were effective, but input validation needed improvement.  

---

## ✅ Conclusion
The project highlighted OrangeHRM’s strengths in scalability and areas requiring security hardening. Recommended fixes were provided to improve **resilience, data protection, and compliance with OWASP Top 10 standards**.  

---

## 📖 References
- [Apache JMeter Documentation](https://jmeter.apache.org)  
- [Burp Suite Documentation](https://portswigger.net/burp)  
- [Wireshark Documentation](https://www.wireshark.org)  
- [OWASP Top 10](https://owasp.org/Top10)  
