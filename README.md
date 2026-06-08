# Sandesh Sahu - Personal Portfolio

[![Live Website](https://img.shields.io/badge/Live_Website-sandesh--op.com-blue?style=for-the-badge&logo=google-chrome)](http://sandesh-op.com)

A personal portfolio website showcasing my technical skills, experience, and projects in Linux administration, networking, cloud computing, and web infrastructure. 

This repository contains the static source code (HTML, CSS, JS) for my portfolio, which is deployed automatically to a custom-configured bare-metal server via a modern CI/CD pipeline.

## 🚀 Tech Stack & Infrastructure

* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5
* **Hosting:** Oracle Cloud VPS (Ubuntu)
* **Web Server:** Bare-metal Nginx (Custom configured for clean URLs and error routing)
* **CI/CD:** GitHub Actions (Automated zero-downtime deployment via SFTP)
* **Security & DNS:** Cloudflare (SSL/TLS, CDN), UFW, and SSH key-only authentication

## 🛠️ Infrastructure & Customizations

This project was designed to demonstrate practical systems administration and deployment skills:
* **Automated CI/CD:** Push-to-deploy workflow using GitHub Actions securely syncing updates to the VPS.
* **Clean URL Routing:** Nginx server blocks manually configured to serve extensionless `.html` files for a professional URL structure.
* **Custom Error Handling:** Internal routing configured for a custom 404 error page.
* **Server Hardening:** Locked down Oracle VPS with disabled password authentication and strict UFW firewall rules.
* **Static Conversions:** Replaced the default PHP contact form (which requires a backend server) with a lightweight, responsive modal linking directly to email and professional social profiles.

## 📜 Credits & Attribution

This website's frontend UI is based on the **FolioOne** template provided by [BootstrapMade](https://bootstrapmade.com/). 

* **Template Name:** FolioOne
* **Author:** BootstrapMade.com
* **Template License:** [BootstrapMade License](https://bootstrapmade.com/license/)

As per the free tier usage guidelines, the original design credit link remains intact in the footer of the HTML files. 

---
*Exploring professional workflows and maintained by [Sandesh Sahu](https://github.com/sandeshsahu1).*