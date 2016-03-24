# aws_hm1
When do we use and what are pros and cons of: ec2, s3, Cloudfront, IAM and rds.

Amazon EC2

Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity in the Amazon Web Services (AWS) cloud. Using Amazon EC2 eliminates your need to invest in hardware up front, so you can develop and deploy applications faster. You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage. Amazon EC2 enables you to scale up or down to handle changes in requirements or spikes in popularity, reducing your need to forecast traffic. Last but not least, EC2 instance is an AWS resource which is reccomended to be launched into a VPC (Virtual Private Network). 

Amazon S3
Amazon S3 is used for Scalable storage in the AWS cloud. It is suggested for a wide range of scenarios, from backing up your data, to storing your images and videos (to be accessed directly or through a CDN), to hosting static websites.

CloudFront Distributions

Use Amazon CloudFront to create a content delivery network (CDN) that makes your website content available from data centers around the world, called edge locations.You store your content on an origin server, such as an Amazon S3 bucket or an HTTP server running on an EC2 instance.You create a CloudFront distribution, associate the distribution with the origin server, and then use a CloudFront URL to access your content:
http://distribution_id.cloudfront.net/file.ext
Alternatively, you can associate your own domain name with your CloudFront distribution. When a user accesses an object that's part of a CloudFront distribution, CloudFront checks whether the object is already in a cache that's near the user. If it is, CloudFront serves the content from the cache; otherwise, CloudFront copies the requested content from the origin server to the cache.

Use CloudFront edge locations to improve the speed of your website.This is especially important if your website displays large media files, such as high-resolution images, audio, or video.

Amazon RDS

Provides a fully-managed relational database that scales to large datasets. It is easy to scale the database storage and compute resources and provide read replicas.You have a choice of database engines: MySQL, PostgreSQL, Oracle, or Microsoft SQL Server. Most software designed for use with these databases should work unmodified with Amazon RDS. If you need a specific relational database that isn't supported by Amazon RDS, host the database on Amazon EC2 instead.

Identity and Access Management (IAM)

You can manage the security credentials that enable users to access your AWS account using AWS
Identity and Access Management (IAM).You can create fine-grained permissions to AWS resources
and apply them to users or groups of users.

