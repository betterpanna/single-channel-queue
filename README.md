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

#For interarrival time
from scipy.stats import *
data_poisson = poisson.rvs(mu=5.6, size=19)


and we can also  find service time using exponential distributation parameter lamda=2

##For service time
from scipy.stats import *
data_expon = expon.rvs(scale=0.5,loc=5,size=20)
print(data_expon)
then we create dataform like that,
	customer no	Interarrivaltime	arrivalTime	service time
0	1	0	0	5.094073
1	2	8	8	5.324692
2	3	4	12	5.657992
3	4	4	16	6.491501
4	5	3	19	5.138822
5	6	6	25	5.392440
6	7	5	30	5.319280
7	8	6	36	5.035201
8	9	3	39	6.061196
9	10	4	43	5.334694
10	11	3	46	5.050287
11	12	8	54	5.094212
12	13	5	59	5.104664
13	14	4	63	5.788552
14	15	8	71	5.842034
15	16	5	76	6.659961
16	17	6	82	6.102871
17	18	4	86	5.982190
18	19	3	89	5.058545
19	20	6	95	5.342689

