# Si Exam Project

## Made by 

Nur-Alhussein Salem Sabet ns156

## Links To System Components Repositorys

[Games Rest API](https://github.com/hassunisalem/GamesRestAPI)
[Calculate Price](https://github.com/hassunisalem/Calculate_price)

## Business Case

GameStop is a video game store - which arguably is an outdated business since most games are bought online today. 
GameStop had a business model that consisted of selling used video games. 
The way they’d appeal to their customer base to sell their games, was the idea that they could buy brand 
new just-released games with a discount, if they gave up one of their own games. 
The more recent titles they gave up, the more discount they’d get. They just had to show up to one of GameStop’s stores 
and show their games that would be tested and confirmed its condition.

This project is an automated solution to this business model, which solves the constraints of showing up physically in the store, 
but instead having the user being able to pick the game they want on the website and request a game discount based on a trade with their own game. 
Then they’d mail their game to the nearest store and the coworkers which have a list of all requests and would test the game's condition.If the games is working the system proceeds to calculate a price, 
send an offer to the user and store the offer in af database, for further business analysis and ad targeting.   

## System architecture

![alt text](https://github.com/hassunisalem/Si_Exam_Repo/blob/main/SystemArc.PNG "System architecture
")

## Business Proces Model Notaion

![alt text](https://github.com/hassunisalem/Si_Exam_Repo/blob/main/BPMN_model.png "BPMN
")  

BPMN and Camunda are used for the coworkers to confirm the used game condition and delegate the flow of the system accordingly. 
Future work could also include adding a time limit on receival of the used game. If a discount deal is requested but the used game 
never shows up, the system could cancel the deal after a fixed time interval has passed and Camunda is an obvious place to implement that.  


