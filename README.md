# :fire: `gh fire`

`gh fire` is a GitHub CLI extention that **helps in the event of an emergency** by switching to the repository's root directory, adding all current files, committing, and pushing commits and all stashes to a new branch. Yes, it's a [`git-fire`](https://github.com/qw3rtman/git-fire) clone.

## What It Does

- changes directory to root directory of the repository
- creates new branch `fire-<current branch>-<seconds since epoch>`
- adds all files
- commits with `"Fire! <new branch name>"` or custom message
- pushes commits to remote
- pushes all stashes to remote

## Usage

`gh fire <message>`

`<message>` is optional. If not specified, `"Fire! fire-<current branch>-<seconds since epoch>"` will be used.

## Installation

Make sure you have [`gh`](https://github.com/cli/cli) and [`git`](https://git-scm.com/) installed.

Then run

```sh
gh extension install maximousblk/gh-fire
```

## Disclaimer

Your life is always more valuable than any code. You should leave the building immediately in a true emergency.

Code can be re-written, but humans cannot.

## Credit

Originally created by [qw3rtman](https://github.com/qw3rtman/git-fire)

## License

This code is licensed under [The MIT License](./LICENSE).
