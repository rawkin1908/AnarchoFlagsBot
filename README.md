## Installation

You need to have the following installed:
* [NodeJS](https://nodejs.org)
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Open your command line (windows: Win+R, mac: open Launchpad and search `terminal`). 
Paste the following in your command line:

```
git clone https://github.com/rawkin1908/AnarchoFlagsBot
cd AnarchoFlagsBot
npm install
```

## Configuration

* Edit `users.json` to add your usernames and passwords
to your reddit accounts and all your throwaways.

* The script looks a file called `target.bmp`. Depending on what you want to defend (hammer & sickle and party parrot,
ancom flags, or rojava flag) modify the appropriate BMP's file name to `target.bmp`

## Bitmap files
* HS-PartyParrot-target.bmp: Hammer & Sickle and Party Parrot
* AnarchoFlags-target.bmp: Ancom and anfem flags
* Rojava-target.bmp: Rojava flag

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

## TODO:
* Add bmp for FALGSC
* Bash the fash?
