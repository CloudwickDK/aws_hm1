# aws_hm1
When do we use and what are pros and cons of: ec2, s3, Cloudfront, IAM and rds.

Amazon EC2

Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) cloud. Using Amazon EC2 eliminates your need to invest in hardware up front, so you can develop and deploy applications faster. You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage. Amazon EC2 enables you to scale up or down to handle changes in requirements or spikes in popularity, reducing your need to forecast traffic. Last but not least, EC2 instance is an AWS resource which is reccomended to be launched into a VPC (Virtual Private Network). 

Amazon S3
Scalable storage in the AWS cloud.

CloudFront Distributions

Use Amazon CloudFront to create a content delivery network (CDN) that makes your website content available from data centers around the world, called edge locations.You store your content on an origin server, such as an Amazon S3 bucket or an HTTP server running on an EC2 instance.You create a CloudFront distribution, associate the distribution with the origin server, and then use a CloudFront URL to access your content:
http://distribution_id.cloudfront.net/file.ext
Alternatively, you can associate your own domain name with your CloudFront distribution. When a user accesses an object that's part of a CloudFront distribution, CloudFront checks whether the object is already in a cache that's near the user. If it is, CloudFront serves the content from the cache; otherwise, CloudFront copies the requested content from the origin server to the cache.
