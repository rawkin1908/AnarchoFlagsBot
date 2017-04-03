## Installation

You need to have the following installed:
* [NodeJS](https://nodejs.org)
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Open your command line (Windows: `Win+R`, Mac: open Launchpad and search `terminal`). 
Paste the following in your command line:

```
git clone https://github.com/rawkin1908/AnarchoFlagsBot
cd AnarchoFlagsBot
npm install
```

## Configuration

* Edit `users.json` to add your usernames and passwords
to your reddit accounts and all your throwaways. You may add as many accounts as you'd like.

* The script looks for a file called `target.bmp`. Depending on what you want to defend (hammer & sickle and party parrot,
ancom flags, or rojava flag) modify the appropriate BMP's file name to `target.bmp`

## Bitmap files
* Hammer-Sickle-target.bmp: Hammer & Sickle
* Party-Parrot-target.bmp: Party Parrot
* Rojava-target.bmp: Rojava flag
* HS-PartyParrot-target.bmp: Hammer & Sickle and Party Parrot

## Usage

Paste the following in your command line:

```
  npm run start
```

Every time it's time to place a pixel the bot will download the board
(and latest remote target) and find the first pixel that doesn't match
the target, and fill it with the correct color. It'll keep keep drawing forever and if it can't draw anymore it's gonna
wait until something breaks and fix it.

## Bug Reporting
Send PM to /u/ZombieJohnBrown with the error message and coordinates of the error (if applicable)

## Common Errors and their Solutions

Error message:
```
UnhandledPromiseRejectionWarning: Unhandled promise rejection (rejection id: 2): 
  TypeError: Cannot read property 'modhash' of undefined
```
Solution:
* Delete all mock user information from `users.json` and `queues.json`. Make sure these files contain only the information for reddit accounts that are confirmed to work.


## TODO:
* Add bmp for FALGSC
* Bash the fash?
