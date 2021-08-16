
## Enhancement One



The artifact is the Jukebox app from CS 320.  I took and added a search functionality to the jukebox app that will query Wikipedia with the title of the song so that you can see more information about it.   

I chose this artifact because it shows my ability to work collaboratively on a group project and use GIT effectively to branch, write my code, and merge it to master.  Additionally the search functionality shows the ability to create an app that can interface with outside data such as JSON objects.  

The ran into an issue with the Wikipedia API requiring a license, so the workaround I used was to create a runtime object, pass that object the windows specific browser executable, and the URL.  Then the program will open that URL in the default browser on the system.  

This creates some interesting problems, first wikipedia doesn't always link to the correct wiki page.  This can result in some unexpected results when the tab is opened in the browser, such as the wiki page for the color yellow popping up rather than the coldplay song.  It can also display a list of possible links although I wasn't able to access a list of links every time due to the limitations of what I was able to accomplish without the license.

[Enhancement 1 Repository](https://github.com/fastgunner/Jukebox)

[Main Page](https://fastgunner.github.io/index.html)
