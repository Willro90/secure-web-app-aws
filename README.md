# secure-web-app-aws
AWS lab project to deploy and secure a static web app using S3, CloudFront, IAM, CloudTrail, and Config
# 🚀 Secure Web App on AWS

This project demonstrates how I deployed and secured a static website using AWS services. It was built as part of my cloud security learning journey and aligns with Technical Account Manager responsibilities.

## 🔐 Tools & Services Used
- Amazon S3 (static site hosting)
- Amazon CloudFront (HTTPS CDN delivery)
- IAM (bucket policies + access control)
- AWS CloudTrail (monitoring/logging)
- AWS Config (compliance rules)

## 🔨 What I Did
1. Created an S3 bucket to host a simple static HTML site
2. Set up CloudFront to restrict access and enforce HTTPS
3. Created a basic bucket policy to limit access to CloudFront only
4. Enabled CloudTrail and AWS Config to monitor usage and compliance
5. Verified `s3-bucket-ssl-requests-only` rule and access logs

## 📸 Screenshots
<img width="1866" height="881" alt="S3" src="https://github.com/user-attachments/assets/7bb30ee8-36dc-4da6-ad1f-09057f242811" />
<img width="1865" height="891" alt="Cloudfront" src="https://github.com/user-attachments/assets/f6b8f07f-46cb-4dc8-80e1-b2e1bc524364" />
<img width="1867" height="892" alt="logs" src="https://github.com/user-attachments/assets/7ca2baf1-a08e-4c1f-a2a8-601084f41cdf" />


## ✅ Outcome
The static site is now securely hosted, accessible only via HTTPS, and monitored for compliance. This lab gave me hands-on experience with IAM, CDN setup, and basic cloud security practices.
[🔗 View Deployed Site]() Troubleshooting 

---
> Created by William Roach | Charlotte, NC
