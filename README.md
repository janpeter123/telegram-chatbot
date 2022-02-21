# Telegram Chatbot

# Introduction
This is a telegram chatbot based on IBM Watson Assistant V1 and Node-red.

# Functionalities 
 - This bot answers questions about Ford cars and it recommends you new Ford products to buy. It also integrates AI to predict car revision prices and values according to the mileage given.

 - This AI was constructed for Ford Ranger model more specifically and was based on this [maintenance table](https://www.ford.com.br/servico-ao-cliente/revisao-preco-fixo/ranger/).

 - It uses IBM Watson Speech to Text and IBM Watson Text To Speech to better accessibility thus blind users can also use this app by typing a cheatcode on telegram then the bot will communicate via audio messages and it can also understant audio messages in Brazilian Portuguese.


# Folder structure 
```
├── DecisionTreeFord.ipynb         # AI Model Code
├── flow_guardian.json             # Node Red Flow
└── skill-FordBot.json             # Watson Assistant V1 Dialog Skill
```

## About the AI
I had used `Decision Tree Regression` to create this model because it had to follow the maintenance table provided, this table wasn't much of a linear equation, neither any type of equation that I know would be good enough to fit this model. So I opted for the Decision tree Model and It was ok.

## Why Ford Company?
Because this project was a college valuation in partnership with Ford Company.





