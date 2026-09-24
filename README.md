# My-static-web-hosting
AWS Static Website Hosting Project
A scalable and secure serverless static website hosting architecture implemented using cloud storage principles, custom error handling, and web hosting best practices.

🚀 Project Overview

This project demonstrates how to host a high-performance static website on the cloud without managing traditional backend servers. It simulates a production-ready setup similar to Amazon S3 combined with AWS CloudFront for content delivery.
🛠️ Architecture & Features
 Core Content: Served via a clean, responsive ⁠index.html⁠ file paired with custom styling (⁠style.css⁠).
 Custom Error Handling: Includes a dedicated ⁠error.html⁠ page configured to catch broken routes or missing files (mirroring S3 custom 404 error page redirection).
 Security & Access Control: Designed with public-read object policies and secure static asset delivery in mind.
 Cost Optimization: Completely serverless architecture, eliminating idle compute costs.

📂 File Structure

├── index.html       # Main landing page

├── style.css        # Custom stylesheet for UI design

└── error.html       # Custom 404 error handling page

🌐 Live Demo

You can view the live hosting output here:
https://muhammedaliansari.github.io/My-static-web-hosting/
