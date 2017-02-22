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


### Game Engines, Renderer Engines


### Physics


### Game Platforms
- **_What are the types of platforms?_**
  - Desktop (Windows, Mac, Linux)
  - Smartphones, and Tablets (Android, iOS, Windows Phone, etc.)
  - Desktop Browsers (Chrome, Firefox, Safari, Opera, Internet Explorer & Edge)
  - Consoles, such as Xbox One, Xbox 360, PS3, PS4, PS Vita, Wii U, New 3DS, etc.

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




# Programming: Apache Cordova

### What the f*ck is Cordova?
- Apache Cordova allows you to build mobile apps with HTML, CSS & JS.
- Allows you to target multiple platforms with one code base.
- It's free and open source.

### In layman's term?
- Basically it's something you can use to create mobile versions of your HTML5 games.
- By 'target multiple platforms', it means you can create versions for Android, iOS and Windows Phone.
- Simply follow the links below to create your first cordova app.
- Once you're done, replace the html files in the "/www/" folder of your cordova project, rebuild it, test your mobile app output and tweak your HTML5 game as it fits.
- Note that cordova also allows you to utilize "cordova plugins", which gives you a javascript API for the native side of your mobile platforms. Ie: Allow your mobile app to access the internet, save a file, etc etc.

### Building Your First Cordova App
- @ https://cordova.apache.org/
- @ https://cordova.apache.org/docs/en/latest/guide/cli/index.html
- @ https://cordova.apache.org/plugins/

### Using Cordova & Visual Studio to build Android & iOS Apps
- @ https://weblog.west-wind.com/posts/2015/jan/06/using-cordova-and-visual-studio-to-build-ios-mobile-apps#iOSsupportisExcellent
- @ https://taco.visualstudio.com/en-us/docs/install-vs-tools-apache-cordova/
- @ https://taco.visualstudio.com/en-us/docs/tutorial-package-publish-readme/

### Common Solutions to Errors (in building w/ Visual Studio)
- Android Studio Directory
  - ANDROID_HOME should be set to Android SDK directory. *ie: C:\AndroidStudioSDK*
  - ADT_HOME should be set to Android SDK directory. *ie: C:\AndroidStudioSDK*
  - ANT_HOME should be your Ant's directory. *ie: C:\Ant*
  - JAVA_HOME should be your Java SDK's directory. *ie: C:\Program Files (x86)\Java\jdk1.8.0_121*
  - _JAVA_OPTIONS should be "-Xmx512M" w/o quotes.
  - PATH should contain directory for Android *ie: C:\AndroidStudioLocal\bin;C:\AndroidStudioSDK\tools;C:\Ant\bin;C:\Program Files (x86)\Java\jdk1.8.0_121\bin*
- Your JDK & JRE version should be 1.8 instead of 1.7.
- Your Java Development Kit's version must match your Java Runtime Environment's version. *ie: JDK v8 = JRE v8*
- add "org.gradle.jvmargs=-XX:MaxHeapSize\=512m -Xmx512m" w/o quotes to your "project.properties" file at "%YourVisualStudioProject%\platforms\android" directory.
- add "multiDexEnabled = true" w/o quotes to your "defaultConfig { }" section in your "build.gradle" file at "%YourVisualStudioProject%\platforms\android" directory.
- Always Build->Clean your project before building it.


# Programming: The Crosswalk Project

### What the f*ck is Crosswalk?
- The CrossWalk enables you to use the most advanced web innovations in your Android and Cordova apps.
- From the crosswalk-project.org homepage:
  - **Include the Crosswalk Project web runtime with your hybrid Android or Cordova / PhoneGap app, and users will consistently see it through a predictable, powerful WebView based on _Google Chromium_.**
  - Get consistent, predictable behavior by reducing Android device fragmentation.
  - Use the latest web innovations and APIs. Provide a feature rich experience on all Android 4.0+ devices.
  - Easily debug with Chrome DevTools.
  - Improve the performance of your HTML, CSS, and JavaScript.

|HTML5 feature|Without the Crosswalk Project|With the Crosswalk Project|
|:-----------------:|:----:|:---:|
| WebRTC			| Nope | Yup |
| WebGL 			| Nope | Yup |
| Vibration API		| Nope | Yup |
| Presentation API 	| Nope | Yup |		
| WebView Updates 	| Nope | Yup |

### In layman's term?
- Simply put, if you want to harness the power of WebGL (and helluva bunch of other features), use CrossWalk!

### Okay, how do I use it?
- **The ideal / recommended way is to _use crosswalk as a WebView plugin_ in your cordova project.**
  - Check out the link below for the quick guide!
  - @ https://crosswalk-project.org/documentation/cordova.html
  - *Note that the same workflow / plugin process is also possible if you've created your cordova project in Visual Studio*
- However, if you don't wanna go the cordova way (very messy, imho)..
  - https://crosswalk-project.org/documentation/getting_started.html

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


# Programming: Tools, Development Kits, Runtimes, Etc.

### Android Studio
- Android Studio Latest
  - https://developer.android.com/studio/index.html
- Installation Notes: 
  - You might have to set the following environment variables
    - ANDROID_HOME, set to **your-ANDROID-SDK-directory**
    - ADT_HOME, set to **your-ANDROID-SDK-directory**
	- PATH, add **your-ANDROID-SDK-directory**

### Apache Ant 
- Ant Build Tool Binaries
  - @ http://www.apache.org/dist/ant/binaries/
  - *Simply get a _ZIP_ file of the latest (or a known version that works), then extract it to a local directory.*
- Installation Notes: 
  - You might have to set the following environment variables
    - ANT_HOME, set to **your-Ant-directory**
	- PATH, add **your-Ant-directory_\bin_**

### Java Development Kit (JDK) & Java Runtime Environment (JRE)
- JDK Latest Versions
  - @ http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
- JRE Latest Versions
  - @ http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html
  - @ https://www.java.com/en/download/manual.jsp
- Old Version Archive (v7 & earlier)
  - @ http://www.oracle.com/technetwork/java/javase/downloads/java-archive-downloads-javase7-521261.html
- Installation Notes: 
  - You might have to set the following environment variables
    - JAVA_HOME, set to **your-SDK-directory**
	- PATH, add **your-SDK-directory_\bin_**

### Code Editors

- Atom Editor (Free, Open-source)
  - A hackable text editor.
  - @ https://atom.io/
  - @ https://atom.io/packages
  - @ https://atom.io/themes

- Notepad ++ (Free, Open-source)
  - A minimal / open-source text editor.
  - @ https://notepad-plus-plus.org/download/

- JetBrains WebStorm (Paid, Licensed)
  - A lightweight yet powerful JavaScript IDE, perfectly equipped for client-side development and server-side development with Node.js.
  - Great TypeScript support!
  - @ https://www.jetbrains.com/webstorm/
  
- Sublime Text (Paid, Licensed)
  - A sophisticated text editor for code, markup and prose. You'll love the slick user interface, extraordinary features and amazing performance.
  - @ https://www.sublimetext.com/

### Miscellaneous Links
- cordova, crosswalk, etc
- monetizing

|Table Head Test|
|:-------------:|
| Row Test      | 




# Drafted / To-Include
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
 - http://www.goodboydigital.com/exclusively-everything/
	
git add -A && git commit -m "Update Readme.md" && git push -u origin master