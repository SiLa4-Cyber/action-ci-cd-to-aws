# Flask deploy with GitHub Actions to AWS Elastic Beanstalk

In order to implement CI/CD in AWS:
We need to create an IAM role with Full S3 Access privileges and an ElasticBeanstalk Administrator. Also we need to create own policy which is in the folder policies in this repo.
You will need to change words written in caps

Further we need to create S3 Bucket and ElasticBeanstalk

The last steps are to change the variables in the main file
