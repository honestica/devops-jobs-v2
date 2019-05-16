# The backstory

One of the developers on the team went through a rails tutorial on friday night and loved it. He/She decided to implement a new tool in it. By monday morning 10am, he/she had a rails-based webapp that solves a crucial need for the support team, that had been raised the previous week. The manager of the support team saw the app and went running to the company CTO who pulled you (the devops in charge!) in with this inquiry : "Can you deploy this app by the end of the day?".

Here is our plan:
- The app the developer provided is : https://github.com/honestica/docker-compose-rails-dev-example 
- The developer provided a dockerfile 

# Level 1 

- Create a new helm chart to deploy the application. (no need for external DB, use sqlite)
- Deploy the chart to the local Kubernetes cluster.
- We should be able to access the application through an url
