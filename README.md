Code for Chat app built with React, Redux, Redux-Saga, and web sockets. 

## Note: this app using WebSockets. so the perfect environment to run it is on your local computer.

## Setup:

```
$ git clone <repo url>
$ cd chat/
$ yarn
$ yarn start #this is for run the front-end
$ sudo chmod 0777 ./server/app.js #gives full premmisions to the server
$ npm install --save ws # install again the ws node native module, for sure
$ cd server/
$ node app.js
```

## Open in browser
open ```http://localhost:3000``` or ```http://localhost:8080``` in your favorite browser.
Enjoy Chatting!!!

(note: You can add more users to your chat by opening additional tabs. Each time you open a new tab in the same address, a user will be added to the chat user list, and any message you send from that tab will be recorded under the specific user name.
Real use of this minimal application: In a computer class, in which all computers are connected to the teacher's computer, use this application to send questions.)