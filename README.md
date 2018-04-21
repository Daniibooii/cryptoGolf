# crytoGolf
A game of golf, with a few twists.<br>
Play the demo! https://guarded-fortress-57011.herokuapp.com/<br>

<img src="https://github.com/Daniibooii/cryptoGolf/blob/master/assets/images/CryptoGolfPHImage.PNG" height: 350px width: 380px><br>

## How to Play
To start, the user will select their favorite cryptocurrency.<br>
This will perform an API call to generate the ground on which the game is played;<br>
it might help to pray for a stable day in the crypto markets!<br>
Then, a ball will generate for the user to hit.<br>
From here, just aim for the hole, and swing away!<br>

## How to Install & Run
To install,
- clone the repo
- run `npm install`

To run,
- run `npm run start`
- in a browser, open http://localhost:3001

# Project Description
This is my personal fork of a group project.<br>
It was demoed to a group of other programmers along with a Powerpoint Presentation;<br>
I created it, ran the demo, and am quite pleased with how it turned out, all things considered.<br>

The PPs are available for viewing here: https://docs.google.com/presentation/d/13ZuqBCF-6kWDh_LJ6N-ZTZI-vsIbP5VXtHiNx92Tfo4/edit?usp=sharing<br>
For reference, Jared and Cris are two more experienced programmers who provided feedback.<br>
All images used in the slides are assumed fair use/non-commercial purposes;<br>
if alerted that any are not, they will be removed.<br>

The original project README can be found directly below.<br>

## Project Description
This project represents a group effort to create a physics-based golf game, with a twist:<br>
the terrain is generated based on the ups and downs of the cryptocurrency market.<br>

The project was conceived and organized by Chandler Dibble;<br>
it was developed by a four-person team over one week.<br>
The total time spent developing our project, including time spent learning new tools, is estimated at 120+ hours.<br>

We primarily utilized Javascript with Node, JQuery, Matter.js, and Express.js.<br>
HTML and CSS were deliberately de-emphasized to allow us to generate our images, shapes, etc. with Javascript.<br>
This is reflected in contributors' roles all including "back-end" work.<br>
Bitfinex's API was utilized to provide our cryptocurrency exchange data, with which we generated our terrain.<br>
Heroku was also utilized for the first time by group members, as previous projects were hosted solely on Github Pages.<br>
Significant time was devoted to learning Matter.js.<br>

Internally, we needed to generate a basic world and physics-based parameters for our game.<br>
Objects such as a golf ball were created and assigned values to allow their proper interaction.<br>
Functions were written to generate our objects, cause them to interact, and influence the manner in which they interacted.<br>
The Bitfinex API was called in order to generate the ground on which golf was played.<br>
Each project member spent time learning how to implement Matter.js.<br>
Expertise on cryptocurrencies was provided by Tim Hill.<br>


## Contributors
__Afolabi Akingbe__ - troubleshooting/math MVP; research, back-end;<br>
Github: https://github.com/folaakingbe<br>
__Chandler Dibble__- project lead/organizer; research, back-end/front-end;<br>
  Github: https://github.com/Xhandler<br>
__Tim Hill__ - cryptocurrency expert; research, initial organiziation, back-end;<br>
  Github: https://github.com/peakcodes<br>
__Daniel Mace__ - project historian/note-taker; research, back-end/front-end, PPs, Heroku;<br>
  Github: https://github.com/Daniibooii<br>

## Notes
Our initial project idea was gito create a Rube Goldberg game;<br>
it became apparent that this wouldn't be viable within the timeframe we allotted ourselves.<br>

To view our original work, please see: https://github.com/Xhandler/rubegoldberg<br>
Future work on rubegoldberg, collaborative or independent, is possible.<br>

## Inspirations
Desert Golfing served as our initial inspiration;<br>
the idea of combining this with cryptocurrency was provided by Jared Nielsen.<br>

## Resources
Project Group's One Drive: https://onedrive.live.com/view.aspx?resid=A24E366977AFCFDC!951&app=OneNote&authkey=!ALdVeX0u2AWWcC0<br>
Matter.js Package: https://www.npmjs.com/package/matter-js<br>
Matter.js Info/Tutorials: http://brm.io/matter-js/<br>
Express.js Package: https://www.npmjs.com/package/express<br>
Express.js Info/Tutorials: https://expressjs.com/<br>
Heroku Deployment Guide: https://github.com/nielsenjared/node-express-heroku-deployment<br>

Desert Golf: http://desertgolfing.captain-games.com/<br>
Many Golf Main Site: https://manygolf.club/<br>
Many Golf Repo: https://github.com/thomasboyt/manygolf<br>
Bitfinex Main Site: https://www.bitfinex.com/<br>
