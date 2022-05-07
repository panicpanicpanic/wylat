# Quickly switch to your last branch

Ever find yourself constantly going back and forth between branches?
Here's a small hack `git` hack that allows you to quickly switch between branches:

`git checkout -`

Example:

We'll first check out to `main`
```sh
$ ~ git checkout main
```

Then, we'll check out to a feature branch
```sh
$ ~ git checkout -b "feature/new-feature"
```

Now, for some `git` magic:
```sh
$ ~ git checkout -
$ ~ git status
On branch main
```

Back to `main` branch!

