### single-channel-queue
##assignment

This is an implementation of Single Channel Queue Simulation Using python Language.


This can be used for different purposes where we can see a single channel queue property..

###Assumptions

Only one checkout counter.
Customers arrive at this checkout counter at random from 1 to 8 minutes apart. Each possible value of interarrival time has the Poisson distribution probability of occurrence
Service times are also considered to be exponentially distribution.
Now, simulate this bank problem having µ=5.6 customers/minute (arrival rate) and λ=2 customers/minute (service
rate) for 20 customers.
The problem is to analyze the system by simulating the arrival and service of 20 customers.
The average
number of customer waiting, the average waiting time of a customer should be your statistical estimators for
examining the true characteristics of the system.

###Tables
Here we can find the interarrival time using this poisson distributation parameter mu for 20 customer but the initial arrival time=0,thats why we import size=19

![image](https://user-images.githubusercontent.com/43786706/112715783-95c49500-8f0c-11eb-8836-41fb56bfbd9d.png)



###and we can also  find service time using exponential distributation parameter lamda=2
![image](https://user-images.githubusercontent.com/43786706/112715794-a70da180-8f0c-11eb-9360-49a72a782d8f.png)

###then we create dataform like that,


![image](https://user-images.githubusercontent.com/43786706/112715693-0dde8b00-8f0c-11eb-94cd-89441222a960.png)
###here we put the value of interarrival time,arrival time,service time.
interarrival time= poission distribuation value,
arrival time=interarrival time+previous arrival time,
service time=exponential distribuation value.

##then we calculate the time service begain and put them in table
![image](https://user-images.githubusercontent.com/43786706/112715876-2ef3ab80-8f0d-11eb-9a67-0e4d2a862bc4.png)

###then we use formula for calculate  "waiting_time_in_queue","Time service end","Time customer spend in system "is
![image](https://user-images.githubusercontent.com/43786706/112715903-63fffe00-8f0d-11eb-8e50-0dbe9d0cc692.png)
![image](https://user-images.githubusercontent.com/43786706/112715926-8c87f800-8f0d-11eb-89ff-31998a029929.png)
![image](https://user-images.githubusercontent.com/43786706/112715949-b50ff200-8f0d-11eb-8f0c-64e71225031a.png)

we know the formula for ideal time of server =  arrival time of customer> previous customer service end time  then print(arrival time) else:  (previous customer end time).
we try ,but we dont implement this formula
at last we import tabulate function to make our table looking good and the table is:
![image](https://user-images.githubusercontent.com/43786706/112716120-9c540c00-8f0e-11eb-94a9-5e32f558bec4.png)
![image](https://user-images.githubusercontent.com/43786706/112716128-aa099180-8f0e-11eb-9573-778deb4faf34.png)
That's all.


