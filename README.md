
# 🔥 Stored XSS Attack – Mutillidae Training

This repository documents a **Stored XSS (Cross-Site Scripting)** attack performed in a **legal lab environment** using [Mutillidae](https://sourceforge.net/projects/mutillidae/) and Kali Linux. The goal of this exercise is to simulate a browser-based attack that captures user cookies and sends them to an attacker-controlled machine.

---

## 📌 Objective

- Perform a **Stored XSS** attack on the blog comment feature in Mutillidae.
- Inject a malicious script that captures the user's session cookie.
- Exfiltrate the cookie to a **listener running on Kali Linux**.

---

## 🧪 Lab Setup

- 🧱 **Victim Web App**: Mutillidae (http://192.168.237.131)
- 🐍 **Attacker Machine**: Kali Linux (192.168.237.130)
- 💻 **Network**: Host-Only / Internal (VirtualBox)

---

## 💥 Attack Scenario

### 1. Open the Blog Comment Page:
