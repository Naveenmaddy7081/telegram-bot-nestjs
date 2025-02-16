# telegramWeatherBot

## Description

A telegram bot that allows users to subscribe for getting daily update on weather and an admin panel with google login for updating bot settings(api keys etc) and managing user accounts(blocking/deleting etc).
Make sure you have the following installed:

Node.js (LTS version recommended)

MongoDB

NestJS CLI

Telegram Bot Token


## Setup

Nest.js has been used for the backend.
React has been used for the frontend.

## Installation

$ bot-backend/npm install
$ client/npm install

## Running the app

```bash
$ bot-backend/ npm run start
$ client / npm run start
```

This should start the telegram bot.


## Bot Commands

- /start - starts the telegram bot 
- /subscribe - subscribe to weather updates
- /weather city - show the weather


## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Admin Panel 

The admin panel has been created and deployed using vercel and railway.
The admin panel is available at [Admin Panel](https://bot-client-rho.vercel.app/)

## Stay in touch

- Author - naveenmaddy9956@gmail.com


