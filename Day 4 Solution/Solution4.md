Task 1

Lauch 3 instances with the following tags respectively
Name: nginx, boot-order: 1
Name: myapp, boot-order: 2
Name: mydb, boot-order: 3

Task 2
write a script that would start/stop these instances in the order you specified, i.e.
instance with boot-order: 3 tag should boot/start first and likewise rest of them
instance with boot-order: 1 tag should stop first and likewise rest of them

Task 3
Launch an ec2 instance with user-data having ansible role to host a website - [like previous assignment]
Figure out a way to launch this instance in your friend's AWS account

## Solution 

# Task 1

![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%204/1.png)

# Task 2

![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%204/2.png)

![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%204/3.png)
