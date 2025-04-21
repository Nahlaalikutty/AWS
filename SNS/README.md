# AWS

### Topic : SNS

#### SNS notification when uploads an object in a bucket

#### 1-Create an s3 bucket
![sns-1.png](sns-1.png)
#### 2-Create a SNS topic(channel) and update the access policy(to provide permission to receive notification)
![sns-2.png](sns-2.png)
#### 3-Create an event notification with the following configuration shown in image
![sns-3.png](sns-3.png)
![sns-4.png](sns-4.png)
#### 4-Since the subscriber need to subscribe create a subscription and confirm it
![sns-5.png](sns-5.png)
![sns-6.png](sns-6.png)
#### 5-Once the subscription is confirmed upload an object in the bucket.
![sns-7.png](sns-7.png)
#### 6-An email notification triggered with all the details
![sns-8.png](sns-8.png)