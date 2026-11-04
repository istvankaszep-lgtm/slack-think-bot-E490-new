# slack-think-bot-E490-new

# Why i made this?
I made this proiect bc i touth this gonna be a good proiect.
I also made this, so other people who want to make a slack bot/app, they can just use this code, if you want to have more command/other commands, you can just write it in to the code and don't forget to add it on https://api.slack.com/slash-command. 

<img width="1920" height="1008" alt="Slack API_ Applications _ Hack Club Slack - Google Chrome 2026  10  31  19_13_54" src="https://github.com/user-attachments/assets/b33ae323-3c07-4530-b043-4b298ccc7153" />


# how do i get the token's?
To make your bot alive you need 2 token's and 1 api.
the firs token you get is when you are setuping the bot.
For the other one you need to go to https://api.slack.com/OAuth & Permissions tab.
after that go down a bit and click on generate token.
Then but those token's into a .env file, then make a .gitignore file and write .env in it.

# Build the bot locally
Now we’ll create the Node project, drop in the bot code, and run it on your machine.

1. Create the project
Create a new folder for your project and open it in VS Code.

Open the integrated terminal with Terminal → New Terminal so commands run inside the project folder.

Initialize the project and install dependencies:

# npm init -y
# npm install @slack/bolt dotenv

npm: command not found / npm is not recognized? You don’t have Node.js installed. Download it from nodejs.org/en/download, then re-run the commands above.

# warning without this the bot will not run!
If you used a different slash command name in the Slack dashboard, change /think-bot-e490-ping here to match.

# 4. Run the bot
node index.js

If it works, you’ll see:

bot is running!
<img width="1920" height="1008" alt="Slack API_ Applications _ Hack Club Slack - Google Chrome 2026  10  31  19_46_03" src="https://github.com/user-attachments/assets/138f0218-25fc-4502-b951-798dc893cef0" />
# To test it type a command.
1. /think-bot-e490-ping (test's if the bot is alive)
2. /think-bot-e490-help ( show's all the command's)
3. /think-bot-e490-catfact (give's a cat fact)
4. /think-bot-e490-joke (give's a joke)
