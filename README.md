# Git Quick Reference

## Getting set up - commands you probably only need to run once.

* `git config --global http.sslVerify false`

* `git config --global credential.helper wincred`

* `git config --global user.name "YOUR NAME"`

* `git config --global user.email "YOUR E-MAIL ADDRESS"`

## The most common Git (and GitHub) commands that we use.

* `git pull` - fetch the contents of the _upstream_ repository and merge changes into your local copy of the repository.

* `git status` - see what has changed in this repository.

* `git add FILE_OR_DIRECTORY` - stage changes to FILE_OR_DIRECTORY for a later commit.

* `git commit -m "DESCRIPTION OF CHANGES" - commit (make permenant) your changes in the local version of the repository.

* `git push` - upload your commit(s) to GitHub.

### Putting it all together:

A typical work session might start out like this:

```bash
cd /folder/where/your/project/is
git pull
```

Followed by some work in Unity and/or Rider. Finally when you're done, you would wrap up with:

```bash
git status
git add FILE_OR_DIRECTORY
git commit -m "Working on bug #1."
git push
```
## Collaborating

<details>
  <summary>
    [Configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)
  </summary>
</details>

<details>
  <summary>
    [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
  </summary>
</details>
