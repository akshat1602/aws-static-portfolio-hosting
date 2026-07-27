# Cloud-Based Static Portfolio Website Hosting using Amazon S3 and Amazon CloudFront

This project is a summer training minor project focused on deploying a static portfolio website on AWS using Amazon S3 and Amazon CloudFront.

## Project Overview

The main objective of this project is to understand how cloud services can be used to host a real website in a simple, scalable, and cost-effective way. The project demonstrates static website hosting using Amazon S3 and fast global content delivery using Amazon CloudFront.

## Live Project Links

- **Amazon S3 Website Endpoint:** [http://akshat-portfolio-2026.s3-website.eu-north-1.amazonaws.com/](http://akshat-portfolio-2026.s3-website.eu-north-1.amazonaws.com/)
- **Amazon CloudFront URL:** [https://d11fx53vt0i9bo.cloudfront.net/](https://d11fx53vt0i9bo.cloudfront.net/)

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
<img width="1913" height="936" alt="Screenshot 2026-07-26 220409" src="https://github.com/user-attachments/assets/8a872396-7ffd-46e5-b8ab-ee9c7ce9fbde" />
<img width="1903" height="872" alt="Screenshot 2026-07-26 220216" src="https://github.com/user-attachments/assets/1f1f7f02-f9ee-47ad-8e29-8f64aee69270" />
<img width="1908" height="875" alt="Screenshot 2026-07-26 220234" src="https://github.com/user-attachments/assets/3900cab3-bdee-4400-8035-a452a8552ce5" />
<img width="1908" height="874" alt="Screenshot 2026-07-26 220519" src="https://github.com/user-attachments/assets/5304902a-0417-4f6d-a056-85374cddcd16" />
<img width="1907" height="868" alt="Screenshot 2026-07-26 220543" src="https://github.com/user-attachments/assets/23429a10-b3b2-42a6-822f-039491701848" />

## Author

**Akshat Trivedi**  
B.Tech CSE Student, BBDNIIT  
Full-Stack Developer

## License

This project is created for academic and training purposes.
