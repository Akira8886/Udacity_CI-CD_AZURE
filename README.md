# Overview

In this project, we will create a web application that will predict house prices in Boston.

Services used :
    - Github 
    - Azure Cloud CLI 
    - Azure App Services
    - Azure DevOps Pipelines 

To work on the project you will need:
- github account
- Azure account

## Project Plan
 Project Plan

* A link to a Trello board for the project: https://trello.com/b/MGha4u5Y/udacity
* A link to a spreadsheet that includes the project plan: https://github.com/silberek/Udacity_CI-CD_AZURE/blob/main/Q4%202022.xlsx

## Instructions
 
* Architectural Diagram (Shows how key parts of the system work)
![grafik](https://user-images.githubusercontent.com/71324665/170563612-3f62f291-983f-40bf-840f-eb4599ff68db.png)

1. Set Up Azure Cloud Shell

* create github repoo
* Launch Azure Cloud Shell and create ssh-keys
* add public key in github-> settings-> SSH and GPG keys
* clone repo in shell
![grafik](https://user-images.githubusercontent.com/71324665/170565562-08b36379-bed0-400f-bb18-7eccb5a20950.png)

* create and activate virtual enviroment 
* create Makefile 
* create requirements.txt
*  Install the Dependiencies
```
make all
```
![grafik](https://user-images.githubusercontent.com/71324665/170566653-971147d5-6733-45a8-b607-920bdba4a6a2.png)
![grafik](https://user-images.githubusercontent.com/71324665/170566755-ed995a49-aac2-4689-b868-e9e1ebff5abf.png)

2. Configure GitHub Actions

Passing GitHub Actions build (after bugfix)

![grafik](https://user-images.githubusercontent.com/71324665/170559953-d53ace49-bc9e-416a-8f58-9635b6d680a1.png)

3. CD on Azure

Create a Pipeline in Azure DevOps for your Flask App.

Pipaline shoud complete without errors:

![grafik](https://user-images.githubusercontent.com/71324665/170694605-fd32f56a-485a-4818-a873-5986cba8f3a3.png)

Edit make_predict_azure_app.sh and update your app name. 
Execute file to make prediction

![grafik](https://user-images.githubusercontent.com/71324665/170696579-ad6ae743-8ff1-417a-a657-9f7da7073730.png)

* Output of streamed log files from deployed application



## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>



