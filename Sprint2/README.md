Online Game players matching application
Live Walkthrough link:

https://kennesawedu-my.sharepoint.com/personal/vboddapa_students_kennesaw_edu/_layouts/15/stream.aspx?id=%2Fpersonal%2Fvboddapa%5Fstudents%5Fkennesaw%5Fedu%2FDocuments%2FRecordings%2FCall%20with%20Sahith%20and%202%20others%2D20230315%5F222612%2DMeeting%20Recording%2Emp4&ga=1&OR=Teams-HL&CT=1678940127019&clickparams=eyJBcHBOYW1lIjoiVGVhbXMtRGVza3RvcCIsIkFwcFZlcnNpb24iOiIyNy8yMzAyMDUwMTQyMSIsIkhhc0ZlZGVyYXRlZFVzZXIiOmZhbHNlfQ%3D%3D

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

The forecast for the second sprint includes:

-Matchmaking process: 5 points

-Connect to external APIs: 5 points

-Create controller, service and repository layers: 5 points

-Connect backend and frontend: 3 points

-Create skeleton for backend: 3 points

-UI changes to search for best player: 5 points

-Compare player data with search details: 5 points

Based on the details provided, the sprint2 forecast for the project can be estimated. The matchmaking process and connecting to external APIs are crucial tasks, and they are assigned 5 points each. Creating the controller, service, and repository layers is also a significant task and requires careful attention. Therefore, it is assigned 5 points as well. Connecting the backend and frontend and creating a skeleton for the backend are assigned 3 points each as they are important but less complex tasks. Finally, UI changes to search for the best player and comparing player data with search details are essential functionalities, and they are assigned 5 points each. 

By prioritizing these tasks in this way, the team can work effectively towards delivering a functional and optimized system within the given sprint time.



--------------------------------------------------------------------------------------------------------------

Sprint Product Backlog Tasks Jira Board
https://webserviceproj123.atlassian.net/jira/core/projects/FIRST/board

--------------------------------------------------------------------------------------------------------------

Kanban Board in Jira

![image](https://user-images.githubusercontent.com/71249872/229991811-cdc17d7c-7240-45a5-bdec-918cd770e1e9.png)


--------------------------------------------------------------------------------------------------------------

Burndown Chart:

![image](https://user-images.githubusercontent.com/71249872/229994984-0f431d46-8012-4435-bcce-7b09dc63a5f1.png)


--------------------------------------------------------------------------------------------------------------
Sprint Daily Scrum Call evidence:

https://kennesawedu-my.sharepoint.com/:v:/g/personal/svancha_students_kennesaw_edu/EbMgm0pKbPRLgjims311xxUB9qaJHkXc31d1VTnUWUV4nQ?e=xG1hxZ

--------------------------------------------------------------------------------------------------------------
Working on the Code evidence:

https://kennesawedu-my.sharepoint.com/:v:/g/personal/svancha_students_kennesaw_edu/EUv0yBtr2dNGmIV3D8GBzrIB4_2DLXwC-dIFU7EujBOP5Q?e=76MgNC

--------------------------------------------------------------------------------------------------------------
A-TDD Test suite execution evidence:

![TDD_Test_suite](https://user-images.githubusercontent.com/71249872/230252819-44a0b337-9478-4a5b-b935-bdd30f8421a5.png)



--------------------------------------------------------------------------------------------------------------

Sprint Review Video

https://kennesawedu-my.sharepoint.com/:v:/r/personal/vboddapa_students_kennesaw_edu/Documents/Recordings/Call%20with%20Sahith%20and%202%20others-20230405_220813-Meeting%20Recording.mp4?csf=1&web=1&e=jiekGd


---------------------------------------------------------------------------------------------------------------

Continuous Integration and Continuous Deployment
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




