# Web Security & Log Analysis

## 📌 Objective
To analyze web server access and error logs in a simulated environment to identify suspicious traffic patterns, potential brute-force attempts, and unauthorized access signatures.

---

## 🛠️ Concepts & Tools Covered
* **Concepts:** Web Server Logs (Access/Error), HTTP Status Codes, Threat Detection, IP Tracking.
* **Analysis Focus:** Spotting unusual request frequencies, error spikes, and malicious payloads in server traffic.

---

## 📋 Key Analysis Steps
1. **Log Inspection:**
   * Reviewing standard log formats (such as Apache/Nginx logs) to understand client requests and server responses.
2. **Anomaly Detection:**
   * Filtering logs for suspicious status codes (like 401 Unauthorized, 403 Forbidden, or repeated 404 Not Found errors indicating scanning).
3. **Mitigation & Defense:**
   * Implementing rate limiting, blocking malicious IPs, and strengthening web application firewalls (WAF).

---

## 📸 Screenshots
![Log Analysis Output](Screenshot%202026-10-01%20072244.png)

---

## 🚀 Key Takeaway
Learned how continuous log monitoring acts as an early warning system for web applications, enabling security analysts to catch and mitigate attacks early.
