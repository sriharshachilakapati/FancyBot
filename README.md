FancyBot
========

My fancy IRC bot written in Javascript for NodeJS.

Features so far:
- !help
  - prints this list of commands
- !ping
  - responds with pong
- !notify nick message
  - notifies the user with message upon activity
- !calc expression
  - executes the expression and prints the result
- !exec code
  - op-only feature: executes javascript code and prints the output
- !notitle URL
  - op-only feature: adds the domain name of the URL to the blacklist for title grabbing
- !lastseen nick
  - prints how long ago the user was seend and their last message
- !convert value fromUnit to toUnit
  - converts the value from the fromUnit to toUnit
- !eightball question
  - returns a magic response to a yes/no question
