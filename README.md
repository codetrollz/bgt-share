# bgt-share

A static page for Board Game Tracker share links: `https://codetrollz.github.io/bgt-share/#g=<code>` (game), `#p=<code>` (play), `#f=<code>` (follow a shelf) or `#i=<code>` (join a group).

The page reads the code from the part after `#` (never sent to a server) and opens the app with `boardgametracker://game?d=<code>`, `://play?d=`, `://follow?d=` or `://group?d=`. It stores nothing and has no analytics.
