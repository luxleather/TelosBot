# SupportBot

SupportBot for Transcendence blockchain Discord server written in Python 3.6 for Heroku.

![SupportBot](https://i.imgur.com/5IWtmTp.png)

How to fork the repository and set it up to work with Heroku?

Fork a copy of this repository by clicking the 'Fork' on the upper right-hand.
Create an application for Heroku.

Under 'Deploy', do the following:

-Deployment Method => Connect your GitHub

-App connected to GitHub => Search for the forked repository

-Automatic Deploy => Enable Automatic Deploy (to redeploy after every commit)

Under 'Settings', click on 'Reveal Config Vars' and enter the following:

-KEY => DISCORD_TOKEN

-VALUE => (Enter the bot token that you copied from the developer portal)

-Click the 'Add' button after entering all of this information.

Under 'Resources', do the following:

-Click on the 'Pencil' icon.

-Switch the worker from off to on.

-Click 'Confirm' to finalize the decision.

NOTE: You are allocated 550 free Dyno hours, which will not last the entire month. However, if you provide a credit card to verify your identity, you are given an additional 450 hours, which will allow your bot to run indefinitely.

