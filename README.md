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
![S3 Bucket](https://github.com/yashraj747/aws-s3-cloudfront-static-website/blob/main/screenshots/S3%20Bucket%20List.png)

### 🔹 index.html inside Bucket
![Index File](https://github.com/yashraj747/aws-s3-cloudfront-static-website/blob/main/screenshots/index.html%20inside%20bucket.png)

### 🔹 Static Website Hosting Enabled
![Hosting](https://github.com/yashraj747/aws-s3-cloudfront-static-website/blob/main/screenshots/Static%20hosting%20enabled.png)

### 🔹 Bucket Policy Applied
![Policy](https://github.com/yashraj747/aws-s3-cloudfront-static-website/blob/main/screenshots/Bucket%20policy.png)

### 🔹 CloudFront Distribution List
![CloudFront List](https://github.com/yashraj747/aws-s3-cloudfront-static-website/blob/main/screenshots/CloudFront%20distribution%20list.png)

### 🔹 CloudFront Distribution Details
![CloudFront Details](https://github.com/yashraj747/aws-s3-cloudfront-static-website/blob/main/screenshots/CloudFront%20details.png)

### 🔹 CloudFront Behavior Settings
![Behavior](https://github.com/yashraj747/aws-s3-cloudfront-static-website/blob/main/screenshots/CloudFront%20behavior%20settings.png)

### 🔹 Final Website Output
![Output](https://github.com/yashraj747/aws-s3-cloudfront-static-website/blob/main/screenshots/Final%20working%20website.png)

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
