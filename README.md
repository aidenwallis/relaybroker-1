# relaybroker [![Build Status](https://travis-ci.org/gempir/relaybroker.svg?branch=master)](https://travis-ci.org/gempir/relaybroker)

#### What is this?
relaybroker is a piece of software that is supposed to act as a proxy between your bot and twitch.tv irc servers. 
It will handle ratelimiting so you don't have to worry about getting global banned or having connection issues.

#### How to use 
Setup a password and a port in the config.go file and compile the program. 
In your bot you need to modify your oauth key like this:

    mypassword;oauth:4614317321asaf13241 

just add your password you setup earlier to the front and add a between the oauth key and the password.
Change your bot's server you want to connect to and port to the server relaybroker is running on and the port you wanted to use.

That's it! Now you can connect to relaybroker normally and don't have to worry about ratelimits or connection issues
