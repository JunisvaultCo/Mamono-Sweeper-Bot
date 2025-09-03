This bot is a very simple and ugly bot that takes screenshots to determine the state of the table and moves the mouse based on some logic.

The bot has an internal system to see if the level has changed but I haven't also saved data about how the level tag should look like. So start it from a game that has level 1 and no monsters hidden.

This bot might be missing some "pattern recognition" at times and will create new files with the text for the pattern and the image so you can see the image and tell it what it is in code (the giant hard-coded bit).


How to use it:
- Open mamono sweeper in a browser with 120% zoom
- python main.py
- quick alt tab to the manono sweeper
- make a few moves if the table is completely clean or unsolveable.

This bot doesn't have a strategy for the first moves but once it gets a few ones or "determineds" it should get going to the very end.
