# 🔐 OWASP Authorization Cheat Sheet

### Authorization & Access Control Research

---

## 📌 Source Information

**Source:** OWASP Authorization Cheat Sheet  
**Organization:** OWASP (Open Worldwide Application Security Project)  
**Type:** Official Web Security Guidance

**Official Source:**  
https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html

---

## 🎯 Why This Source Was Studied ?

Authorization determines whether an authenticated user is allowed to perform a specific action or access a specific resource.

This is important for our system because users may have different permissions for different cases and documents.

OWASP clearly distinguishes **authentication** from **authorization**: authentication verifies identity, while authorization determines permitted access.

---

## 🔑 Key Security Principles

### 01 — Least Privilege

Users should receive only the minimum permissions required to perform their work.

**Application in our system:**

An investigator should only receive access to the cases and documents required for their assigned work.

---

### 02 — Deny by Default

Access should be denied unless a permission has been explicitly granted.

**Application in our system:**

A newly created user should not automatically receive access to cases or documents.

Access must be explicitly assigned.

---

### 03 — Validate Permissions on Every Request

Authorization should be checked for every request instead of assuming that a previous authorization check is sufficient. 

**Application in our system:**

```text
User Request
     ↓
Authentication
     ↓
Check Role + Case Permission
     ↓
Permission Granted?
   ↙        ↘
 YES        NO
 ↓           ↓
Allow       Deny
