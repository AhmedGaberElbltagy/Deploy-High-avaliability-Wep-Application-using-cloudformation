# Project 2 - Deploy a High-Availability Web App using CloudFormation 


> In this project (Udagram App), I deployed web servers for a highly available web app using CloudFormation.
> I wrote the script that creates and deploys the infrastructure and application for an Udagram app from the ground up.
> The script begin deploying the networking components followed by servers, security roles and software.

## The files included are:
```sh
1- /project ScreenShots: Screenshot the result of deploy.
2- /UdgramApplication : Udagram App Code (Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function etc ...)
3- create.sh : Cloudformation create stack script. 
4- update.sh : Cloudformation update stack script.
5- infrastructure.yml : Udagram Project's CloudFormation script.
6- infrastructure.json : Udagram Project's CloudFormation script parameters.
```
## Instruction of deploy:
Just run;
```sh
> ./create.sh UdagramApp infrastructure_networkandserver.yml infrastructure_networkandserver.json
```
the link for UdgramApp :http://udaci-webap-f955yvvbcu27-1701822217.us-west-2.elb.amazonaws.com/