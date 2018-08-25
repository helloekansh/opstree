Task 1
Create a vpc not by wizard this time but manually, having 2 public subnets and 2 private subnets and 2 protected subnets.

setup should be highly available

Create 1 IGW and 2 NGW in each availability zone and make the appropriate routes in route tables

Main route will remain intact, instead make 4 route tables

public_route_table
private_route_table_1
private_route_table_2
protected_route_table

Task 2
Make LAMP setup with 2 instances in each private subnets.
Server-1 should serve a webpage that would say "Hi! i am server 1"
Server-2 should serve a webpage that would say "Hi! i am server 2"

Task 3
Launch a public load balancer that would forward the requests to these 2 LAMP instances

create the same setup using aws-cli except vpc

Solutions:

# Task 1

Step1)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/1.png)

Step2)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/2.png

Step3)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/3.png

Step4)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/4.png

Step5)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/5.png

Step6)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/6.png

Step7)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/7.png

Step8)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/8.png

Step9)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/9.png

Step10)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/10.png

# Task 2

Step11)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/11.png

Step12)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/12.png

Step13)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/13.png

Step14)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/14.png

# Task 3

Step15)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/15.png

Step16)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/16.png

Step17)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/17.png

Step18)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/18.png

Step19)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/19.png

Step20)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/20.png

Step21)
![alt text](https://github.com/helloekansh/opstree/blob/master/Media/Day%202/21.png
