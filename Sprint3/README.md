Online Game players matching application
Live Walkthrough link:

https://kennesawedu-my.sharepoint.com/personal/vboddapa_students_kennesaw_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fvboddapa%5Fstudents%5Fkennesaw%5Fedu%2FDocuments%2FRecordings%2FCall%20with%20Sahith%20and%202%20others%2D20230425%5F183432%2DMeeting%20Recording%2Emp4&ga=1


--------------------------------------------------------------------------------------------------------------
Code URL

https://github.com/webserviceproject/WebserviceProjectTeam9
--------------------------------------------------------------------------------------------------------------
Project Documents

https://github.com/webserviceproject/Documents
--------------------------------------------------------------------------------------------------------------
Team Name: Team 9

Team Members:

Sahith Vardhan Reddy Vancha: Product Owner

Veeramma Boddapati: Scrum Master

Subramanya Rahul Annavajhula: Development Team

Sai Sushanth Reddy Jonnalagadda: Development Team

--------------------------------------------------------------------------------------------------------------

Sprint 2

Forecast and Rationale

The forecast for the third sprint includes:

-CI Integration: 8 points

-CD Integration: 10 points

-Fix bugs in sprint 2: 11 points

-Jest Unit Testing: 8 points

In software development, sprint planning involves estimating the amount of work that can be completed in a particular timeframe, usually ranging from one to four weeks. In this case, the forecast for the third sprint includes four main tasks with their corresponding estimated points.

The first task is CI (Continuous Integration) Integration, which is estimated at 8 points. Continuous Integration is a software development practice where code changes are frequently integrated into a central repository and then automatically tested and built. The integration process allows for early detection of errors and conflicts in the code, ensuring that the software product is stable and reliable.

The second task is CD (Continuous Deployment) Integration, estimated at 10 points. Continuous Deployment is the next step after Continuous Integration, where the software product is automatically deployed to the production environment after passing all the automated tests. This process ensures that the software is always up to date and that new features or bug fixes are immediately available to users.

The third task is fixing bugs in sprint 2, estimated at 11 points. Bugs are a common occurrence in software development, and it is important to address them promptly to maintain the quality of the product. Fixing bugs in the previous sprint ensures that the software product is stable and reliable, and it also helps to build trust with the users.

The fourth task is Jest Unit Testing, estimated at 8 points. Unit testing is a software testing technique where individual components or modules of the software are tested in isolation from the rest of the system. Jest is a popular JavaScript testing framework that is widely used for unit testing. Writing unit tests helps to identify issues early in the development process and ensures that the software behaves as expected.

In conclusion, the forecast for the third sprint includes four main tasks with a total of 37 estimated points. The tasks focus on improving the quality and reliability of the software product, ensuring that it is stable and ready for deployment.


--------------------------------------------------------------------------------------------------------------

Sprint Product Backlog Tasks Jira Board
https://webserviceproj123.atlassian.net/jira/core/projects/FIRST/board

--------------------------------------------------------------------------------------------------------------

Kanban Board in Jira

