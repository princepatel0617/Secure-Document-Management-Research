# 🔏 NIST FIPS 180-4 — Secure Hash Standard

## Source Information

**Title:** Secure Hash Standard (SHS)  
**Publication:** FIPS PUB 180-4  
**Organization:** National Institute of Standards and Technology (NIST)  
**Published:** August 2015

**Official Source:**  
## 📖 Relevant Sections from NIST FIPS 180-4

### 1. Document Integrity & Change Detection

This section explains that secure hash algorithms can determine the integrity
of a message and that a change to the message will, with very high
probability, result in a different message digest.

[Open PDF](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf#page=15)

---

### 2. SHA-256 Digest Size & Algorithm

**Relevant Topic:** SHA-256 produces a 256-bit message digest

[Open PDF](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf#page=25)

---

## 🔎 What Does This Standard Cover?

FIPS 180-4 defines cryptographic hash algorithms used to generate
fixed-length message digests from digital data.

The standard includes:

- SHA-1
- SHA-224
- SHA-256
- SHA-384
- SHA-512
- SHA-512/224
- SHA-512/256

---

## 🔐 What Is SHA-256?

SHA-256 is a cryptographic hash algorithm that produces a
**256-bit message digest**.

In simple terms:

```text
Document
    ↓
 SHA-256
    ↓
256-bit Hash
