# GitGood-Fetch-EasyMode

For starters, this is the simplest and cleanest case of `git fetch` you'll likely ever see - while it's not practical, it is nice to ease into what `git fetch` is doing, and how we interact with it before we get to some more "interesting" cases!

## Step 1 - Fork this repo! 🍴

At this point, you'll hopefully know how to fork, but if not you can check out [this](https://github.com/chris-alexiuk/GitGood-Forking) repo!

## Step 2 - Clone the fork! 🧑‍🤝‍🧑

That's right, we'll be [cloning](https://github.com/chris-alexiuk/GitGood-Cloning) our fork to our local!

## Step 3 - Make a remote change! ⚒️

It can be as simple as editing the README.md, as long as you make - and then commit a change on the remote repository!

## Step 4 - It's time to fetch! 🦴

It's as easy as `git fetch` in the command line of your local repository - and away you go!

## Step 5 - Review and merge!

Now that we have made our remote changes, we can use the following flow to update our local repository:

  1. `git fetch origin` to fetch any updates from our origin.
  2. `git log origin/main` to check the git log of our remote changes. 
  3. `git switch main` to make sure we're on the right branch (this can be any branch you wish to merge the pulled changes to)
  4. `git merge origin/main` - this will do the merge and let us have our fully updated `origin/main` branch in our local repo!

## Step 6 - Celebrate! 🎉
