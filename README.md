# single-channel-queue
assignment
**Note:This is an implementation of Single Channel Queue Simulation Using python Language.
single channel queue simulation has very important for bank service/ticket counter etc process.
This can be used for different purposes where we can see a single channel queue property.**
**Update 03/20/2021:*We used a new Poisson distribution  & exponentially distribution value for calculate interarrival times & Service times.\
**Update 03/21/2021:**


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
![image](https://user-images.githubusercontent.com/43786706/112716217-3c119a00-8f0f-11eb-9820-9e6866093fa9.png)

If there are any technical questions after the README, FAQ, and past/current issues have been read, please  contact:
* panna.ganguly.27@gmail.com
* Farjanajesin9@gmail.com
* Tanzimnur5@gmail.com
* Isratjahanelva01@gmail.com
* sohagchakmamonipciu@gmail.com


###then we use formula for calculate  "waiting_time_in_queue","Time service end","Time customer spend in system "is
![image](https://user-images.githubusercontent.com/43786706/112716225-4af84c80-8f0f-11eb-9444-0cb2125952e3.png)

![image](https://user-images.githubusercontent.com/43786706/112716234-55b2e180-8f0f-11eb-8f34-cdaa7ff644e0.png)

![image](https://user-images.githubusercontent.com/43786706/112716245-5fd4e000-8f0f-11eb-8a37-950aa7e8adc0.png)



we know the formula for ideal time of server =  arrival time of customer> previous customer service end time  then print(arrival time) else:  (previous customer end time).
we try ,but we dont implement this formula
at last we import tabulate function to make our table looking good and the table is:
![image](https://user-images.githubusercontent.com/43786706/112716120-9c540c00-8f0e-11eb-94a9-5e32f558bec4.png)
![image](https://user-images.githubusercontent.com/43786706/112716128-aa099180-8f0e-11eb-9573-778deb4faf34.png)
That's all.


