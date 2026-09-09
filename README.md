# Transfer Stash

One person's Grim Dawn transfer stash, rendered as the game itself prints it,
published at **https://dereksswong.github.io/gd-stash-site/**

Every card is a real stash item with the game's own tooltip lines, its own colour
codes, and the trigger condition on any skill it grants. Search, chip filters and
a Mastery filter sit above them.

## This repo is output, not source

`index.html` is generated — **never hand-edit it**. It is built by a separate
private pipeline from an Item Assistant export plus a local extraction of the
game database (~77k files) that cannot live in a repo. Regenerate and redeploy
from there; an edit made here is lost on the next build.

The page carries `robots: noindex` and is not meant to be found by search. A
Pages site is readable by anyone with the link regardless of repo visibility.

Item names, stats and flavor text are the property of Crate Entertainment.
