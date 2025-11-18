# Task 3: Password Cracking using John the Ripper

## 📌 Objective
To crack a password hash using brute-force / dictionary attack with John the Ripper as part of the cyber security lab task.

## 🧰 Tool Used
- John the Ripper
- OS: Kali Linux (or your OS)

## 🔐 Hash Details
- Hash file: `hash.txt`
- Hash type: linux password hash

## 🧨 Commands Used

- zip2john Newfile.txt.zip > hash.txt
- john --format=zip hash.txt
