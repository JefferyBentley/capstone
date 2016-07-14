# capstone
## Running Notes
The program Running Notes has 2 models inside the Django SQL database. They are Users and Notes. The Notes model contains fields named user, created, modified and note respectively. 
The notes template uses these fields and iterates over them for each new note with the attributes named note.user, note.created, note.modified and note.note respectively.

The views.py file has the notes function which takes request as the argument and return renders notes.html dictionary key "notes":. A regular expression for notes was added to the url patterns array to so that notes could be imported to the notes.html page. 

reformatting of the template to add text container segment, text alignment and search bar using Semantic UI styling. 
