# commitground.org
Commitground webpage repository

# Branch history
Current
- [white](/tree/white) : 2018-06-18
History
- [white](/tree/white) : 2018-06-18

# How to contribute

We may change our web page continuously with some minor changes and also the major changes. So here's the branch policy.

1. When you make a new major change, please make a new branch. You can name the branch as anything you want.
2. Please make a [new issue] with "Change branch"
3. If your suggestion is accepted, `gh-pages` branch will designate the new branch. Following commands will be executed by CI tool or organization member. Keep in mind that `gh-pages` exists only to designate the current page branch.
```
git branch -D gh-pages
git checkout -b gh-pages origin/[your-branch]
git push origin gh-pages --force
```
4. Minor changes to the branch will be automatically integrated into the `gh-pages` branch by Travis CI.


# Built with Jekyll
Followed [Jekyll's quick start guide](https://jekyllrb.com/docs/quickstart/)
