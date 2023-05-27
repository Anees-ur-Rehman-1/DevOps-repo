# Continuous deployment (CD)
Continuous deployment is a software release process that uses automated testing to validate if changes to a codebase are correct and stable for immediate autonomous deployment to a production environment.

The software release cycle has evolved over time. The legacy process of moving code from one machine to another and checking if it works as expected used to be an error-prone and resource-heavy process. Now, tools can automate this entire deployment process, which allows engineering organizations to focus on core business needs instead of infrastructure overhead.

# Continuous deployment vs. continuous delivery
The distinction between continuous deployment vs. continuous delivery can be confusing because of the nomenclature. They are both abbreviated as CD and have very similar responsibilities. Delivery is the precursor to deployment. In delivery, there is a final manual approval step before the production release. 

The following is a mnemonic exercise to help remember the distinction between the two. Think about receiving a package from your favorite online retail store. When waiting for a package to arrive you coordinate with a delivery service. This is the delivery phase.  Once the package has successfully arrived, you open the package and review its contents to make sure it matches your expectations. If it does not, it may be rejected and returned. If the package is correct you are ready to “deploy” and use the new purchase!

In the delivery phase, developers will review and merge code changes that are then packaged into an artifact. This package is then moved to a production environment where it awaits approval to be opened for deployment.  In the deployment phase, the package is opened and reviewed with a system of automated checks. If the checks fail the package is rejected. 

When the checks pass the package is automatically deployed to production. Continuous deployment is the full end-to-end, automated software deployment pipeline. 




## What are the benefits of continuous deployment?
Continuous deployment offers incredible productivity benefits for software development teams. The combination of DevOps with continuous deployment allows teams to accelerate releases significantly. Since deployment pipelines are triggered automatically for every change, teams can develop faster. If the team has an idea for a new product or feature, it can be in the hands of customers as soon as the code has been pushed. Continuous deployment allows teams to deploy small batches of changes, which makes releases less risky and easier to fix if a problem occurs.

From a business perspective, continuous delivery allows a company to respond to changing market demands by rapidly deploying and validating new ideas and features. 

## Continuous deployment tools
Once you adopt automated testing it is a good idea to couple it with a test coverage tool that will give you an idea of how much of your codebase is covered by your test suite.

It is good to aim a coverage above 80% but be careful not to confuse high percentage of coverage with a good test suite. A code coverage tool will help you find untested code but it is the quality of your tests that will make the difference at the end of the day.

If you’re just getting started don’t rush in attaining 100% coverage of your codebase, but rather than that use a test coverage tool to find out critical parts of your application, that do not yet have tests and start there.

## Automated testing
The most critical dependency for continuous deployment is automated testing. In fact, the entire chain of continuous integration, delivery, and deployment depends on it. Automated tests are used to prevent any regressions when new code is introduced and can replace manual tests of new code changes.

## Rolling deployments
The distinguishing feature between continuous deployment and delivery is the automated step of activating new code within a live environment. A continuous deployment pipeline must be able to undo a deployment in the event that bugs or breaking changes are deployed. Automated rolling deployment tools like green-blue deploys are a requirement for proper continuous deployment.

## Monitoring and alerts
A robust continuous deployment pipeline will have real-time monitoring and alerts. These tools provide visibility into the health of the overall system and into the before and after state of new code deployments. Additionally, alerts can be used to trigger a rolling deployment ‘undo’ to revert a failed deployment.

## Continuous deployment best practices
Once a continuous deployment pipeline is established, ongoing maintenance and participation are required from the engineering team to ensure its success. The following best practices and behaviors will ensure an engineering team is getting the most value out of a continuous deployment pipeline.

## Test-driven development
Test-driven development is the practice of defining a behavior specification for new software features before development begins. Once the spec is defined developers will then write automated tests that match the spec. Finally, the actual deliverable code is written to satisfy the test cases and match the spec. This process ensures that all new code is covered with automated testing upfront. The alternative to this is delivering the code first and then producing test coverage after. This leaves an opportunity for gaps between the expected spec behavior and the produced code.

## A single method of deployment
Once a continuous deployment pipeline is in place, it’s critical that it is the only method of deployment. Developers should not be manually copying code to production or live editing things. Manual changes external to the CD pipeline will de-sync the deployment history, breaking the CD flow.

## Containerization
Containerizing a software application ensures that it behaves the same across any machine it is deployed on. This eliminates a whole class of issues where software works on one machine but behaves differently on another. Containers can be integrated as part of the CD pipeline so that the code behaves the same on a developer’s machine as it does during automated testing and production deployment.



