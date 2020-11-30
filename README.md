# Chatbot-UI

Looking for UI Designs for your ChatBot with alluring colours and responsive features? Look no further! Explore our available designs in different colour schemes and ensure smooth traversal across all devices. Don't like the available designs? Don't you worry! Customize themes and colours according to your liking very quickly and easily.

<h2><a href="https://elysian01.github.io/Chatbot-UI/">Click here</a> to see documentation and working demo of UI</h2>

## Get Started

Copy-paste the stylesheet <link> into your <head> before all other stylesheets to load our CSS.

```
<link rel="stylesheet" href="https://drive.google.com/uc?id=1x2TCnJdXTQFErgZhxjMUWKIIfIfSbIy-">
```

Copy-paste the folowing code into your <body>, and update the function parameters to your need.

```
<div id="chat-container"></div>

<script src="https://drive.google.com/uc?id=1QslZLwqbJl471otp1Ph1y8MLHSzKqCPl"></script>

<script>
createChatBot(host = 'http://localhost:5005/webhooks/rest/webhook',
botLogo = "./imgs/bot-logo2.png ",
title = "Covid BOT ", welcomeMessage = "Hey, i am Covid Bot ",
inactiveMsg = "Server is down, Please contact the developer to activate it ",
theme="blue ")
</script>

```

### The frontend webiste for documentation is also built using Vuejs [files are here](./chatbot-ui-vuejs-app) and deployed version of site is [here](https://chatbot-web-ui.netlify.app/) 