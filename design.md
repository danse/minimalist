```
$ minima-add single line text
$ minima-block
writing here
i can go on a new line
$ minima-select file # any name except `unselected`
$ minima-edit
```

Minimalist will commit after every command. The commit does not need
to have a meaning, since we are rather interested in the metadata.

The folder is `~/minima`. Those are called "minima files" and are
supposed to be shared in a repo called `minima`. "Minima" designates
the structure, while Minimalist is the name of this particular client
for creating them.

Minima files do not need any client in order to be produced, they can
easily be produced manually. A suggestion for the commit message is to
use `git commit -am $(date -Iseconds)`.

