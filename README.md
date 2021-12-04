# Air_Quality_Index
Data Science Project on Air Quality Index Analysis with Python.

## Introduction to Air Quality Index Analysis
Consider the analysis of the air quality index as a criterion ranging from 0 to 500. The higher the value of the AQI, the higher the level of air pollution and the greater the problem of air quality. For example, an AQI value of 50 or less represents good air quality, while an AQI value greater than 300 represents unsafe air quality.

For each pollutant, an AQI value of 100 generally corresponds to a concentration in ambient air equal to the level of the national short-term ambient air quality standard for the protection of public health. AQI values ​​equal to or less than 100 are generally considered satisfactory.

When AQI values ​​are above 100, the air quality is unhealthy: first for certain groups of sensitive people, then for everyone as AQI values ​​increase.


The AQI is divided into six categories. Each category corresponds to a different level of health problem. Each category also has a specific colour. Colour allows people to quickly determine if the air quality is reaching unhealthy levels in their communities.

## Data Science Project on Air Quality Index Analysis with Python

Now let’s get started with Data Science project on Air Quality Index analysis with Python. 

I will recommend you to use Kaggle notebook for this task. The reason why I am recommending you to use a Kaggle notebook you will understand at the end of this article, as we are going to use some APIs provided by Kaggle so I hope you will use a Kaggle notebook for the task of Air Quality Index analysis with Python.

**Now let’s get started with this task by importing the necessary Python libraries:**

