# Deploying a static website on AWS console


### This project successfully deployed a static website to AWS using S3, CloudFront, and IAM.
### The steps are as follow:

## - create a s3 bucket

 ![1  Successfully created a public S3 bucket](https://user-images.githubusercontent.com/60348108/173179927-01b5b72c-2ce5-4911-8875-23a4cac4bfef.png)
 
## - Upload files to the s3 bucket

  ![2  files successfully uploaded to the S3 bucket](https://user-images.githubusercontent.com/60348108/173179975-6f46fa88-8470-4698-a7ed-54cdd762ab28.png)
  
## - Configure the s3 bucket: congifure the bucket policy that makes the contents in the s3 buckets to be accessible to the public

  ![3  successfully configured the s3 bucket](https://user-images.githubusercontent.com/60348108/173180007-5cc7e4c0-6d84-4953-9f80-cd78912edf9a.png)
  
## - Host the website using CloudFront, and then configure it.
#### The AWS's content distribution network service: **CloudFront** also helps to speed up contents distribution.

  ![4  website available for hosting](https://user-images.githubusercontent.com/60348108/173180021-867ba7c0-fd69-452a-8197-735b77097772.png)
  
## - use the configured CloudFront to retrieve and distribute website files.

  ![5  Successfully used configured CloudFront to retrieve and distribute website files](https://user-images.githubusercontent.com/60348108/173180075-c263f014-773b-4696-8241-ca8144dfa389.png)

## - Voila! The website is Live
  
![6  Voila! the website is live!!](https://user-images.githubusercontent.com/60348108/173180091-3c440f12-6eff-4bcf-8463-62d2dd8a809f.png)


#### The S3 website-endpoint URL: http://my-592174434184-bucket.s3-website-us-east-1.amazonaws.com

#### The CloudFront domain name URL: https://d1t3kj31fc4i9r.cloudfront.net/




