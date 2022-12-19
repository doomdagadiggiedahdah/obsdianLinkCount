# obsdianLinkCount
Goes through your vault and lists how many links each of your notes have then returns a nice table 

## Setup
Right now you'll have to hardcode the folders you want to have seached and place them in FOLDERS.

If you change MAX_LINKS to "x" you'll be able to see the notes that have up to "x" amount of links.

Set your vault location appropriately and finally you'll end up with a file called "The Unlinked.md" which will be placed in your vault location.

You'll probably need to `chmod +x` the linkCount.sh file, and then you're set \m/

## Todo
* place above setup stuff in a .gitignore file
* remove the .md from the files
* create setup sequence (for storing presets)
* maybe find out how to put this in a plugin for the community store
