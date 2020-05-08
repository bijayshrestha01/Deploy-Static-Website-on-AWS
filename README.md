# Deploy-Static-Website-on-AWS
Deploy a static website on AWS utilizing S3 bucket, IAM policies, and CloudFront.

In this project, you will deploy a static website to AWS. First, you will create a S3 bucket and upload the website files to your bucket. Next, you will configure the bucket for website hosting and secure it using IAM policies. Next, you will speed up content delivery using AWS’ content distribution network service, CloudFront. Lastly, you will access your website in a browser using the unique CloudFront endpoint.

The folder contains the screenshots of the steps for deploying the static website on AWS.

1. Create a S3 bucket
2. Configure the S3 bucket
3. Upload all the files to the S3 bucket created
4. Update the S3 bucket policy
5. Deploy the website under 'Properties' tab with 'Static website hosting'
6. Test your webstite url

The website is distributed via CloudFront. A CloudFront distribution should be created using the 'Web' delivery method.
