# ☁️ AWS S3 Static Website

A modern responsive static website hosted on **Amazon S3**, with a custom 404 error page and EC2-to-S3 integration using AWS CLI and IAM.

## 🌐 Live Website

👉 [**Visit Live Website**](http://ec2-to-s3-bucket111111.s3-website.ap-south-1.amazonaws.com)

## 📌 Project Overview

This project demonstrates the deployment of a static website using Amazon S3.

The website includes:

- Modern responsive UI
- Custom CSS animations
- Responsive design
- Custom 404 error page
- S3 static website hosting
- EC2 and S3 integration
- AWS CLI usage
- IAM Role-based authentication

## 🏗️ AWS Architecture

```text
                    AWS Cloud
                       │
                       │
                 ┌─────▼─────┐
                 │    EC2    │
                 │ Instance  │
                 └─────┬─────┘
                       │
                   AWS CLI
                       │
                   IAM Role
                       │
                 ┌─────▼─────┐
                 │    S3     │
                 │  Bucket   │
                 └─────┬─────┘
                       │
             ┌─────────┴─────────┐
             │                   │
        index.html           error.html
             │                   │
             └─────────┬─────────┘
                       │
                       ▼
                Static Websitegit add README.md