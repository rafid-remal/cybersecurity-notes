# 🐧 Linux Basics

---

## 📌 What is Linux?
Linux is an open-source operating system widely used in servers and cybersecurity.

---

## ⚡ Important Commands

### 📂 List files
```bash
ls
```

### 📁 Change directory
```bash
cd folder_name
```

### 📍 Show current directory
```bash
pwd
```

### 📄 Create file
```bash
touch file.txt
```

### ❌ Remove file
```bash
rm file.txt
```

---

## 🔐 File Permissions

### Example:
```bash
-rwxr-xr--
```

### Meaning:
- 👤 Owner: read, write, execute
- 👥 Group: read, execute
- 🌍 Others: read only


---

## 🚀 Advanced Commands

### 🔍 Search inside files
```bash
grep "text" file.txt
```

### 📦 Archive files (tar)
```bash
tar -cvf archive.tar folder/
```

### 📂 Extract archive
```bash
tar -xvf archive.tar
```

### 🌐 Download files
```bash
wget https://example.com/file.zip
```

### 🔄 System update (Debian/Ubuntu)
```bash
sudo apt update && sudo apt upgrade
```

### 👀 View running processes
```bash
top
```

### ⚙️ Change file permissions
```bash
chmod 755 file.txt
```

### 👤 Change file ownership
```bash
chown user:user file.txt
```
