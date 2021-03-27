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



and we can also  find service time using exponential distributation parameter lamda=2
![image](https://user-images.githubusercontent.com/43786706/112715794-a70da180-8f0c-11eb-9360-49a72a782d8f.png)

then we create dataform like that,


![image](https://user-images.githubusercontent.com/43786706/112715693-0dde8b00-8f0c-11eb-94cd-89441222a960.png)
here we put the value of interarrival time,arrival time,service time.
interarrival time= poission distribuation value,
arrival time=interarrival time+previous arrival time,
service time=exponential distribuation value.
