<div align="center">
	<a href="https://github.com/prafaelo/refresh-git">
		<img src="./assets/refresh-mind-icon.svg"
			 alt="Refresh Git Icon">
	</a>
	<h1>REFRESH GIT :octocat:</h1>
	<a href="https://github.com/prafaelo/refresh-git">
		<img src="https://img.shields.io/static/v1?label=🤹&message=refresh-git&color=blue&labelColor=green"
			 alt="Travis Build Status">
	</a>
	<a href="https://github.com/ahmadawais/Emoji-Log/" >
		<img src="https://cdn.rawgit.com/ahmadawais/stuff/ca97874/emoji-log/flat-round.svg" 
		     alt="emoji-log">
	</a>
	<a href="https://travis-ci.org/prafaelo/refresh-git">
		<img src="https://img.shields.io/travis/prafaelo/refresh-git.svg?&logo=travis&style=flat"
			 alt="Travis Build Status">
	</a>	  
    <h3>Refresh your mind about everything about Git<h3>
</div>

---

# About
This cheat sheet summarizes everything useful commonly used Git and GitHub for quick reference.

# Install
- GUI: [Github desktop](https://github.com/desktop/desktop) 

# Commands

## Configure:

This is used to identify the commits you create:

`$ git config --global user.name "[User Name]"`

`$ git config --global user.email "[e-mail]"`

> Tip: Not necessary if you will use GitHub Desktop.


## Make Changes

<div align="center" >
    <p> File Status Lifecycle <p/>
    <a href="https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository">
	    <img width="50%" height="%50" src="https://git-scm.com/book/en/v2/images/lifecycle.png" alt="File Status Lifecycle">
    </a>
</div>

Shows the status of changes as untracked, modified, or staged:

`$ git status`

List all remote and local branches:

`$ git branch -a`

Tells Git what files will be committed. It's necessary make it before of the `$ git commit` command:

`$ git add [file-1] [file-2] [...] [file-n]`

Add changes from all tracked and untracked file (new file, modified file and deleted file):

`$ git add -A`
> Tip: Use this in almost all cases. [Find out more](https://stackoverflow.com/questions/572549/difference-between-git-add-a-and-git-add).

Add changes from only tracked files (modified file and deleted file):

`$ git add -u`
> Tip: This is useful when the new files are temporary and still not are in .gitignore. For example: log files.

Record changes to the local repository:

`$ git commit -m "[summary message]" -m "[description message]"`
> Tip: You can add many description messages, for example: `$ git commit -m "Summary" -m "msg 1" -m "msg 2" -m "msg 3"`, etc.

Unstages the file, but preserve its contents:
`$ git reset <file>`
> Tip: use only `$ git reset` for reset all files.

Discard changes in working directory

`$ git checkout <file>`

# Troubleshooting
- Git push results in “Authentication Failed”:
> When you're using two-factor authentication you a personal access token is required to authenticate to GitHub over HTTPS with Git on the command line or the API. [Find out more](https://help.github.com/en/articles/creating-a-personal-access-token-for-the-command-line).

# Commit Message Guidelines
- [Gitmoji - Emoji guide for commit messages](https://gitmoji.carloscuesta.me/)
- [Emoji Log - Emoji Git commit messages spec standard](https://github.com/ahmadawais/Emoji-Log/)
- [Angula commit message guideline](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit) 

# Repository Management
- [Dynamic badges for open source projects](https://shields.io/)
- [Documentation for the open source community](https://github.com/readthedocs/)
- [Code Coverage](https://codecov.io/)

# Tricks
- [GitHub Searching code](https://help.github.com/en/articles/searching-code)
- [A curated list of GitHub's awesomeness](https://github.com/phillipadsmith/awesome-github)

# Git Code Management
List of alternatives source/git code management
- [github.com](github.com)
- [bitbucket.org](bitbucket.org)
- [gitlab.com](gitlab.com)

# References
- [GitHub - Git basic handbook](https://guides.github.com/introduction/git-handbook/#basic-git)
- [GitHub - Git cheat sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
- [Git site](https://git-scm.com/)
- [Book: Git Pro](https://github.com/progit/progit2)
