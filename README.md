# Caption Tweets

## Summary

This is a prototype of visualising if each soap opera character has its own account and tweet their dialogues


## Mockup design

<img src="https://lh5.googleusercontent.com/-vEwZRTjj6V0/UaEodQw8WOI/AAAAAAAADH8/l42rYqUaf4U/w962-h712-no/Screen+Shot+2013-05-25+at+22.07.24.png
" alt="Mockup" width="500px">

## Current state of design :-(

<img src="https://lh5.googleusercontent.com/-NiT0iciSVUw/UaEpc2mkA_I/AAAAAAAADII/on5V_DLDvL4/w993-h712-no/Screen+Shot+2013-05-25+at+22.12.50.png" alt="Current" width="500px">

## How to run this site.

Since it does ajax load json file, you need to startup server.

eg: Python

    python -m SimpleHTTPServer

eg: Thin

    thin -A file start -p 8000

## Note.

The video is currently dummy video


## Todo

- When the family circles are clicked, show list of popular tweets on "Family tweets" section.
- When a character is speaking, highlight the character circle.
- As more people fav/rt/mentions, increase the size of circles.


## Completed.

- When a character is speaking, update his/her current dialogue at "Current Tweet"
