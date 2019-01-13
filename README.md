# Simple GMod Loading Screen

## About

I got tired of all these "welcome to my server, here's a thousand things to read" loading screens, so I created a minimal screen for my server.

This doesn't have all the bells and whistles of "you're on your way to \<host\>, playing \<map\>!" with music playing in the background. It's just a spinner and some text that changes. Very reminicent of GMod 10's default loading screen.

## Installation

* Clone this repo onto your webserver somewhere 
* Edit `phrases.json` to include all the phrases you'd like to display to your user
* In you server's `server.cfg`, modify `sv_loadingurl` to point to this page.
