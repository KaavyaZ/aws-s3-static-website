# AWS S3 Static Website

## Overview

This is the first project in my AWS & DevOps portfolio. Beyond deploying a static webpage, I used this project to understand how Amazon S3 Static Website Hosting works and how bucket policies can control access to individual objects.

## Technologies Used

- Amazon S3
- HTML

## Features

- Static website hosting
- Custom index document
- Object-level bucket policy
- Public access configured using S3 bucket policies

## Experiments

As part of this project, I explored object-level permissions by:

- Granting public read access only to `index.html`
- Verifying the website loaded successfully
- Uploading another object without modifying the bucket policy
- Confirming it returned **403 Access Denied**, demonstrating object-level access control

## What I Learned

- Difference between S3 buckets and objects
- How S3 Static Website Hosting works
- Difference between an object URL and a website endpoint
- HTML is served by Amazon S3 and rendered by the browser
- Bucket policies can grant permissions to individual objects
  
## Future Improvements

- Amazon CloudFront
- Infrastructure as Code using AWS CloudFormation
- Automated deployments with GitHub Actions
- HTTPS

## Project Status

- ✅ Completed
- Last updated: July 2026

## Next Project

Build on this website by placing Amazon CloudFront in front of the S3 bucket to improve performance and learn about content delivery.
