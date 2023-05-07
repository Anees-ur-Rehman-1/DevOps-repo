# What is DevOps?
The word DevOps is a combination of two words Development and Operations. Before getting into what DevOps is, let us get an idea about the two teams involved in software development. The development team is responsible for developing, designing, and building the application. The operation team deals with the deployment and testing of the application. If there are problems with the application, the operation team also provides feedback to the development team. Now let us get to the history of DevOps.

# History of Devops
Let us see some important events of DevOps :

**2007-2008:** The DevOps idea was started

**2009:** In the initial stage the first conference was ” Deploys a day: Dev and Ops cooperation of flicker.”  Another conference called “DevOps Days in Ghent, Belgium” also happened.

**2010**:DevOps days conference happened in the United States at mount view, calif.

**2012:** Allana browns at puppet creates a state of DevOps report


**2014:** Publishing the annual “State of DevOps report”

**2017:** Forrester Research calls 2017 “The Year of DevOps”

**2018:** 30 DevOps day conferences were scheduled across the united states.

# Why did we need DevOps?
As we know about the problems faced in traditional models like in the waterfall model, there is a problem of a one-way stream of work, due to which if there is any mistake, the whole process repeats, and there is no interaction with customers. Now, this is solved in agile by splitting the whole development plan into several iterations for better production efficiency.  The agile model also includes customer interaction with the company to rectify mistakes. But there is another problem faced in Agile too.


Here, the problem arises when the development team continuously changes the code for better performance and sends the code to the operations team for testing. But there may be a delay in the operations team feedback in situations like if the developers sent code for review at night but due to the unavailability of the operations team, there will be a delay in the project feedback.

So, DevOps is the solution to this problem. DevOps is a practice or a methodology in which the development and operations teams work together by including automation at the initial stages. So they can work on rapidly changing systems, fix bugs, and help to deliver a good quality of software in time.

