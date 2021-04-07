# Meme

This is Climate Live's Graphics Generator, which we use to develop quick graphics for socials. It's forked from the LA Times, who forked it from Vox Media. It's still a work in progress, though it's functional right now. Theres been issues with running it in some browsers, especially safari - we recommend Chrome.

# How to deploy
-------------------------------

**Edit the ``source`` directory to make the changes you want**


You can fire up the test server locally by running:

`bundle install` (if this fails, running `bundle update` before helps)

then `make serve`

**Build the source files into a working static site**

Like so:


`make build`


**Commit your work**

Use Git to commit your work to our repository.

```bash
# Add the changes
$ git add .
# Log your work
$ git commit -m "A precise message goes here"
# Push it up to GitHub
$ git push origin master
```
