## Installation

You need to have [NodeJS installed](https://nodejs.org)

Paste the following in your terminal:

```
git clone https://github.com/rawkin1908/AnarchoFlagsBot
cd AnarchoFlagsBot
npm install
```

## Configuration

Change `users.example.json` to `users.json` and add your usernames and passwords
of your account and all your throwaways.

## Usage

```
  npm run start
```

Every time it's time to place a pixel the bot will download the board
(and latest remote target) and find the first pixel that doesn't match
the target, and fill it with the correct color. It'll keep keep drawing forever and if it can't draw anymore it's gonna
wait until something breaks and fix it.
