# Module-Challenge-15


## Challenge Objective
  -Create a RoboAdvisor to help with recommendations for an investment porfolio retirement plan. 
 
## Instructions
Three steps:

  1) Configure the initial robo advisor

  2) Build and test the robo advisor

  3) Enhance the robo advisor with an Amazon Lambda function

## Step 1: Configure the Initial Robo Advisor

* Create a Amazon Lex bot named RoboAdvisor 
    
* Establish new intent, named recommenedPortfolio 
  
* Congfig sample utterance:
  
    <img width="352" alt="image" src="https://user-images.githubusercontent.com/105945472/188673772-41a44c10-9036-459c-b31e-8e2acccbbed7.png"> 
  
* Create four slots:
    
    <img width="599" alt="image" src="https://user-images.githubusercontent.com/105945472/188673565-a2d1c3e9-097a-4897-8e91-2e6eb4327e22.png">
  
* Confirmation Prompts:
  
    <img width="355" alt="image" src="https://user-images.githubusercontent.com/105945472/188674186-3218379b-675e-44e9-a09e-038339f6ed9d.png">
    
## Step 2: Build and Test the Robo Advisor   
  
 * Build the bot buy selecting the Build button
  
 * When building it complete test the bot. 
  
 * Record video of working bot *Refrence video located under Module-Challenge-15 repository file named: Amazon Lex - Google Chrome 2022-09-01 05-22-12 
  
## Step 3: Step 3: Enhance the Robo Advisor with an Amazon Lambda Function

 * Create new Lambda funcition using Python 3.7 as the runtime programming language. 
  
 * Complete recommened_portfoliio funciton by adding the requested validation rules. 
    
 * Implement investment recommendations evidenced by the accuracy of the bots response. 
    
 * Inculded the Lambda function into the RoboAvisor bot and record a vid with bot working *Reference video located under Module-Challenge-15 repository file named:        Amazon Lex - Google Chrome 2022-09-06 05-47-12 


## Technoliges
  * AWS Lambda
  * AWS Lex
## Imports and Libraries
from datetime import datetime
from dateutil.relativedelta import relativedelta
  
  
  # COMMENT 
  Unfortunately, I my bot was unable to return a risk level response. I reviewed the risk level code portion several times and still was stumped on receiving an outcome. The utterances and slots for the bot operated properly. 
