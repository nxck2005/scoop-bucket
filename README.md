# scoop-bucket

[Scoop](https://scoop.sh) bucket for [surmise](https://github.com/nxck2005/surmise),
the word game for the terminal.

```sh
scoop bucket add nxck2005 https://github.com/nxck2005/scoop-bucket
scoop install surmise
```

Updates land shortly after each surmise release: a nightly job bumps
`surmise.json`, verifies the new archives' checksums against the release's own
`checksums.txt`, and opens a pull request here. Then, as ever:

```sh
scoop update
scoop update surmise
```
