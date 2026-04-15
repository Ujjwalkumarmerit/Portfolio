# Static Portfolio Website on AWS
A responsive personal portfolio website hosted on AWS S3 and delivered securely via CloudFront CDN.

## 🚀 Live Demo
**CloudFront URL:** [Wait for your .cloudfront.net link and paste it here]
**S3 Endpoint:** http://ujjwal-portfolio-2026.s3-website.eu-north-1.amazonaws.com

## 🛠️ Project Overview
This project demonstrates the deployment of a high-availability static website using industry-standard Cloud and DevOps practices. It fulfills the requirements for Task 1:
- **Frontend:** Responsive HTML5 & CSS3 using Google Fonts (Inter).
- **Storage:** Amazon S3 for static object hosting.
- **Security:** SSL/TLS encryption via CloudFront (HTTPS).
- **Performance:** Global content delivery via Amazon CloudFront CDN.

## 📖 Steps Taken

### 1. Web Development
- Developed a single-page portfolio with a Hero section, 3 project cards, and a footer.
- Optimized for mobile responsiveness using CSS Flexbox.

### 2. AWS S3 Configuration
- Created a bucket named `ujjwal-portfolio-2026` and enabled **Static Website Hosting**.
- Configured a **Bucket Policy** to allow public `s3:GetObject` access.
- Uploaded `index.html` to the bucket.

### 3. CloudFront CDN Setup
- Created a CloudFront Distribution pointing to the S3 website endpoint.
- Enabled **"Redirect HTTP to HTTPS"** for secure access.
- Set `index.html` as the Default Root Object.

## 🛠️ Skills Gained
- Static website hosting on AWS S3.
- Implementing public bucket policies.
- Configuring Content Delivery Networks (CDN).
- Managing version control with Git and GitHub.
