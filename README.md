DialogFlow
NodeJS
Facebook

=============
Create application on Heroku and create github pipeline
Make sure to define hellonode.js in the Procfile
Deploy application on Github
Open Heroku->application->settings
Scroll down to Domains and certificates
Domain name is your application name
Run app in browser and run hellonode.js

Your FIRST HELLO WORLD website is LIVE
=============

This is the actual URL where everything is getting replicated.
===============

1. Open DialogFlow integration and stop the bot
2. Open developers.facebook.com 
3. choose your app
4. From left choose webhooks, under the products
5. Click on Edit Subscription button
6. Click remove subscription

very important: When setting the webhook in developers.facebook

in the callback URL paste domainname / webhook/

For example:
https://smartattendancetracker.herokuapp.com/webhook/

To check logs on local command prompt

install heroku cli

heroku login

heroku logs -a smartattendancetracker

=====To check if the app is deployed
go to heroku
open app
you will see just deployed

Method: processMessageEvent(event)
Line :  console.log("Text", text);

Line: 318 doApiAiRequest(apiaiRequest, sender) 

Line: 332 this.doTextResponse(sender, responseText);

219: doTextResponse(sender, responseText) {

doApiAiRequest(apiaiRequest, sender) {
    //add
    let action = response.result.action;
    //Add another else if condition
declare method handleApiAiAction










==========Agenda Thursday=============
1. Make changes in the code. put some log statements and see output in the logs
2. Open Dialogflow, run the code and see json output (Diagnostic Info). Show outputContexts details which captures the complete parameters list
3. Open intent where questions are being asked and copy action name. In my case, it is personal-details-for-job-application

