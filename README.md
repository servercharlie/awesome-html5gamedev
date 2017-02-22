<p align="center">
  <br>
  <img src="http://i.imgur.com/ObPvla5.jpg" alt="awesome">
  <br>
  <br>
</p>

## awesome-html5gamedev
A curated list of awesome things related to HTML5 Game Development

- [Official Libraries](#official-libraries)
- [Official Examples](#official-examples)
- [Community](#community)
- [Tutorials](#tutorials)
- [Game Developer Tools](#game-developer-tools)
- [General Developer Tools](#general-developer-tools)
- [Miscellaneous Links](#miscellaneous-links)

### Official Libraries
- official libraries, sites, etc

### Official Examples
- pixi, phaser, panda, etc

### Community
- game dev forums, reddits, discord & slack, etc

### Tutorials
- sites, vids, forum posts, etc.

### Game Developer Tools
- Spritesheets / Texture Management
  - Spritesheet Packer (Free / Open-source)
    - Supported Formats: 
	- @ 
  - TexturePacker (Paid)
    - Supported Formats: 
	- @ 

### General Developer Tools

# All About Games

### Game Types
- test
- test 
  - test

### Game Genres


### Game Platforms
- **_What are the types of platforms?_**
  - Desktop (Windows, Mac, Linux)
  - Smartphones, and Tablets (Android, iOS, Windows Phone, etc.)
  - Desktop Browsers (Chrome, Firefox, Safari, Opera, Internet Explorer & Edge)
  - Consoles, such as Xbox One, PS4, Wii U, 3DS, etc.

- **_Supported platform versions_**
  - Ask yourself, do you want your game to run only in new versions of iOS and Android, or also on older versions?
  
- **_Canvas or WebGL in platforms_**
  - In the case of HTML5 games, you'll want to maximize the experience given the platform your users are using. Can your target platform support WebGL without sacrificing gameplay / playability?

### Game Output
- **_Screen sizes_**
  - Different devices have different screen dimensions / width-height ratio.
  
- **_Pixels per inch_**
  - This matters greatly for smartphones and tablets.
  
- **_Frames per second_**
  - As much as possible you wanna be running around 60 fps.
  - Anything else lower than that = poor gaming experience.
  
- **_WebGL or Canvas?_**
  - If you're simply aiming for desktop & browser, take advantage of WebGL if you can!
  - If you're aiming for smartphone / mobile / tablet support, and worried about platform compatibility.. Canvas is the way to go! (*Note: It varies greatly though, since sometimes you may want to take advantage of WebGL, too, ie: w/ CrossWalk*)
  
- **_Music & Sound Effects_**
  - ...
  
- **_Others_**
  - Is it portrait / landscape?
  - Does your game use vibrations?

### Game Input
- **_??_**
  - Keyboard & Mouse
  - Screen touch gestures like taps, swipes, pinch, shake, etc.
  - Gamepads / Controllers
  
  
### Game Networking

- **_Why should I worry about networking?_**
  - It matters when your game has to connect to the internet, ie: it has ads, or submits data to an online ranking, or connects to a server for multiplayer support, etc.
  
- **_I'm making a multiplayer game, should I use TCP / UDP, Websockets / Long-Polling?_**
  - Summary 1: TCP has more overhead than UDP, but UDP is more prone into being 'dropped' than TCP. Both has pros and cons and you can google it up (30 min read = enough to learn difference between both).
  - Summary 2: HTTP is built on top of TCP. Browsers operate on HTTP, so they're on top of TCP. Websockets are also built on top of TCP. Websockets > Long-polling, since long-polling is strenous for the servers. As of now, it means you're stuck with TCP since UDP support is only implemented in NodeJS's dgram library (hint hint: it means Desktop Clients built w/ Electron & Node-Webkit can take advantage of it).
  - Summary 3: However, you can use various techniques to 'mask' any latency / perceivable 'lag' effects on your games.. read the referenced in-depth articles below:
  - @ https://0fps.wordpress.com/2014/02/10/replication-in-networked-games-overview-part-1/
  - @ https://0fps.net/2014/02/17/replication-in-networked-games-latency-part-2/
  - @ https://0fps.net/2014/02/26/replication-in-networked-games-spacetime-consistency-part-3/
  - @ https://0fps.net/2014/03/09/replication-in-network-games-bandwidth-part-4/

<hr/>


# Javascript: Learning The Language

### Mozilla Developer's Network
- Introductory
  - @ https://developer.mozilla.org/en-US/docs/Web/JavaScript
- Intermediate to Advanced
  - @ https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction

### You Don't Know JS
- This is a series of books diving deep into the core mechanisms of the JavaScript language.
- @ https://github.com/getify/You-Dont-Know-JS
  
### Javascript Design Patterns
- Self explanatory.
- @ https://addyosmani.com/resources/essentialjsdesignpatterns/book/#mixinpatternjavascript
  
### Single-arity Functions
- @ https://gcanti.github.io/2014/09/25/six-reasons-to-define-constructors-with-only-one-argument.html
  
### Introduction to Promises
- @ https://developers.google.com/web/fundamentals/getting-started/primers/promises

# Javascript: All About NodeJS & NPM

### What is NodeJS

### What is NPM  

### Installing NodeJS & NPM
- @ https://nodejs.org/en/download/



# Javascript: Useful Libraries

### Lodash
- A modern JavaScript utility library delivering modularity, performance & extras.
- *Generate random numbers, sort arrays, throttle functions, etc etc.. (check the docs!)*
- @ https://lodash.com/
- @ https://lodash.com/docs/

### Socket.IO
- **Realtime application framework**, built on top of engine.io.
- *Allows server-to-client communication*
- *Note: Servers are ran under NodeJS.*
- @ https://socket.io/
- @ https://github.com/socketio/socket.io
  
### Primus
- **Same as socket io, but with more robust plugins** (check their github profile).
- @ https://github.com/primus/primus
 
### Primus EventEmitter3
- **NodeJS-like event emitters**, useful for event-driven code flow.
- @ https://github.com/primus/eventemitter3
  
### Primus EJSON
- **Extended JSON** from MeteorJS library.
- *Make sure to check out docs to maximize usefullness!*
- @ https://github.com/primus/ejson

### Sat JS
- Simple JS library for performing **2D collision detection**.
- @ https://github.com/jriecken/sat-js
  
### HammerJS
- Add support for **Touch Gestures**
- @ https://hammerjs.github.io/
- @ https://github.com/hammerjs/hammer.js



# Javascript: Creating Desktop Apps

### Electron
- Build cross platform desktop apps with JavaScript, HTML, and CSS
- *Compiles in Windows, Mac & Linux binaries, more preferred than Node-Webkit*
- @ https://electron.atom.io/

### Node-Webkit
- NW.js (previously known as node-webkit) lets you call all Node.js modules directly from DOM and enables a new way of writing applications with all Web technologies.
- @ https://nwjs.io/


<hr/>


# Programming: Version Control

### Git
- @ https://git-scm.com/downloads
  
### SourceTree
- 



# Programming: Code Editors
- JetBrains WebStorm

- Atom Editor

- Notepad ++
  - @ https://notepad-plus-plus.org/download/
  
- Sublime Text

# Programming: Cheatsheets

### Android Codenames, Tags, and Build Numbers
- At a high level, Android development happens around families of releases, which use code names ordered alphabetically after tasty treats.
- In this document: Platform Codenames, Versions, API Levels, and NDK Releases
- @ https://source.android.com/source/build-numbers.html

# Programming: Useful Statistics

### Market share held by the leading internet browsers in Europe from January 2012 to January 2017
- This statistic displays the market share, or the share of internet users in Europe who used different browsers to access the web from January 2015 to January 2017. As of November 2016, Chrome had a 50.49 percent share of the European market.
- @ https://www.statista.com/statistics/269881/market-share-held-by-internet-browsers-in-europe/


### Mobile OS Fragmentation (as of June 2016)
- This chart shows the percentage of iOS and Android devices running the most recent versions of the two operating systems in June 2016.
- @ https://www.statista.com/chart/5118/mobile-os-fragmentation/

### Mobile Payment Volume Increase (projection, from 2015 to 2021) 
- This chart shows the estimated growth in mobile payment transaction volume in the U.S.
- @ https://www.statista.com/chart/7793/mobile-payment-transaction-volume/

### Average cost per installation (CPI) for Android and iOS apps worldwide as of February 2017 (in U.S. dollars)
- This statistic gives information on the average cost per installation (CPI) for Android and iOS apps worldwide as of February 2017. During the measured period, the average CPI for an Android app was 0.44 U.S. dollars.
- @ https://www.statista.com/statistics/247411/cost-per-installation-android-ios-worldwide/

### Miscellaneous Links
- cordova, crosswalk, etc
- monetizing

|Table Head Test|
|:-------------:|
| Row Test      | 


### drafted / to-include
- books
- twitter
- youtube channels
- 0fps series
- https://0fps.net/2014/02/17/replication-in-networked-games-latency-part-2/
- statistics, between desktop & mobile & tablets
- statistics, iOS vs android
- statistics, of ios and android versions
- statistics, browser share, mozilla, chrome, ie, etc
- links to webgl coverage
- links to other game engines and renderers
- links to gists and demos
- developer tools --> game developer tools
- general developer tools (filezilla, flux, faststone, screentogif, etc)
- guide to mmo game hosting
- web concepts
- vps, dedicated servers, shared hosting 
- virtual machines, etc.
- server location, server latency, server hardware & bandwidth throughput / ingress/egress
 - github, gitlab, bitbucket
 - trello, slack, telegram, discord, gitter
 - facebook, twitter
 - game assets
    - free and paid
 - cover use of browserify, babel with preset-env and uglify js w/ mangle and compress
 - 
	
git add -A && git commit -m "Update Readme.md" && git push -u origin master