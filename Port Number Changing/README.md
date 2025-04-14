# AWS

### Topic : Port Number Changing

#### How to change default port ssh 22 to a custom port

#### 1-Launch an Instance
![img_1.png](img_1.png)
#### 2-Connect to the instance
#### 3-Login as root user
#### 4-Open the config file and change the ssh port number from 22 to 100
![img_2.png](img_2.png)
![img_3.png](img_3.png)
![img_4.png](img_4.png)
#### 5-Restart the service
![img_5.png](img_5.png)
#### 6-Login the instance through terminal.Shows connection refused.
![img_6.png](img_6.png)
#### 7-After that update the security group of the instance 
![img_8.png](img_8.png)
#### 8-Now connect to custom port 100 instead of the default SSH port (22).Shows connection established
![img_7.png](img_7.png)
