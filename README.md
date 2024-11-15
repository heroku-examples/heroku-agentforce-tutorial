Creating Agentforce Custom Actions with Heroku
==============================================

This tutorial will guide you through how to configure an Agentforce Action deployed to Heroku within your Salesforce org. This allows Agentforce agents to access powerful custom coded actions written in Python and other languages that take advantage Heroku's fully managed and elastic compute service. 

<img src="images/main.png" width="80%" alt="Image description">

Want to learn more before diving in?
------------------------------------

The examples in this tutorial are intentially basic to allow you a clean starting point to develop your own actions. We have also provided fully built actions that we recommend you review first. When you are ready continue below to started building your own Agentforce Action with Heroku.

| Example | Demo Video |  | Related Content
| ------- | ---------- | ---------- | ---------------
| The **Archive Agent** action demonstrates using Heroku to access and perform complex comput over unstructed archived data using the [Einstein AI LLM Gateway](https://developer.salesforce.com/blogs/2023/08/building-ai-powered-apps-with-llms-and-einstein) to interpret naturla language requests to perform dynamic calculations. | [Link](https://youtu.be/mNgrdf1GX-w)| <img src="images/archiveagent2.png" width="50%" alt="Image description"> | [Blog](https://blog.heroku.com/building-supercharged-agents-heroku-agentforce) [Code](https://github.com/heroku-examples/agentforce-collage-agent)
| With the **Coral Cloud Collage Agent** we explore how the Coral Cloud Resort invites its guests to browse and book unique experiences throughout their stay using Agentforce. With Heroku, we extend the agents functionality to generate a personalized collage of each guest's adventures, showcasing how custom code deployed on Heroku can create dynamic digital media delivered directly within the Agentforce experience. | [Link](https://www.youtube.com/watch?v=yd97A9GLFUA&t=3s)| ![image](images/collage2.jpg) ![image](images/collage.png) | [Code](https://github.com/heroku-examples/agentforce-collage-agent)


Step 1 - Action API URL
-----------------------

This tutorial provides examples in Java and Python on how to code a basic Agentforce action. You can deploy these to your own Heroku account or proceed for now with the predeployed versions we have created for you.

| Language | Predeployed API URL | Predployed API Test Page | Or.. Deploy your Own to Heroku
| -------- | --------------- | ------------------- | -----------
| Python | [Action API URL](x) | [Action API Test Page](x) | Go to this [GitHub Repository](https://github.com/heroku-examples/heroku-agentforce-tutorial-python)
| Java | [Action API URL](https://agentforce-tutorial-java-fd05948b2c0a.herokuapp.com) | [Action API Test Page](https://agentforce-tutorial-java-fd05948b2c0a.herokuapp.com/swagger-ui/index.html) | Go to this [GitHub Repository](https://github.com/heroku-examples/heroku-agentforce-tutorial-java)

With the above information you have two paths to take:
- **If you are using the predeployed versions**, right click the ***Action API URL*** link from above and copy the URL to your clipboard when requested below. Optionally, click the ***Action API Test URL*** to try the API out from your browser, this will be the Action API Agentforce will eventually callout to when invoking your action.
- **If you want to deploy your own action before proceeding**, follow the instructions in the respective repository above and return here with the deployed URL.

Step 2 - Creating a Named Credential
------------------------------------

Bla bla bla

Step 3 - Registering the Action API
-----------------------------------

Bla bla bla

Step 4 - Assigning Permissions
------------------------------

Bla bla bla

Step 5 - Creating an Agentforce Action
--------------------------------------

Bla bla bla

Step 6 - Using Agent Builder
----------------------------

Bla bla bla