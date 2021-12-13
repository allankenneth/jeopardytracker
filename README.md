# Simple Jeopardy! Score Tracker

Track a small group of people playing Jeopardy! where you can *only add* correctly answered questions (there's no subtraction for missed answers) and the associated dollar values.

https://allankenneth.github.io/jeopardytracker/

Data never leaves your device as all data is stored and processed entirely on the client in vanilla javascript (and PouchDB to manage localstorage). If you dump your cache all the info will be erased. This is just meant to light-heartedly and temporarily track random Jeopardy! games among 3-4 people.

This is a pure and simple HTML file that you can self-host practically anywhere. 
It depends on [PouchDB](https://pouchdb.com) to leverage browser localstorage in an effective way,
while not utilizing any of its synch features.

*You can't share games among the group as tracking is limited to each device.*
*I literally spent 4 hours on this, and only did it for my own usage and how I play Jeopardy! with my family,   so your milage may vary.*

