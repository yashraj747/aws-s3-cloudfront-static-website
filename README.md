# 🚀 AWS Static Website Hosting (S3 + CloudFront)

![AWS](https://img.shields.io/badge/AWS-S3%20%2B%20CloudFront-orange)
![Status](https://img.shields.io/badge/Status-Deployed-success)
![Project](https://img.shields.io/badge/Level-Beginner%20DevOps-blue)

---

## 📌 Overview

Deployed a **static website on AWS S3** and distributed it globally using **CloudFront CDN with HTTPS support**.

This project demonstrates a real-world **cloud hosting architecture** using AWS services.

---

## 🧱 Architecture

User → CloudFront (CDN) → S3 Bucket

---

## ⚙️ Tech Stack

- **Amazon S3** – Static file hosting  
- **Amazon CloudFront** – CDN + HTTPS  
- **HTML** – Frontend  

---

## 🌐 Features

- Static website hosting  
- Global CDN delivery  
- HTTPS enabled  
- Low-latency performance  
- Public access configuration  

---

## 🛠️ Setup (Quick Summary)

1. Create S3 bucket and upload `index.html`  
2. Enable static website hosting  
3. Configure public access (bucket policy)  
4. Create CloudFront distribution  
5. Set default root object = `index.html`  
6. Access via CloudFront URL  

---

## 📸 Screenshots

### 🔹 S3 Bucket List
![S3 Bucket](screenshots/1-s3-bucket.png)

### 🔹 index.html inside Bucket
![Index File](screenshots/2-index-file.png)

### 🔹 Static Website Hosting Enabled
![Hosting](screenshots/3-static-hosting.png)

### 🔹 Bucket Policy Applied
![Policy](screenshots/4-bucket-policy.png)

### 🔹 CloudFront Distribution List
![CloudFront List](screenshots/5-cloudfront-list.png)

### 🔹 CloudFront Distribution Details
![CloudFront Details](screenshots/6-cloudfront-details.png)

### 🔹 CloudFront Behavior Settings
![Behavior](screenshots/7-cloudfront-behavior.png)

### 🔹 Final Website Output
![Output](screenshots/8-final-output.png)

---

## ✅ Result

✔ Website successfully deployed using AWS  
✔ Accessible via CloudFront with HTTPS  
✔ Improved performance using CDN  

---

## 🎯 Key Learnings

- Difference between S3 **website endpoint vs REST endpoint**  
- How CDN improves performance  
- Importance of correct origin configuration  
- Debugging CloudFront errors  

---

## 📌 Future Improvements

- Custom domain (Route 53)  
- SSL with AWS Certificate Manager  
- CI/CD with GitHub Actions  
- Better UI design  

---

## 👨‍💻 Author

**Yashraj**  
DevOps Student
