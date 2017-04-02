## Installation

You need to have [NodeJS installed](https://nodejs.org)

Paste the following in your terminal:

```
git clone https://github.com/rawkin1908/AnarchoFlagsBot
cd AnarchoFlagsBot
npm install
```

## Configuration

Edit `users.json` to add your usernames and passwords
to your reddit accounts and all your throwaways.

## Usage

Paste the following in your terminal:

```
  npm run start
```

Every time it's time to place a pixel the bot will download the board
(and latest remote target) and find the first pixel that doesn't match
the target, and fill it with the correct color. It'll keep keep drawing forever and if it can't draw anymore it's gonna
wait until something breaks and fix it.
