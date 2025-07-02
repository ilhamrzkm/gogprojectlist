# Project Proposal for Grey Ogre Games
First of all I am going to start with the problems that has happened throughout store's operation. I will focus on MTG section of problems and I will use 3 factors to judge, importance, difficulty to create a solution and time requirement. The solutions can be applied to Pokemon or other card games but that is not our main source of income for now. Tradeoffs using current set of technologies should be laid out and discussed. Timeline of such solution creation will not be specific but it will be a rough estimate based on my current skills.

##  1. Pricing Baseline
At the moment we have enough data points from the past 4~5 years of using Binderpos and Shopify to generate a pricing baseline for cards. This project is not specifically targeted towards Binderpos but it will be the baseline of our prices for future. I can still use CK as a main data point but I believe creating our own pricing will be needed sooner or later. A solution that I will propose is to use a web crawler using https://spider.cloud/ to gather all the relevant data from CK, Hareruya etc. Next, we use the statistical approaches that I am currently learning to produce the pricing baseline tailored to our data points. I will start by using a smaller dataset, then expand from there for all the cards. 
```
4 Steps:
Gather Data -> Clean it -> Process it -> Data out
```

![alt text](pricingsweetspot.jpg)

 Importance | Difficulty | Time Required 
 :---: | :---: | :---: 
4/5 | 3/5 | 3 Months

Project extension ideas:
 - Auto-updater to Binderpos/shopify
 - Public facing buylist

## 2. Binder Clone
Currently Binderpos is our main source of sales and source of problem. I believe we should move away from Binderpos sooner or later but, in the meantime Binderpos pricing is not reliable anymore. Creating a fully functional Binderpos clone may be desirable and although it may look simple but, it is not.

To create a Binder clone I need this knowledge / requirements:
1. Operating Systems -> Distributed Systems in depth knowledge
2. 10000 ~ 100000 lines of code
3. A Software Team
4. Maybe funding?

There reason why Binderpos is getting worse is because maintaining data intensive systems requires a huge software team. Since their acquisition, I believe it is no longer their priority to have a huge software team and maintain the system.

 Importance | Difficulty | Time Required 
 :---: | :---: | :---: 
 5/5 | 5/5 | 12 months+

 Do keep in mind that alternatives will also face the same problem as Binderpos from being reliable to unreliable. It is just the nature of subscription based model to capture and lock in customers. Creating our own may be worth it if we are going to scale 5~10x our current operation, meaning this project is backed by more people and more money. Another plus is that we can do what binder do by capturing local store to use our system and scale from there.

 ## 3. Public Facing Buylist
I've mentioned previously that this project may be an extension from project 1 however, it may also be a starting point instead and scale to project 1
```
Project 1 -> project 3
VS
Project 3 -> project 1
```

Without the pricing baseline I can think of using MTG