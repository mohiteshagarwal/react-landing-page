
# React Landing Page

![Heroku](https://heroku-badge.herokuapp.com/?app=react-landing-page1)

With this guide you should get an awesome landing page up and running in 5 minutes!

Please ping me if you decide to use this so I can create a gallery of some sort :)

If you have ideas on how to improve this, issues or PR's are much appreciated!

[Live demo](https://react-landing-page1.herokuapp.com/) of what we'll be deploying.

![alt text](https://github.com/jonathancai11/react-landing-page/blob/main/demo.gif)

## Deploying

It is best practice to deploy first, and then develop second. Let's get started!


1.  #### Fork this repository

* Just hit the "Fork" button in the top right-hand corner of this Github repo.

2.  #### Setup Heroku

* Sign up for an account at [heroku](https://heroku.com/).
* Create a new Heroku app with a name you like

3.  #### Deploy to Heroku

* Go to the "Deploy" section in the project nav-bar
* Under "Deployment Method" click "Github"
* Under "Connect to Github", enter in your forked Github repository 
* (optional) Under "Automatic deploys", click "Enable Automatic Deploys" (this will ensure that every new commit under the main branch will automatically trigger a redeploy)
* Under "Manual deploy" click "Deploy Branch"
* We're done! Check [your-app-name].herokuapp.com to make sure it's live! 🚀


NOTE: If there is enough interest, I will add a guide on how to hook up a custom domain.  

## Developing

You'll obviously want to modify the content of this landing page to suit your next cool thing. Here are a few instructions on how:

#### Running locally

* In your terminal, run `yarn start`.
* Head to localhost:3000 in your browser to make sure its working.

#### Google Form

The most important aspect of your landing page is probably the form input. You need to see if your audience is picking up what you're putting down!

1. Head to [forms.google.com](forms.google.com) and create a form. It's quite intuitive.
2. When you're done creating it, click "Send" in the top right corner
3. Under the "Send via" line, click the embed icon. 
4. Copy the Embed HTML code.
5. Paste into `src/pages/Home.js` near the bottom where the form is (replacing the old iframe object).
6. (optional) Go to the "Responses" tab and in the three dots drop-down, check "Get email notification for responses" It's helpful to get notifications when people sign up.

NOTE: If there is enough interest, I may also add a TypeForm integration so you can see if people are even willing to pay you for pre-orders or beta access or what-not 😉

#### Hero

The Hero is basically what you first see when the page is loaded.

#### Features

I'm using gif's to show off the features but you can also just display static images.

If you like the gif's, I recommend using [giphy capture](https://giphy.com/apps/giphycapture) to screen record your features.

#### Google Analytics
