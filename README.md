# ☁️ Static Website Hosting using Amazon S3

## 📌 Project Overview
Serverless static website hosting using Amazon S3 without any compute resources. The website is served via the S3 Website Endpoint, demonstrating a fully serverless static content hosting model.

## 💻 Tech Stack
- Amazon S3  
- Static Website Hosting

## 🏗 Architecture Flow
Client → S3 Website Endpoint → index.html 

![S3 Architecture](s3-architecture.jpg)

## ⚙️ Implementation Summary
- Created a globally unique S3 bucket and configured region  
- Enabled Static Website Hosting (`index.html` as index document)  
- Configured public read access via bucket policy  
- Uploaded website files and verified accessibility through the endpoint

## 🔐 Security Considerations
- Public access is required (not suitable for sensitive data)  
- No IAM credentials are exposed  
- Fully serverless, reducing operational overhead

## ⚠️ Limitations
- HTTP only (no built-in HTTPS)  
- No CDN integration, which may lead to higher latency for global users

## 🚀 Key Outcomes
- Fully serverless hosting model  
- Automatic high availability  
- Cost-efficient static content delivery

## 📂 Repository Files
- `index.html` – Complete static website (HTML, CSS, JavaScript)  
- `README.md` – Project documentation  
- `s3-architecture.jpg` – Architecture diagram  
- `Snapshots-2.pdf` – Deployment snapshots

## 📸 Snapshots Include
- Live Website Output via S3 Endpoint  
- S3 Bucket Overview  
- Static Website Hosting Configuration  
- Bucket Policy Configuration
