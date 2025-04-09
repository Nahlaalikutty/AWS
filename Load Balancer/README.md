# AWS

### Topic : Load Balancer

#### 1-Launch 2 Instance in different Availability zones
![instances.png](instances.png)
#### 2-Host website on each instances
![server1.png](server1.png)

![server2.png](server2.png)
#### 3-Create Load Balancer with same vpc ,define the AZ and security group of instances
#### 4-Listener -HTTP Port 80
![targetgroup.png](targetgroup.png)
#### 5-Create Target group and attach 2 instances
#### 6-Now attach Target group with load balancer
![loadbalancer.png](loadbalancer.png)
#### 7-Once the status of load balancer is active,copy the DNS and run it
![final.png](final.png)