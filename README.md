googleformtofusion
==================

A Google Apps script to get data from a Google form and post it to a Fusion table.

This is built off a script written in early 2012 by Kathryn Hurley at Google because the functionality didn't exist
to link results from a Google Form with a Fusion Table. Here's her script: 

http://kh-samples.googlecode.com/svn/trunk/code/appsscript.js

Google Forms automatically creates a Google spreadsheet with all responses, and you can make a Fusion Table
from a spreadsheet, but you can't yet (easily) manipulate Google Form results in a Fusion Table. 

I'm modifying Kathryn's code for the new Google API requirements. 

Also, I'm modifying it to allow editing in the Fusion Table. As it was written, it synced the Fusion Table with
the Form spreadsheet, so if you made changes on the fusion table, they'd be wiped out eventually. I want the
functionality of collecting a bunch of responses with Google Forms, and then being able to modify them
(and make notes on them, especially in Fusion Card view). 

Also, this is my first github thing. 

Note: After Kathryn wrote this script, a few others collaborated on a different script that does much of the
same thing. It definitely works well and is very well documented, but like Kathryn's script, it 'syncs'
the Fusion Table with the spreadsheet by deleting the whole Fusion Table and re-importing the
spreadsheet. So if you make notes on the Fusion Table, those are deleted. If you don't anticipate modifying
anything on the Fusion Table data, I highly recommend using their script.

John McGrath and Chris Keller's code is here:

https://gist.github.com/chrislkeller/3013360

And the walkthrough is here: 

http://blog.chrislkeller.com/google-group-user-john-m-posts-script-that-br/
