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
[🔗 View Deployed Site](https://cdjack-web-app.s3.us-east-2.amazonaws.com/Sample%20HTML%20File.html?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAWMJTRZCXRGNX3AT2%2F20250713%2Fus-east-2%2Fs3%2Faws4_request&X-Amz-Date=20250713T192301Z&X-Amz-Expires=300&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAMaCXVzLWVhc3QtMiJHMEUCIAtRq6SpP8deIIgfhRLFcm%2FMK2akuml1T3%2BfZ4LqYIfuAiEAyyozkl0xFuvFRXHFA5zlrtKGMWETtS4LrVmG%2Fbn%2BRHIq1gIIHBAAGgw0Mzg3MzE2NTUzNDMiDHT2u2lBMh72GT%2Fv7yqzAlty45BXq9wljSQwOdI3r8j33p8mPSjaRv46pd0CRYxmDKn2Zmlk1LR5yT24a2SHGaFK36MYFQ3czOJH%2BdTWuGBByWO9mXr%2Fw9NPvDSH62eMpYhpvq%2BWVmgJE0IxtnhNdnnj99a5c3Ykv0WF3BwwaC61Ez2Uc60D6KHHvJElEF7GXnUIqi2eP4Dt2Fd7VkFETBPzb2j4SqtTzhWLRmCHmVNEfU%2BmgI%2FT%2BldRJuC976oMS2QqiUMN3JjiUS4%2B5ccf8WvSI09rFuyFc%2BOmiL2qcJCqvWNEh5XbNrdJabBQJkvXQwzG0QPbaOybeCSogqIYRKvxDba53Fh298ReBaqqe%2B%2Fzys26XSg2%2B4PWNCPYYQfyunAS5M95u%2BdzaMT77zpkP1XOFDReccjnHeADc1uEc6k%2FmPMww%2F%2FPwwY6rQJl1ZS82qL4cfYxFWJ3ic89Wl56cumBgirbg9uwXWkvD1qlYlHGueTvBNOxm2EczJJAQTKYkta%2FhY6jAsvy5TZD%2BR1ZQyqdjM2A8c7zRiX97ol7KBXI%2B4KbnLwLm9Bzzaxw4M%2BTI6qSlI5%2B%2BHNE8VbIieJxm3ajScOAju71m8o3S8PGWNAGiiReCzJyTzYV856OZEEQtxTVod56AfopjRkKWtSnk0G3rHA%2BF%2FVNE6i95YZDl9dl8TNyA1jt2wq9YUaaZqVkxJx4Jz5bgtFWQ5qN7WbFRKtdo7xXVFdK5mTFpHs2ANtZ1r3mvSXkSTwMgl%2BMXkWfH40kdjl6juuxKNvBwFE7yl3ppgnF6kUlYmrDu%2BTrfOvXaIMHFkj3o3BrSVgWsaA%2FcijTNOOEwCtI&X-Amz-Signature=78da0be50c9083e1af4270b1562c4858551d1682a27c7f0028d0d53a7e030498&X-Amz-SignedHeaders=host&response-content-disposition=inline)

---
> Created by William Roach | Charlotte, NC