![a1](https://user-images.githubusercontent.com/95492893/144712742-3953b153-1225-4aa1-b50d-5209ca5be74a.PNG)

**Now I will define some values that I will keep using in this task:**

**colorscale = ['#77DD77','#33AF13','#F6D20E','#F17700','#FE6B64','#F12424']
PAPER_BGCOLOR = '#f5f2d0'
BGCOLOR = 'LightSteelBlue'**

**Now let’s define and visualize the significance of each colour that is used in the Air Quality Index:**

![a2](https://user-images.githubusercontent.com/95492893/144712824-4e2387e0-8d6a-4d07-8ad0-9bfc9f87d3a9.PNG)
![a3](https://user-images.githubusercontent.com/95492893/144712861-a02961ad-e597-4a2c-9f30-ff17a655e9b2.PNG)
![a4](https://user-images.githubusercontent.com/95492893/144712894-05c6b6de-6bb9-4ef2-853a-44eb4cca1ab4.PNG)

![image](https://user-images.githubusercontent.com/95492893/144712920-badfb03e-41c8-4522-b276-76f12dafc995.png)

**I will be using the same colour codes as in the table above for all of the charts in this task to display the AQI levels. Now, let’s read the data and start with the task of analyzing the air quality index with Python:**

![a5](https://user-images.githubusercontent.com/95492893/144712965-3aa5491c-0b8e-4a06-ab11-397ce8484be9.PNG)

## Visualizing AQI Stations
The datasets I am using in this task are based on Indian AQI records. The air quality index is based on the measurement of emissions of particles (PM2.5 and PM10), ozone (O3), nitrogen dioxide (NO2), sulfur dioxide (SO2) and carbon monoxide (CO).

**Most of the AQI stations on the map monitor both PM2.5 and PM10 data, but there are a few exceptions where only PM10 is available. Let’s visualize all the AQI stations in operation in India:**

![a6](https://user-images.githubusercontent.com/95492893/144713019-cd21aeff-7950-4676-b1be-7dee13663a72.PNG)
![a7](https://user-images.githubusercontent.com/95492893/144713079-867d7455-093f-4754-89e2-3a7bdb221ace.PNG)
![a8](https://user-images.githubusercontent.com/95492893/144713131-23f4bdc4-451a-4276-9760-f9c831213fee.PNG)
![a9](https://user-images.githubusercontent.com/95492893/144713175-ac059f41-51e7-4034-bf38-612aac604f53.PNG)
![a10](https://user-images.githubusercontent.com/95492893/144713211-ae3c743d-95d4-4d1d-aebe-17726b31c204.PNG)
![a11](https://user-images.githubusercontent.com/95492893/144713251-4a4a950a-b15c-4487-9c81-c9301bd8e10c.PNG)
![a12](https://user-images.githubusercontent.com/95492893/144713291-e68e4718-6eb1-4d11-ba0b-642b19419aed.PNG)
![a13](https://user-images.githubusercontent.com/95492893/144713329-d16098a9-566b-4519-92ac-0bf97a0ea1a8.PNG)
![a14](https://user-images.githubusercontent.com/95492893/144713534-da043a0b-13b4-4459-a5d5-aa1befae19d9.PNG)
![a15](https://user-images.githubusercontent.com/95492893/144713518-fcccffa2-9166-46bc-8cd0-36c2108dfbad.PNG)
![a16](https://user-images.githubusercontent.com/95492893/144713605-ab5c6480-94d9-487e-b3ba-f8cf47fa9230.PNG)
![a17](https://user-images.githubusercontent.com/95492893/144713632-e22b4574-9145-496c-ace2-bdc96f320468.PNG)
![a18](https://user-images.githubusercontent.com/95492893/144713674-a9882381-d438-4ff6-ae4d-8e11b73b9956.PNG)
![a19](https://user-images.githubusercontent.com/95492893/144713704-5e9dc8e9-cc4c-43dc-9e55-da9542765a27.PNG)

![image](https://user-images.githubusercontent.com/95492893/144713720-e4eb0702-5aef-4053-bee1-6b9b4ee71d4c.png)


**Now let’s visualize the AQI stations per city in India:**

![a20](https://user-images.githubusercontent.com/95492893/144713807-00046720-0201-4edf-b2a6-14604eb9d04f.PNG)
![a21](https://user-images.githubusercontent.com/95492893/144713878-d9963f30-16d8-4457-a8db-f6570021b247.PNG)


![image](https://user-images.githubusercontent.com/95492893/144713898-2ef41349-c9c5-48ac-b3b1-310abdd4cee3.png)

## Analyzing Air Quality Index with Python
I will analyze the AQI in India by comparing the performance of before and after the lockdown, because we all saw a major change in the climate of almost every country because of the Lockdown.

The very first national lockdown to curb the spread of the coronavirus was imposed from March 23. Restricted lockdown or almost stops people movement i.e. have to stay in their homes and can only go out to buy essentials which means almost 0 vehicle movement, restricted movement of trucks, no construction, no moving industries or no construction.


**So all the things that contribute to pollution have been completely stopped. As a result, the environment begins to heal.**

![a22](https://user-images.githubusercontent.com/95492893/144713945-a5cf11dc-091b-43e5-9d5c-bfed9f3c47f9.PNG)
![a23](https://user-images.githubusercontent.com/95492893/144714013-0548810c-afe9-4cac-b35c-ba80424fff78.PNG)


Through the graph below, I will try to analyze this if the air quality has improved due to the lockdown. The left side of the plot will display the Before Lockout scenario and the right side will display the After Lockout scenario.

**The colour scale used conforms to the standard Indian AQI calculation scale:**

![a24](https://user-images.githubusercontent.com/95492893/144714053-cb237aa6-95af-469c-b36a-b5bac61ab7a6.PNG)
![a25](https://user-images.githubusercontent.com/95492893/144714112-046b26e3-6dcb-4ac0-989c-fb1ed6f28c2f.PNG)
![a26](https://user-images.githubusercontent.com/95492893/144714211-914f063d-71e1-4d0d-8b1d-1c85359b4278.PNG)
![a27](https://user-images.githubusercontent.com/95492893/144714257-82b0a53d-c133-481a-8cda-497b7a3b0608.PNG)

![image](https://user-images.githubusercontent.com/95492893/144714275-04309476-b040-4684-bd35-2d0a4a71a8da.png)

**The lockdown has worked to reduce air pollution in India as air quality is at best “satisfactory” at all measuring stations.**
































