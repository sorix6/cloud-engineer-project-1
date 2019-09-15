# # Deploy a Static Website on AWS

The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. In this project, a static website is deployed to AWS.

The followig steps have been taken for the deployment of the website:

1. Create a S3 bucket
![S3 bucket](https://raw.githubusercontent.com/sorix6/cloud-engineer-project-1/master/images/s3-bucket.JPG)

2. Upload the website files to the S3 bucket
![S3 bucket](https://raw.githubusercontent.com/sorix6/cloud-engineer-project-1/master/images/s3-bucket.JPG)

3. Secure the S3 bucket with IAM (Identity and Access Management) policies
![S3 bucket](https://raw.githubusercontent.com/sorix6/cloud-engineer-project-1/master/images/s3-bucket.JPG)
**Making the bucket public is a required step for static websites hosting.**

4. Configure the S3 bucket for website hosting
![S3 bucket](https://raw.githubusercontent.com/sorix6/cloud-engineer-project-1/master/images/s3-bucket.JPG)

5. Distribute the website via CloudFront 
![S3 bucket](https://raw.githubusercontent.com/sorix6/cloud-engineer-project-1/master/images/s3-bucket.JPG)

The Domain Name of the distribution: d2r54jy43xh9v6.cloudfront.net

The website can be accessed at [http://d2r54jy43xh9v6.cloudfront.net/index.html](http://d2r54jy43xh9v6.cloudfront.net/index.html)
