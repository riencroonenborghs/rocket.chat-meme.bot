# memebot

*meme.bot* is a rocket.chat bot for generating memes.
It's written in Ruby/Sinatra.

# Get it up and running

- # TODO write how to set up an outgoing + incoming hook in rocket.chat
- sign up at [ImgFlip](https://imgflip.com/signup)
- deploy *meme.bot* somewhere and make sure the outgoing + incoming hooks (_INCOMING_HOOK_URL_ and _OUTGOING_HOOK_URL_) + ImgFlip's username/password (_IMGFLIP_USERNAME/IMGFLIP_PASSWORD_) are available in the environment (.env or something)

# How to

`!meme help` 


`!meme list` 
Returns a list of the top 10 meme and a link to a longer list.

`!meme Meme Name Goes Here: caption line 1 [| caption line 2]`
Generates the meme with your captions.
