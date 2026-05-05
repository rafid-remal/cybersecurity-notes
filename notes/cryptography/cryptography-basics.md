# 🔐 Cryptography Basics

---

## 📌 What is Cryptography?
Cryptography is the practice of securing information by transforming it into an unreadable format, only accessible to authorized users.

---

## 🔑 Key Concepts

### 🔒 Encryption
Converts readable data (plaintext) into unreadable data (ciphertext).

### 🔓 Decryption
Converts ciphertext back into plaintext.

---

## 🔢 Types of Cryptography

### 1. Symmetric Encryption
- Same key for encryption and decryption
- Fast but less secure for key sharing

**Examples:**
- AES
- DES

---

### 2. Asymmetric Encryption
- Uses two keys: Public + Private
- More secure, used in authentication

**Examples:**
- RSA

---

### 3. Hashing
- One-way function (cannot be reversed)
- Used for passwords and data integrity

**Examples:**
- MD5
- SHA-256

---

## ⚖️ Encryption vs Hashing

| Feature | Encryption | Hashing |
|--------|----------|--------|
| Reversible | Yes | No |
| Key Required | Yes | No |
| Use Case | Secure communication | Password storage |

---

## 🧪 Common Commands (Linux)

### 🔐 Generate SHA-256 hash
```bash
echo "hello" | sha256sum
```

---

### 🔑 Generate MD5 hash
```bash
echo "hello" | md5sum
```

---

### 🔒 Encrypt file using OpenSSL (AES)
```bash
openssl enc -aes-256-cbc -salt -in file.txt -out file.enc
```

---

### 🔓 Decrypt file
```bash
openssl enc -d -aes-256-cbc -in file.enc -out file.txt
```

---

### 🔑 Generate RSA Key Pair
```bash
openssl genrsa -out private.key 2048
openssl rsa -in private.key -pubout -out public.key
```

---

## 🧠 Important Concepts

### 🔐 Public Key
Shared openly, used for encryption.

### 🔑 Private Key
Kept secret, used for decryption.

---

### 🧾 Digital Signature
Used to verify authenticity and integrity of data.

---

### 🧂 Salting
Adding random data before hashing to prevent attacks.

---

## ⚠️ Common Attacks

- Brute Force Attack
- Dictionary Attack
- Rainbow Table Attack
- Man-in-the-Middle (MITM)

---

## 🛠️ Pro Tips
- Never store passwords in plain text  
- Always use **SHA-256 or stronger** (avoid MD5 in real systems)  
- Use salting + hashing together  
- Prefer **AES-256** for encryption  

---

## 🚀 Next Steps
- Learn how HTTPS uses cryptography  
- Explore TLS/SSL handshake  
- Practice with tools like OpenSSL  

---
