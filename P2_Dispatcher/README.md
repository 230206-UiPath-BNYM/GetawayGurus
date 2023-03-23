## The Dispatcher ##

This dispatcher takes Excel sheets from a given email, saves them locally, and then sends them to the queue. After completing the batch, it cleans up the local files and creates an empty working folder for the next dispatch process. Sweet!

The Excel sheets need to be formatted properly according to a template in the root project folder.
