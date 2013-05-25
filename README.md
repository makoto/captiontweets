# Caption Tweets

## Summary

This is a prototype of visualising if each soap opera character has its own account and tweet their dialogues

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
- When a character is speaking, update his/her current dialogue at "Current Tweet"
- When a character is speaking, highlight the character circle.
- As more people fav/rt/mentions, increase the size of circles.