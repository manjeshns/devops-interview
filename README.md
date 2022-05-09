## Case Study Results

Created Resource group, App service plan and App service through ARM templates. I have uploaded the ARM templates
 - Hosted the App service on App service plan which helps in scaling.
- Deployed the ARM template via pipeline

Pipeline structure:
![image](https://user-images.githubusercontent.com/35796218/167390838-17afffe4-79fe-4594-a7f6-37cd54eab925.png)

![image](https://user-images.githubusercontent.com/35796218/167390970-60bc3cc8-1b92-4d4b-a8eb-9e70b86a2491.png)

Resources deployed in Azure portal

![image](https://user-images.githubusercontent.com/35796218/167389745-434ee43d-4eff-42f0-8ab7-49b62817d71e.png)

![image](https://user-images.githubusercontent.com/35796218/167383277-683d12b0-af9b-42c2-bbe6-7cc351f83d7e.png)


### CI/CD pipeline for code deployment : 

#### CI pipeline structure

![image](https://user-images.githubusercontent.com/35796218/167387228-772d3f26-08ae-4fa2-a3b8-e86cc95e11b4.png)

Created account in AccuWeather and included api key as part of pipeline variables

![image](https://user-images.githubusercontent.com/35796218/167388614-6666a6f9-2fa3-4b4d-bf57-006e4fdbca0f.png)

![image](https://user-images.githubusercontent.com/35796218/167388835-24c4c83a-3a55-4078-a6e4-cbd30ed9f971.png)

#### CD pipeline structure

![image](https://user-images.githubusercontent.com/35796218/167388098-7ba089ff-0707-4449-9689-389dc3e64944.png)

![image](https://user-images.githubusercontent.com/35796218/167388032-62fb37fc-76b0-48e4-a7e0-85640f38e61f.png)

Configured pre deployment approvals before performing code deployment

![image](https://user-images.githubusercontent.com/35796218/167388253-a3db7cdf-352e-4448-b231-aa1d4b4f6f7c.png)

App service URL : 

https://brady-webapp.azurewebsites.net/
