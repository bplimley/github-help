# github-help
A collection of useful resources for getting up to speed on git and GitHub. Thanks to [Garret Christensen](https://github.com/garretchristensen) for [his talk](https://github.com/garretchristensen/THWGitDemo) at [The Hacker Within at UC Berkeley](http://www.thehackerwithin.org/berkeley/) for some of these resources.

## Tutorials
* Software Carpentry has a good [git tutorial](http://swcarpentry.github.io/git-novice/) for new users.
* Atlassian has [good resources](https://www.atlassian.com/git/tutorials/) too, although note that some of it is based on Bitbucket which is an alternative to GitHub.
* Roger Dudler has a [visually pleasing simple summary](http://rogerdudler.github.io/git-guide/).
* Guides for the GitHub [desktop (GUI) application](https://help.github.com/desktop/guides/).
* [Think Like (a) Git](http://think-like-a-git.net/) by Sam Livingston-Gray is an intermediate tutorial, for if you already know how to make a repo and add commits, but struggle with more complex operations.

## Git commits, branching, workflow
* tpope explains [what a commit message should look like](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
* [git-flow](http://nvie.com/posts/a-successful-git-branching-model/) by Vincent Driessen (1/5/2010) describes a formalized workflow using `master`, `develop`, `release` branch, feature branches, and hotfixes.
* [github-flow](http://scottchacon.com/2011/08/31/github-flow.html) by Scott Chacon (8/31/2011) describes a simpler workflow, using only `master` and feature branches. Continuous integration and GitHub pull requests ensure that features are stable before merging into `master`.

## Cleaning up messes
* [Changing History, or how to Git Pretty](http://justinhileman.info/article/changing-history/) by Justin Hileman (11/?/2011) is a thorough explanation of how to fix whatever went wrong in your commit history, culminating in an [awesome flowchart](http://justinhileman.info/article/git-pretty/). (Also summarized in a [presentation](https://presentate.com/bobthecow/talks/changing-history))
* [The Thing About Git](http://2ndscale.com/rtomayko/2008/the-thing-about-git) by Ryan Tomayko (4/8/2008) gives a good tutorial for `git add --patch`.
