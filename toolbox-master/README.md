# ReadMe

This doc is to explain the repo.

I created a series of tools for post-production and pre-compilation of front end assets like HTML, JS and CSS.

 - miniHTML uglifies HTML and adds `alt` to `img` tags for compliance.
 - prettyHTML formats HTML to be indented and readable.
 - miniJS uglifies JS.
 - miniCSS uglifies CSS.
 - sass runs SASS.


## How to use!

For the new coder:
1) install NodeJS
2) download this repo to your computer
3) get a command prompt in the root of this folder
4) type `npm i` and it will install all the stuff you will need in that folder
5) type `gulp` and you should see a confirmation that it works
6) type `gulp --tasks` and it will tell you all the tasks in the file, when you see one you want, you'll type `gulp taskName` and it will run that task.
7) place the files you want to work with in a sub folder and open gulpfile.js and look at the comments next to the tasks. *Choose a source and destination*. :warning: They can be the same, but I am not that bold/foolhearty.

:date: Updated 28 Feb 2018
