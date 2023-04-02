# CustomDiscordAIChatbot by Rokawoo https://rokawoo.neocities.org/

Instructions to set up your bot:

Pre-rec: Install all libraries with 'pip install discord openai asyncio discord-webhook'

1.) Download the chatBot code, then open it in an editor.

2.) Find line 13, input your bot's personality string, this will be fed to the OpenAI api's role, for example you can put "You are to play the role of..." and add
any other information, creating a good personality string is crucial to your bot's behavior.

3.) Find line 21, input your OpenAI api key.

4.) Find line 35, enter the status you want want your bot to have, it will say 'playing [status]'.

5.) Find line 49, enter the name of your bot in all lowercase, if a user sends a message with the bot's name in it, the bot will respond.

6.) Find line 92, enter your discord webhook url here, this is meant for the purpose of logging your bot's conversations. You will need to set this up externally.

7.) Find line 105, put your bot's error message in the case of an exception.

8.) Find line 109, enter your discord's bot secret key.

You are now ready to run the bot, make sure the bot is in your server, it will be able to talk in any text channel it has access to, say its name. Enjoy!
You may run the bot by hosting it locally or on replit. Here is my replit for example: https://replit.com/@RokaAwoo/Roka


OPTIONAL:
On line 83 you can change the bot's past message memory, by default it only saves what is asked of it by a user.

You may replace line 85 with the contents of line 87 to 89 for better context awareness, it will addtionally save its own responses.

On line 76 you can change the bot's typing time, it is dynamic meaning the longer the message the longer it takes to type, but by defualt its just a tiny diffrence.
