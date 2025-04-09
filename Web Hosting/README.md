# AWS

### Topic : EC2 Web Hosting

#### How to host a website in EC2 Instance.

#### 1-Launch an Instance
#### 2-Connect to the instance
#### 3-Login as root user
#### 4-Install the packages that supports a web hosting model inside EC2 instance
#### 5-Update the packages - yum update -y
#### 6-Install Packages - yum install httpd -y
#### 7-Check the status - systemctl status httpd
#### 8-If inactive ,make it active -systemctl start httpd
#### 9-Create a folder and get into it
#### 10-Download file - wget <URL>
#### 11-Get in to html file and move the contents to /var/www/html - mv * /var/www/html
#### 12- cd /var/www/html
#### 13-copy the public ip and run on browser