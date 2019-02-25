# Ohana Air Alexa Skill Listener

Heroku app linking the Ohana Air Alexa Skill with your Salesforce Org

## Getting Started



### Prerequisites

An existing Heroku account. If you don't have one create it in: https://signup.heroku.com/login
A connected app in your Salesforce org, with the Full Access Oauth Scope: https://help.salesforce.com/articleView?id=connected_app_create.htm&type=5 

### Installing

Click on the button to add this app to your Heroku Environment:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/heroku/node-js-sample)

Provide a name for your app (no spaces, no capitals. i.e: ohana-air-demo)

Click Deploy App.

After a Successful deployment, click on Manage App and Navigate to the Settings Tab. 

Here, click on Reveal Config Vars

You'll need to setup the following Environment Variables:

SF_CLIENT_ID - Your Connected App's Consumer Key (or use my own: 3MVG9CEn_O3jvv0wSU8GUbzMW4F4KMZ_M9NyJ5rdWWI82IaF9o9MqlONbc91u.afCgq2.2J9zxLPrHXZsaVkU)

SF_CLIENT_SECRET - Your Connected App's Consumer Secret (my own: 2873266068466400413)

SF_USER_NAME - Your Salesforce User Name

SF_PASSWORD - Your Salesforce Password
