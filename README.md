# Cloud-Based Static Portfolio Website Hosting using Amazon S3 and CloudFront

This project is a summer training minor project focused on deploying a static portfolio website on AWS using Amazon S3 and Amazon CloudFront.

## Project Overview

The main objective of this project is to understand how cloud services can be used to host a real website in a simple, scalable, and cost-effective way. The project demonstrates static website hosting using Amazon S3 and fast global content delivery using Amazon CloudFront.

## Features

- Static portfolio website deployment
- Hosting through Amazon S3
- Content delivery through Amazon CloudFront
- Simple and cost-effective cloud architecture
- Public website access through generated endpoint and distribution URL

## Technologies Used

- HTML
- CSS
- JavaScript
- Amazon S3
- Amazon CloudFront
- AWS Management Console

## AWS Services Used

### Amazon S3
Amazon S3 is used to store the website files such as HTML, CSS, JavaScript, and images. Static website hosting is enabled on the S3 bucket to make the site accessible through a public endpoint.

### Amazon CloudFront
Amazon CloudFront is used as a Content Delivery Network (CDN). It helps deliver the website content faster by using distributed edge locations and improves performance for end users.

## Project Workflow

1. Create the portfolio website locally using HTML, CSS, and JavaScript.
2. Create an S3 bucket on AWS.
3. Upload website files to the S3 bucket.
4. Enable static website hosting for the bucket.
5. Test the S3 website endpoint.
6. Create a CloudFront distribution.
7. Connect CloudFront with the S3-hosted website.
8. Test the final deployed website using the CloudFront domain.

## Project Structure

```bash
project-folder/
│── index.html
│── style.css
│── images/
```

## Deployment Steps

### Step 1: Create S3 Bucket
Create a new S3 bucket with a unique name and keep the required permissions for hosting.

### Step 2: Upload Website Files
Upload all website files including HTML, CSS, and images into the bucket.

### Step 3: Enable Static Website Hosting
Go to bucket properties and enable static website hosting. Set `index.html` as the index document.

### Step 4: Access S3 Website Endpoint
After configuration, use the generated S3 website endpoint to verify the hosted site.

### Step 5: Create CloudFront Distribution
Create a CloudFront distribution and set the S3 website endpoint as the origin.

### Step 6: Test Final Output
After deployment, use the CloudFront domain name to access the final website.

## Learning Outcomes

- Understood static website hosting on AWS
- Learned how to configure Amazon S3 for web hosting
- Learned how CloudFront improves website delivery
- Gained practical experience with cloud deployment
- Improved understanding of AWS console-based configuration

## Screenshots




## Author

**Akshat Trivedi**  
B.Tech CSE Student, BBDNIIT
Full-Stack Developer

## License

This project is created for academic and training purposes.