![DevOps model](https://user-images.githubusercontent.com/125833255/236693347-b96b87c4-9df6-44ce-8da6-4ee1ba7a768d.png)

# Waterfall Model 
Let’s consider traditionally developing software using a Waterfall Model in this Devops Tutorial.

![Waterfall-Model-Devops-Tutorial-Edureka](https://user-images.githubusercontent.com/125833255/236693399-4b42147d-4e2d-47e7-b780-47ce5a2867e5.png)

In the above diagram in this Devops Tutorial, you will see the phases it will involve:

**In phase 1** – Complete Requirement is gathered and SRS is developed

**In phase 2** – This System is Planned and Designed using the SRS

**In phase 3** – Implementation of the System takes place

**In phase 4** – System is tested and its quality is assured

**In phase 5** – System is deployed to the end users

**In phase 6** – Regular Maintenance of the system is done

# Waterfall Model Challenges
The Water-fall model worked fine and served well for many years however it had some challenges. In the following diagram the challenges of Waterfall Model are highlighted.

![WaterFall-Model-Challenges-DevOps-Tutorial-Edureka-4](https://user-images.githubusercontent.com/125833255/236693658-f7c7bc35-083f-4276-a369-225ff5d62374.png)


In the above diagram in this Devops Tutorial you can see that both Development and Operations had challenges in the Waterfall Model.  From Developers point of view there were majorly two challenges:

* After Development, the code deployment time was huge.

* Pressure of work on old, pending and new code was high because development and deployment time was high. On the other hand, Operations was also not completely satisfied.

**There were four major challenges they faced as per the above diagram in this Devops Tutorial:**

1. It was difficult to maintain ~100% uptime of the production environment.

2. Infrastructure Automation tools were not very affective.

3. Number of severs to be monitored keeps on increasing with time and hence the complexity.

4. It was very difficult to provide feedback and diagnose issue in the product.

# DevOps Architecture:
Let us now discuss different phases of DevOps architecture:

![Picture2](https://user-images.githubusercontent.com/125833255/236693702-546f2d00-c7e2-4be3-a448-f7f51450eeee.png)

* Plan – In DevOps planning plays an important role. In this stage, all the requirements of the project and everything regarding the project like time for each stage, cost. etc are discussed. This will help everyone in teams to get a brief idea about the project. 

* Code – In this Stage the code is written over here according to the client’s requirements. Here the code is divided into small codes called Units. This is done to get a clear picture of the code. For example, if the team is doing a project on an online -Ekart application then the login part is divided as one unit, after login the page which shows all the categories is divided as another unit, user profile as another unit, etc. 

Some of the examples of the tools used are Git, JIRA

* Build – In this stage Building of the units is done. Some of the examples of the tools used are maven, Gradle.

* Test – Testing of all units is done in this stage. So we will get to know where exactly the code is having bugs and if there are mistakes found it is returned. Some of the examples of the tools used are Selenium, PYtest

* Integrate – In this stage, all the units of the codes are integrated. That means in this step we will be creating a connection between the development team and the operation team to implement Continuous Integration and Continuous Deployment. An example of the tool used is Jenkins. 

* Deploy – In this stage, the code is deployed on the client’s environment. Some of the examples of the tools used are AWS, Docker.

* Operate – Operations are performed on the code if required. Some of the examples of the tools used are Kubernetes, open shift.

* Monitor – In this stage monitoring of the application is done over here in the client’s environment. Some of the examples of the tools used are Nagios, elastic stack.

How is DevOps different from traditional IT in this Devops Tutorial?
 Let us take a look at some key differences between traditional IT and DevOps in this Devops Tutorial.

Let us take a look at the workflow of traditional IT methods and DevOps to get a better understanding of the differences between them.

In traditional IT methods [specifically waterfall method] the developer writes the code in their coding environment. Once the development is complete they will inform the operations team to test the code. 


Now the operations team will be taking the code from the coding repository and will be passing through some test cases. If there are any bugs detected then it’s sent back again to the development team. This is continued till the bugs are resolved. So as we can see the main problem is, there is a lot of time is wasted because the testing is done only when the coding is completed. So if there is a small mistake by developers. For finding that small mistake the whole testing process is done again. So the solution for this problem is implementing testing at the early stages [development stage].

Now if we check about the workflow of DevOps. The main feature includes Continuous Integration and Continuous Deployment pipeline. By which the previous problem can be resolved. So now the development team need not wait for the results of their code. By including the automation feature at the initial stages [development stage] we can get the knowledge about bugs at initial stages and they can be solved quickly. So there will be a faster deployment and quick delivery of the software.


# How is DevOps different from Agile?

|DevOps|Agile|
|:-----|:----|
|DevOps deals with filling the time gap between the development team and the operations team.|Agile methodology deals with filling the gap between customers and the company.|
|Here the feedback will be coming from the Operations team to the development team.|Here the feedback will be coming from the customers to the company.|
|It focuses on constant testing and delivery.|	It focuses on constant changes.|
|Some of the tools used in DevOps: Puppet, AWS|Some of the tools used for Agile: JIRA, Bugzilla, Kanboard|


# Advantages and Disadvantages of DevOps:
## Advantages:
Faster development of software and quick deliveries.
DevOps is flexible and adaptable to changes easily.
Compared to the previous software development models confusion about the project is decreased due to which the product quality and efficiency are increased.
The gap between the development team and operation team was bridged. i.e, the communication between the teams has been increased.
Efficiency is increased by the addition of automation which includes continuous integration and continuous deployment.
Customer satisfaction is enhanced.
## Disadvantages:
DevOps is expensive.
Certain levels of skills are required for maintaining the DevOps architecture.
Adopting DevOps technology into the traditional style of industries is quite a challenge.

## Summary:
Now that we’ve covered all of the fundamentals of DevOps in this DevOps Tutorial article, you should understand why we chose DevOps over other software development methodologies [such as waterfall and agile]. Aside from that, we went through some of the most popular DevOps applications. I hope this has clarified some of the core DevOps concepts and given you a better understanding of why DevOps is needed.

