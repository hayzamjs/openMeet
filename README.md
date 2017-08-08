# openMeet 
A dead simple WebRTC based video conferencing utility.

## Why openMeet? 

Since companies like MeetSpace are too expensive for small offices and such and also since softwares like Jitsi is just too hard to set up. OpenMeet can literally be up and running in a minute.

### How to get it up and running

1) Deploy on heroku
2) Deploy on your own server

### Method 1, Deploying on Heroku :-

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Fazelesswhite/openMeet)

### Method 2, Deploying on your own server :-

* Clone the repo using git clone https://github.com/Fazelesswhite/openMeet
* ` npm install`
* You need to use SSL for it to work since nowadays browsers are insisting on SSL for WebRTC, do this by changing the line 21   of server.js file,
  `from .file({ file: 'settings.json' }); to .file({ file: 'settings.ssl.json' });`
* To start the server `node server.js`
* Visit https://IP:1818/ to view the main application or https://IP:1818/admin for admin page for which the default credentials are hayzam.rb:minimumviablepassword

-----------

[//]: <> (openMeet is a fork of tubertc, which is a good project too but is slow development wise.)

### Buy me a cup of coffee <3

1LHT8uYsmQW8rCQjx58CJVZLgGxKL5pL89

^ Bitcoin RULZ ALL

### License 

MIT License


