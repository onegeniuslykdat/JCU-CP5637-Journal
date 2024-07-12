# Week 6
Monday, 08-Jul-2024 to Saturday, 13-Jul-2024


******************************************************************************************************************************************
***Task: Complete setting up all of the teamwork tools, make at least one GitHub commit (see a message in your integrated/linked Slack group), and complete your group agreement in your project board.
***Submit:
***Each student provide links to your teamwork tools: Slack channel (and Discord if you're using it), GitHub repo and either Trello board or GitHub project - containing something you have contributed to the planning for your project or initial group setup.
***A link to your LinkedIn profile (showing connections with teammates)
***A link to your learning journal entry (Learning on Project Management)
***Slack: https://app.slack.com/client/T1HPNSNKT/C078QLM30R4
***LinkedIn: https://au.linkedin.com/in/anthony-u-onyekwere-123b18128
******************************************************************************************************************************************

# Learning Activities & Resources***
This week I learnt about the deployments and development environments. We looked at the standard development environments, consisting of local, staging and production.
* Local environment - using stacks and tools like .Net, iisExpress, XAMP, LAMP, mySQL, SQL-Server, Apache, NG-Inx, etc to develop on your machine. It is often not available online. In the case when a staging environment is not used, a virtual machine which imitates the production environment can be used on the local computer.
* Staging environment - an optional copy of the production environment and available online for ver few. It is typically used to get feedback from a client.
* Production environment - the live environment which end users interact with. Production environments are typically created in Linux servers.

We also looked at deployment workflows. These are systematic and automated processes for moving files and configurations (such as database) from local development environment to staging or production development environments. Good workflows must include version control systems. We also learnt about the linux/unix shell for writing scripts and managing file permissions used in deployment workflows. We were introduced to:
* AWs on Vagrant ([AWS WordPress](https://github.com/lindsaymarkward/awswordpress))
* WordMove ([Wordmove:- Welaika](https://github.com/welaika/wordmove))

# Estimated Hours***
I spent a total of about 6 hours of my own time this week on this subject. On Friday, the next day after class, I spent an hour working on setting up my journal. I spent an additional hour on Saturday, the next day, setting up github/project/trello/etc***. The following week, on Monday and Wednesday, I spent 2 hours each day, working on:
* ***
* ***

# Content Insights***
This week's content introduced the standard development environments used in the industry. These are the local environment, staging and production environments. I also learnt about differnet workflows for WordPress, namely:
* AWS on Vagrant
* Wordmove
* WordPress on Azure app Service, which I discovered.

In order to setup workflows with version control, I created a GitHub repository and using the All-In-One WP Migration plugin, I exported my WordPress website into the GitHub repository. Then I created the deployment workflow into my Azure App Service.

# Career/Employability/Learning Insights***
I looked at various options for having development environments, such as AWS, Wordmove and Azure. I found the Azure platform very easy to use and there were free services available for students. In Azure, I looked at using [Windows Virtual Machines (VM)s](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal?WT.mc_id=UI_empg) as well as [Linux VMs](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal?WT.mc_id=UI_empg&tabs=ubuntu) as an environment. I also looked at using [Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/overview?WT.mc_id=APC-AppServices) and I learnt about [WordPress hosting on Azure](https://learn.microsoft.com/en-us/azure/app-service/migrate-wordpress?source=recommendations), using the All-in-One WP Migration plugin on WordPress. I was able to setup my own AppServcie using the WordPress hosting on Azure option.

Below is my configuration dashboard:
![WordPress on Azure App service](images/wordpress_on_azure.png)


I particulary liked the WordPress hosting on Azure, as this exposed me to the linux SSH and I learnt some new commands. It also integrates easily with GitHub in using deployment center, which is essential for workflows. I decided to setup my environment as follows:
* Local - WordPress dashboard
* Production - WordPress on Azure App service

Learning about Wordpress deployment workflows is very helpful. I used the following workflow:
* From WordPress to GitHub: ([Wordpress GitHubRepo](https://github.com/onegeniuslykdat/cp5637wordpresstest))
![WordPress All-In-One plugin](images/all_in_one_WP_migration.png)
  
* From GitHub to Azure
![GitHub repository linked to Azure](images/gitHub_on_Azure.png)
![GitHub repository to Azure workflow](images/gitHub_action_workflow_file.png)


Although I have some experience with development, I found setting up these environments very fun. I also enjoyed creating the deployment workflows on Azure and connecting to GitHub for version control. I intend to explore this much more. Overall, I learnt new skills which were impactful for me, as I previously did not know CMS could be used in this manner.
