# single-channel-queue
assignment
**Note:This is an implementation of Single Channel Queue Simulation Using python Language.
single channel queue simulation has very important for bank service/ticket counter etc process.
This can be used for different purposes where we can see a single channel queue property.

**Update 03/20/2021:**We created a new Poisson distribution  & exponentially distribution value for calculate interarrival times & Service times.\
**Update 03/21/2021:**we put the value of interarrival time,arrival time,service time.\
**Update 03/24/2021:**we  calculate the time service begain and put them in table.\
**Update 03/25/2021:** we  calculate the waiting time of queue & also calculate time customer spend in system.\
**Update 03/26/2021:** we design the table to using the tabulate function.\
we know the formula for ideal time of server =  arrival time of customer> previous customer service end time  then print(arrival time) else:  (previous customer end time).
we try ,but we dont implement this formula.



#Assumptions

Only one checkout counter.
Customers arrive at this checkout counter at random from 1 to 8 minutes apart. Each possible value of interarrival time has the Poisson distribution probability of occurrence
Service times are also considered to be exponentially distribution.
Now, simulate this bank problem having µ=5.6 customers/minute (arrival rate) and λ=2 customers/minute (service
rate) for 20 customers.
The problem is to analyze the system by simulating the arrival and service of 20 customers.
The average
number of customer waiting, the average waiting time of a customer should be your statistical estimators for
examining the true characteristics of the system.

###then we create dataform like that,to see that please  click [here] 
(https://user-images.githubusercontent.com/43786706/112715693-0dde8b00-8f0c-11eb-94cd-89441222a960.png)


For a detailed description of the methodology behind single channel queue and the associated dataset please click [here]
(https://user-images.githubusercontent.com/43786706/112716217-3c119a00-8f0f-11eb-9820-9e6866093fa9.png)
If you are a researcher or devloper and you would like access to the **single channel queue** on your data or existing data, please reach out to panna.ganguly.27@gmail.com or 
Isratjahanelva01@gmail.com.Lets all work together to get a better soluation of this problem.
Our respective teacher Muhtadir Shihab is to encourage our and contribution to this project.If you would like to discuss alternative licensing models, please reach out to us at panna.ganguly.27@gmail.com and sohagchakmamonipciu@gmail.com or Tanzimnur5@gmail.com 

If there are any technical questions after the README, FAQ, and past/current issues have been read, please  contact:
* panna.ganguly.27@gmail.com
* Farjanajesin9@gmail.com
* Tanzimnur5@gmail.com
* Isratjahanelva01@gmail.com
* sohagchakmamonipciu@gmail.com
## Table of Contents
1. [Requirements](#requirements) to install on your system
2. How to [generate single channel queue dataset]
3. Steps for [calculating,& evaluation ] of single channel queue coloumns "Interarrival time","arrival time""time service end"
4. Steps for [waiting time of queue]of single channel queue problem
5. Steps for [time customer spend in system]of single channel queue problem
6. st
7. [Results](#results)


we know the formula for ideal time of server =  arrival time of customer> previous customer service end time  then print(arrival time) else:  (previous customer end time).
we try ,but we dont implement this formula


## Requirements

The main requirements are listed below:

* Python 3.6
* Numpy
* Scikit-Learn
* Matplotlib
Additional requirements to generate dataset:
* PyDicom
* Pandas
* Jupyter
## Results
These are the final results for the COVIDNet models.
at last we import tabulate function to make our table looking good and the table is:
![image](https://user-images.githubusercontent.com/43786706/112716120-9c540c00-8f0e-11eb-94a9-5e32f558bec4.png)
![image](https://user-images.githubusercontent.com/43786706/112716128-aa099180-8f0e-11eb-9573-778deb4faf34.png)
That's all.
