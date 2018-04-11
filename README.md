# edbot

![Basic Drawing](./BasicDrawing.jpg?raw=true "Basic Drawing")
EdBot serves as hub for multiple bot platforms
Developers only need to name their lambda function starting with edbot_ and their function will be exposed in the chat room.
For example, if the lambda function is name edbot_action, then in the chat room, if the user types “@action do something” the “do something” part will be passed through to the edbot_action Lambda function. 
Only the edbot function needs to be connected to the bot platforms, leaving the Lambda developers free to focus on the features of their Lambda function, with little or no knowledge of the chat bot setup. 

