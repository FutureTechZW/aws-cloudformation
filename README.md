# warp-assessment
Front-end
template1-designer(2).png![image](https://user-images.githubusercontent.com/51120436/127410511-197cd156-3426-4d45-9c48-ee21ef229b66.png)


The front-end consists of  the following AWS Resources

S3 Bucket: to host the static website content
S3 Bucket policy: to restrict the access to the S3 bucket to CloudFront only
Certificate Manager: to request the SSL certificate
Route 53: to serve the content under a custom domain
CloudFront: to serve the static website from the S3 bucket

It also consist of and index.html file that is linked to the template.yml file.
The index.html file is a resume which runs on a domain michaelchiramba.cf in Route53 hosted zone.

The final outcome of the frontend can be found here http://michaelchiramba.cf.s3-website-us-east-1.amazonaws.com/



Back-end 
![image](https://user-images.githubusercontent.com/51120436/127409974-a8c491df-5fd9-434a-b69b-00e580c35852.png)

It consits of a vpc with 2 subnets one for ec2 instance and other for rds (mysql).
1. Internet Getway
2. RouteTable
3. Security Group
4. EC2 instance
5. RDS MySQL Database
6. VPC 
7. Security group
8. Internet Gateway
