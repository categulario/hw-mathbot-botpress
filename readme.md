# Mathbot

Mathbot is a chatbot with which you can practice multiplication tables. Created for children, or adults too, to practice and master the tables
in a funny way.

You can try it here: [http://chatbotmakers.com/tablas/](http://chatbotmakers.com/tablas/)

Master branch runs with Botpress X. Branch botpress-v1-1 is an old and deprecated version.

There is also a version being developed using Botkit. https://github.com/roccons/hw-mathbot-botkit/


## Installation (Botpress X)

__Note:__ *You can only install as a global dependency a single version of botpress (either v1.x or v10.x). If you want to run a project with another version you have to indicate the path of the local installation of botpress.*

Install botpress as a global dependency

```
// using npm
npm install -g botpress@10.28.x

// using yarn
yarn global add botpresss@10.28.x
```

Clone this repository

`git clone git@github.com:roccons/hw-mathbot.git`

Enter the folder that was created after cloning

`cd hw-mathbot`

Install the dependencies

```
// using npm
npm install

// using yarn
yarn install
```

Run the chatbot with the following command

`botpress start`

If you don't have installed this version of botpress as a global dependency, run:

`node_modules/.bin/botpress start`

Enter the following address from any web browser

For dashboard:
`http://localhost:3000`

For chat only:
`http://localhost:3000/s/chat`


Say anything in the chat and just follow the instructions

---

If you [deployed](https://botpress.io/docs/latest/getting_started/trivia_deploying/) this bot to heroku you have to set some environment variables:
- Password
`heroku config:set BOTPRESS_PASSWORD=yourSecretPassword`
- Botpress url.
`heroku config:set BOTPRESS_URL=https://your-url-12345.herokuapp.com`