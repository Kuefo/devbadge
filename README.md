--- Instructions ---
Go to https://discord.com/developers/applications, and create a new application on the account you want the badge on.
Go to the bot tab and generate a bot account for the application.
Click the "Reset Token" button to generate a token (if you have 2fa enabled, you'll need your code).
Copy the token to your clipboard.
Click this badge to clone this repo to a new repl in Replit -> Run on Repl.it
You will be redirected to Replit, you might have to create an account (you can Register with Google).
Replit is a website, and does not run off your computer!
Wait for the repo has finished cloning and the repl to fully connect.
Click the green "Run" button at the top.
Go to the console (big black square on the right) and paste in the token you copied earlier (Note: CTRL + V won't work, you'll need to do CTRL + Shift + V or right-click and click paste).
Press the 'Enter' key.
Wait for it to print 'DONE | Application/Bot is up and running. DO NOT CLOSE THIS TAB UNLESS YOU ARE FINISHED USING THE BOT, IT WILL PUT THE BOT OFFLINE.' in the console, DON'T STOP THE PROGRAM OR CLOSE THE TAB YET OR THE BOT WILL CONSIDERED BY DISCORD AS 'UNRESPONSIVE'
Go back to the application page, go to the "General Information" tab, scroll down and copy application id.
Create a new discord server (you can delete it at the end).
Enable community on the server (you only need to do this if you don't own any other discord server with community enabled)
Return back to https://discord.com/developers/applications.
Copy the application id.

Use this invite link to add the application to the server: (replace {applicationid} with what you copied) https://discord.com/oauth2/authorize?client_id={applicationid}&scope=bot%20applications.commands&permissions=105227086912
In the server, go to a channel and use the /ping command on the bot.

Go to the https://discord.com/developers/active-developer page and register everything (if it says you're not eligible, it's because you're not registered in their system yet. you might have to wait up to 24 hours).
Congrats on that shiny new badge.
NOTE: Make sure you have the “Use data to improve Discord” setting enabled under User Settings > Privacy & Safety otherwise you won't be able to be marked as eligible.

NOTE 2: You do not need to keep the Replit tab open 24/7. Only go to the Replit url whenever you want to run your bot.
