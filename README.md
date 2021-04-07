# Meme

This is Climate Live's Graphics Generator, which we use to develop quick graphics for socials. It's forked from the LA Times, who forked it from Vox Media. There's been issues with running it in some browsers, especially Safari - we recommend Chrome. You can check the live build at [meme.climatelive.org]

# How to deploy
-------------------------------

**Edit the ``source`` directory to make the changes you want**


You can fire up the test server locally by running:

`bundle install` (if this fails, running `bundle update` before helps)

then `make serve`

**Build the source files into a working static site**

Like so:

`middleman build`

This will create the build on your server. We currently host on Cloudflare pages which works great. 


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
