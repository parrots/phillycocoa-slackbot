## Hubot scripts for rOpenSci

* Add any new scripts and commit to the `scripts` folder
* Then push here, followed by `git push heroku master` (assuming you have access to that remote)
* `heroku ps:scale web=1`

__Some slackbot commands that work in public rooms__

```coffee
applause|applaud|bravo|slow clap - Get applause
brb (or afk, or bbl)
debug - {user: <user object to send message to>}
slackbot <user> doesn't have <role> role - Removes a role from a user
slackbot <user> has <role> role - Assigns a role to a user
slackbot <user> is a badass guitarist - assign a role to a user
slackbot <user> is not a badass guitarist - remove a role from a user
slackbot animate me <query> - The same thing as `image me`, except adds a few parameters to try to return an animated GIF instead.
slackbot announce "<message>" - Sends a message to all slackbot rooms.
slackbot announce downtime complete for "<service>" - Syntactic sugar for announcing downtime completion
slackbot announce downtime for "<service>" starting <timeframe> - Syntactic sugar for announcing downtime commencement
slackbot die - End slackbot process
slackbot echo <text> - Reply back with <text>
slackbot fake event <event> - Triggers the <event> event for debugging reasons
slackbot help - Displays all of the help commands that slackbot knows about.
slackbot help <query> - Displays all help commands that match <query>.
slackbot i am <available|free|not busy|at hand> - Set that you are available
slackbot i am <unavailable|dnd|do not disturb|busy|in the zone> - Setthat you are not available
slackbot image me <query> - The Original. Queries Google Images for <query> and returns a random top result.
slackbot is <user> available - Find out if the specified user is available or not
slackbot map me <query> - Returns a map view of the area returned by `query`.
slackbot mustache me <query> - Searches Google Images for the specified query and mustaches it.
slackbot mustache me <url> - Adds a mustache to the specified URL.
slackbot ping - Reply with pong
slackbot pug bomb N - get N pugs
slackbot pug me - Receive a pug
slackbot show storage - Display the contents that are persisted in the brain
slackbot show users - Display all users that slackbot knows about
slackbot the rules - Make sure slackbot still knows the rules.
slackbot time - Reply with current time
slackbot translate me <phrase> - Searches for a translation for the <phrase> and then prints that bad boy out.
slackbot translate me from <source> into <target> <phrase> - Translates <phrase> from <source> into <target>. Both <source> and <target> are optional
slackbot weather - Get the weather for slackbot_DARK_SKY_DEFAULT_LOCATION
slackbot weather <location> - Get the weather for <location>
slackbot what role does <user> have - Find out what roles are assigned to a specific user
slackbot who has admin role - Find out who's an admin and can assign roles
slackbot who is <user> - see what roles a user has
slackbot youtube me <query> - Searches YouTube for the query and returns the video embed link.
sarcastic applause|clap - Get sarcastic applause
ship it - Display a motivation squirrel
```

You can also run `slackbot help` in any room to get a more up to date list.


