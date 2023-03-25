# XP ( Extreme Programming Framework )
## Definition
Extreme Programming (XP) is a software development methodology that emphasizes iterative and incremental development, frequent releases, customer involvement, and a focus on quality code. XP is one of the agile methodologies and is designed to help teams quickly respond to changing requirements.
XP is a set of engineering practices. Developers have to go beyond their capabilities while performing these practices. That’s where the “extreme” in the framework’s title comes from. To get a better understanding of these practices, we’ll start with describing XP’s lifecycle and the roles engaged in the process. 
## The process and roles of extreme programming
The XP framework normally involves 5 phases or stages of the development process that iterate continuously:
### Planning 
the first stage, is when the customer meets the development team and presents the requirements in the form of user stories to describe the desired result. The team then estimates the stories and creates a release plan broken down into iterations needed to cover the required functionality part after part. If one or more of the stories can’t be estimated, so-called spikes can be introduced which means that further research is needed
### Designing 
is actually a part of the planning process, but can be set apart to emphasize its importance. It’s related to one of the main XP values that we’ll discuss below — simplicity. A good design brings logic and structure to the system and allows to avoid unnecessary complexities and redundancies.
### Coding 
is the phase during which the actual code is created by implementing specific XP practices such as coding standards, pair programming, continuous integration, and collective code ownership (the entire list is described below).
### Testing 
is the core of extreme programming. It is the regular activity that involves both unit tests (automated testing to determine if the developed feature works properly) and acceptance tests (customer testing to verify that the overall system is created according to the initial requirements).
### Listening 
is all about constant communication and feedback. The customers and project managers are involved to describe the business logic and value that is expected.

![XP](https://user-images.githubusercontent.com/125833255/227708798-20d12631-faa2-4a30-a62e-fc50b5f59b05.png)

Such a development process entails the cooperation between several participants, each having his or her own tasks and responsibilities. Extreme programming puts people in the center of the system, emphasizing the value and importance of such social skills as communication, cooperation, responsiveness, and feedback. So, these roles are commonly associated with XP:
### Customers 
are expected to be heavily engaged in the development process by creating user stories, providing continuous feedback, and making all the necessary business decisions related to the project.
### Programmers or developers
are the team members that actually create the product. They are responsible for implementing user stories and conducting user tests (sometimes a separate Tester role is set apart). Since XP is usually associated with cross-functional teams, the skill set of such members can be different.
### Trackers or managers
link customers and developers. It’s not a required role and can be performed by one of the developers. These people organize the meetups, regulate discussions, and keep track of important progress KPIs.
### Coaches
can be included in the teams as mentors to help with understanding the XP practices. It’s usually an outside assistant or external consultant who is not involved in the development process, but has used XP before and so can help avoid mistakes.
## Values and principles of extreme programming
In the late 90s, Ken Beck summarized a set of certain values and principles that describe extreme programming and lead to more effective cooperation within the team and, ultimately, higher product quality.
![XP values](https://user-images.githubusercontent.com/125833255/227708913-05855561-a4e9-43d1-b8dc-24efb14c66fd.png)

## Values of extreme programming
XP has simple rules that are based on 5 values to guide the teamwork:
### Communication 
Everyone on a team works jointly at every stage of the project.
### Simplicity 
Developers strive to write simple code bringing more value to a product, as it saves time and effort.
### Feedbacik 
Team members deliver software frequently, get feedback about it, and improve a product according to the new requirements.
### Respect 
Every person assigned to a project contributes to a common goal.
### Courage 
Programmers objectively evaluate their own results without making excuses and are always ready to respond to changes.
These values represent a specific mindset of motivated team players who do their best on the way to achieving a common goal. XP principles derive from these values and reflect them in more concrete ways.
## Principles of extreme programming
Most researchers denote 5 XP principles as:
### Rapid feedback
Team members understand the given feedback and react to it right away.
### Assumed simplicity
Developers need to focus on the job that is important at the moment and follow YAGNI (You Ain’t Gonna Need It) and DRY (Don’t Repeat Yourself) principles.
### Incremental changes
Small changes made to a product step by step work better than big ones made at once.
### Embracing change
If a client thinks a product needs to be changed, programmers should support this decision and plan how to implement new requirements.
### Quality work
A team that works well, makes a valuable product and feels proud of it.
Having discussed the main values and principles of XP, let’s take a closer look at the practices inherent in this framework.
## Extreme programming practices
The practices of XP are a set of specific rules and methods that distinguishes it from other methodologies. When used in conjunction, they reinforce each other, help mitigate the risks of the development process, and lead to the expected high-quality result. XP suggests using 12 practices while developing software which can be clustered into four groups.

![practices](https://user-images.githubusercontent.com/125833255/227709187-419a243a-3887-4498-86c6-ff03d0456a41.png)

## Test-Driven Development
Is it possible to write a clear code quickly? The answer is yes, according to XP practitioners. The quality of software derives from short development cycles that, in turn, allow for receiving frequent feedback. And valuable feedback comes from good testing. XP teams practice test-driven development technique (TDD) that entails writing an automated unit test before the code itself. According to this approach, every piece of code must pass the test to be released. So, software engineers thereby focus on writing code that can accomplish the needed function. That’s the way TDD allows programmers to use immediate feedback to produce reliable software. You can learn more about improving software testing in our dedicated article.
### The Planning Game
This is a meeting that occurs at the beginning of an iteration cycle. The development team and the customer get together to discuss and approve a product’s features. At the end of the planning game, developers plan for the upcoming iteration and release, assigning tasks for each of them.
### On-site Customer
As we already mentioned, according to XP, the end customer should fully participate in development. The customer should be present all the time to answer team questions, set priorities, and resolve disputes if necessary.
### Pair Programming
This practice requires two programmers to work jointly on the same code. While the first developer focuses on writing, the other one reviews code, suggests improvements, and fixes mistakes along the way. Such teamwork results in high-quality software and faster knowledge sharing but takes about 15 percent more time. In this regard, it’s more reasonable trying pair programming for long-term projects.
### Code Refactoring
To deliver business value with well-designed software in every short iteration, XP teams also use refactoring. The goal of this technique is to continuously improve code. Refactoring is about removing redundancy, eliminating unnecessary functions, increasing code coherency, and at the same time decoupling elements. Keep your code clean and simple, so you can easily understand and modify it when required would be the advice of any XP team member.