![MicrosoftTeams-image (2)](https://user-images.githubusercontent.com/71249872/234742111-237a4a10-a413-4484-92d5-0c7706feca05.png)



--------------------------------------------------------------------------------------------------------------

Burndown Chart:

![image](https://user-images.githubusercontent.com/71249872/229994984-0f431d46-8012-4435-bcce-7b09dc63a5f1.png)


--------------------------------------------------------------------------------------------------------------
Sprint Daily Scrum Call evidence:

https://kennesawedu-my.sharepoint.com/personal/vboddapa_students_kennesaw_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fvboddapa%5Fstudents%5Fkennesaw%5Fedu%2FDocuments%2FRecordings%2FCall%20with%20Sahith%20and%202%20others%2D20230425%5F184826%2DMeeting%20Recording%2Emp4&ga=1

--------------------------------------------------------------------------------------------------------------
Working on the Code evidence:

![MicrosoftTeams-image (3)](https://user-images.githubusercontent.com/71249872/234742152-c8ecdfd8-c65d-4138-b321-bf08b469debc.png)


--------------------------------------------------------------------------------------------------------------
A-TDD Test suite execution evidence:

![TDD_Test_suite](https://user-images.githubusercontent.com/71249872/230252819-44a0b337-9478-4a5b-b935-bdd30f8421a5.png)



--------------------------------------------------------------------------------------------------------------

Sprint Review Video

https://kennesawedu-my.sharepoint.com/personal/vboddapa_students_kennesaw_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fvboddapa%5Fstudents%5Fkennesaw%5Fedu%2FDocuments%2FRecordings%2FCall%20with%20Sahith%20and%202%20others%2D20230425%5F183432%2DMeeting%20Recording%2Emp4&ga=1


---------------------------------------------------------------------------------------------------------------

Continuous Integration and Continuous Deployment

![MicrosoftTeams-image (4)](https://user-images.githubusercontent.com/71249872/234742207-463a714a-eeeb-4566-a029-647a42319836.png)

CI-CD demo

https://kennesawedu-my.sharepoint.com/personal/vboddapa_students_kennesaw_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fvboddapa%5Fstudents%5Fkennesaw%5Fedu%2FDocuments%2FRecordings%2FCall%20with%20Sahith%20and%202%20others%2D20230425%5F181812%2DMeeting%20Recording%2Emp4&ga=1

Introduction:
Continuous Integration and Continuous Deployment (CI/CD) is an approach that allows developers to automate the software delivery process. This approach involves integrating the code changes frequently and testing the application to ensure that it's functioning correctly. Continuous Deployment is an extension of CI, which automates the deployment process of code changes to production environments.
Azure is a cloud computing service that offers various tools and services for building, testing, deploying, and managing applications. In this document, we'll cover the steps for implementing CI/CD with Azure.
Steps for Implementing CI/CD with Azure:
1. Create a new Azure DevOps project:
Azure DevOps is a platform that provides tools for planning, developing, testing, and deploying applications. To get started, create a new Azure DevOps project. Follow these steps:
• Go to the Azure DevOps portal.
• Click on "Create Project."
• Enter a name for your project and select the appropriate organization.
• Choose a version control system (Git, TFVC).
• Click on "Create."
2. Set up Continuous Integration:
Continuous Integration (CI) involves automating the process of building and testing code changes. In Azure DevOps, you can use Azure Pipelines for CI. Follow these steps:
• Go to your Azure DevOps project.
• Click on "Pipelines" and select "Create Pipeline."
• Select your code repository and choose the appropriate pipeline type.
• Select your build agent and click on "Continue."
• Configure the pipeline settings, such as trigger conditions, build stages, and tasks.
• Save the pipeline configuration.
3. Set up Continuous Deployment:
Continuous Deployment (CD) involves automating the process of deploying code changes to production environments. In Azure DevOps, you can use Azure Release Pipelines for CD. Follow these steps:
• Go to your Azure DevOps project.
• Click on "Releases" and select "Create Release Pipeline."
• Select your build pipeline as the artifact source.
• Configure the release pipeline settings, such as stages, deployment triggers, and tasks.
• Save the release pipeline configuration.
4. Configure Deployment Environments:
To deploy code changes to production environments, you need to configure the deployment environments. In Azure DevOps, you can use Azure Environments for this purpose. Follow these steps:
• Go to your Azure DevOps project.
• Click on "Environments" and select "New Environment."
• Enter a name for your environment and select the appropriate resource group.
• Choose the appropriate deployment target (Azure Kubernetes Service, Virtual Machines, etc.).
• Configure the environment settings, such as variables, security, and approvals.
• Save the environment configuration.
5. Test and Deploy:
After configuring the CI/CD pipeline and deployment environment, you can test and deploy your application. Follow these steps:
• Make changes to your code and push them to the code repository.
• The Azure Pipelines will automatically trigger the build process and create a new build artifact.
• The Azure Release Pipelines will automatically trigger the deployment process and deploy the code changes to the production environment.
• Monitor the deployment process and verify that the application is functioning correctly.





