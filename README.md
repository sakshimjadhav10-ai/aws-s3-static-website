# AWS S3 Static Website Hosting ☁️

A responsive static website hosted using Amazon S3.

## 🚀 Project Overview

This project demonstrates how to deploy a static website using Amazon S3 and integrate an EC2 instance with S3 using the AWS CLI.

## 🛠️ AWS Services Used

- Amazon S3
- Amazon EC2
- AWS IAM
- AWS CLI

## ✨ Features

- Responsive static website
- Modern HTML/CSS design
- Custom 404 error page
- S3 static website hosting
- EC2 to S3 integration
- IAM Role-based authentication
- AWS CLI integration

## 🏗️ Architecture

```text
Laptop
   │
   │ SSH
   ▼
 EC2 Instance
   │
   │ AWS CLI
   ▼
 IAM Role
   │
   ▼
 Amazon S3
   │
   ├── index.html
   └── error.html