# Secrets---Starting-Code
You can register and login in different ways like if you want to login with your email and password or if you want to login with google it remembers sessions and cookies So that you can seamlessly switch tabs and still the user remain login 
while creating this project i learnt about different levels of security 
First i implemented it using normal password and email
level 2 : using Encryption using this module const encrypt = require("mongoose-encryption")
level 3: LEVEL 3 USING HASHING PASSWORDS then salting  so that if no encryption key no way to go back and find the actual person  const md5 = require("md5");
level 4: cookies and sessions  -> cookies store data of previous sessions and why we are logined to a site when we come bac and why the item is still added to a cart when we come back if we delete cookies these things will go out 
using passport.js to add cookies and session with 3 routes login signup and register

Level 5: we need not to take tension of the security if we handle it to google or facebook like sign in with google 
with oauth you can ask for a particular data from eg google like only user name or password or if we are making tinder like application awe also want friendlit from facebook or contacts using oauth we can do that
DOCUMENTATION  https://www.passportjs.org/packages/passport-google-oauth20/
$ npm install passport-google-oauth20
https://console.developers.google.com/
