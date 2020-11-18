# codereddit-securly-safe
Original code reddit code can be found here: https://github.com/codereddit/codereddit.    

## Description
As of currently, securly blocks reddit.com which is nessesary for code reddit to actually work. However, securly doesn't block en.reddit.com. This allowed me to change the main ```codereddit.js``` file and replace the reddit urls with en.reddit urls. The main work is done in ```renderpage()``` and the original urls are commented out and replaced with the new ones. This exploit won't work if en.reddit.com is blocked. Just run the index.html file and you're good!

## Important!
Because google chrome is dumb, you need to run google chrome with the `--allow-file-access-from-files` flag in order for this to work. This can be done through terminal with the following line input to terminal:   
```
open -a Google\ Chrome --args --allow-file-access-from-files
```
