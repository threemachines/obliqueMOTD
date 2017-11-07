##`fortune`-formatted Oblique Strategies

This is a `strfile`-formatted set of Brian Eno and Peter Schmidt's Oblique Strategies, ready for use with the `fortune` utility. I've also included Richard Diebenkorn's (much shorter) "notes to myself on beginning a painting".

Suggested usage is to install the `fortune` command via homebrew and put something like the following in your `~/.bash_profile` or similar:
```
echo "Today's oblique strategy:"
fortune ~/obliqueMOTD/obliquestrategies ~/obliqueMOTD/diebenkorn_notes
echo ''
```

Contributions or fixes are welcome; just make sure to rerun `strfile` after any changes to the text files.

Known issues: some of the strategies were originally formatted multiline and were condensed somewhere along the way. `strfile` can handle multiline just fine, so those should be reformatted.

Totally untested on anything except the `fortune` I got from homebrew this morning. No license because none of this stuff is mine in the first place. My thanks to https://github.com/amonks/oblique-strategies-api for getting the strategies in plaintext to start.
