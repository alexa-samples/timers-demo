# Timers API Demo

# ** This repository has been archived **
This repository is still available as a point-in-time reference, but no further updates or support will be prioritized.


## What You Will Need
*  [Amazon Developer Account](http://developer.amazon.com/alexa)
*  [Amazon Web Services Account](http://aws.amazon.com/)
*  An Alexa device which supports timers (e.g. Amazon Echo)

## Setting Up the Demo
This folder contains the interaction model and skill code.  It is structured to make it easy to deploy if you have the ASK CLI already setup.  If you would like to use the Developer Portal, you can follow the steps outlined in the [Hello World](https://github.com/alexa/skill-sample-nodejs-hello-world) example, substituting the [Model](./models/en-US.json) and the [skill code](./lambda/custom/index.js) when called for.

## Running the Demo
To start the demo say "alexa open timers demo".  Then say "create a timer", "check my timers", "delete my timer", "pause my timer" or "resume my timer" to manage your custom timers.

You will need to grant Timers permissions to the skill either using the Alexa app or voice permissions.

> Note: attempting a one shot to create the timer may trigger the built in timer functionality.

> Note: timers are not supported in the Alexa developer console simulator.
