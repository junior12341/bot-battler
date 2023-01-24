# bot-battler

# INTRO
As a galactic web developer, you have been hired by a powerful overlord to create a website that allows them to browse a collection of robots, examine their details, and enlist the ones they like into their army. The design of the website has already been completed, so your task is to add the necessary functionality by getting information, displaying it correctly, and integrating it into the existing code. Keep in mind that while you should aim to seamlessly insert your code into the existing structure, slight styling discrepancies are not a major concern. Welcome to Bot Battlr, the ultimate destination for building your own robot army.

For this project, you will be developing a React application that displays a list of robots and other features. It is important that you pay attention to the instructions for setting up the application and try to find the appropriate places to add code to the existing codebase. This code challenge is also assessing your ability to follow directions. Although you have a good degree of freedom in how you implement the features, make sure to read the instructions carefully.

# SETUP
To start, run npm install && npm start to get the app up and running.

Make sure to open http://localhost:8002/bots in the browser to verify that your backend is working before you proceed!

The base URL for your backend is: http://localhost:8002

# WHAT IS AVAILABLE
The BotPage is the topmost component after App, and acts as the main container for all the elements of the page. The BotCollection and YourBotArmy are child components of the BotPage, where all the robots will be displayed in the BotCollection, while YourBotArmy (the green section on the top of the screen) will only show the robots that have been selected by the user. The BotCard and BotSpecs are presentational components that have been supplied to you and are pre-styled, it is your responsibility to get the data into them. The code for styling the page has already been written, so you should focus on adding functionality rather than editing it. However, minor styling issues are not a major concern.


# OUTPUT
As a user, I should be able to:

See profiles of all bots rendered in BotCollection.
Add an individual bot to my army by clicking on it. The selected bot should render in the YourBotArmy component. The bot can be enlisted only once. The bot does not disappear from the BotCollection.
Release a bot from my army by clicking on it. The bot disappears from the YourBotArmy component.
Discharge a bot from their service forever, by clicking the red button marked "x", which would delete the bot both from the backend and from the YourBotArmy on the frontend.
