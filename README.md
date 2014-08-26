# Alex's .dotfiles

## Installation

### Using Git and the setup script

You can clone the repository wherever you want. (I like to keep it in ~/Projects/dotfiles, with ~/dotfiles as a symlink.) The setup script will pull in the latest version and copy the files to your home folder.

```bash
git clone https://github.com/alexandrebroudin/dotfiles.git && cd dotfiles && source setup.sh
```

To update, `cd` into your local `dotfiles` repository and then:

```bash
source setup.sh
```

```bash
# Git credentials
# Not in the repository, to prevent people from accidentally committing under my name
GIT_AUTHOR_NAME="Alexandre Broudin"
GIT_COMMITTER_NAME="$GIT_AUTHOR_NAME"
git config --global user.name "$GIT_AUTHOR_NAME"
GIT_AUTHOR_EMAIL="alexandrebroudin@mailinator.com"
GIT_COMMITTER_EMAIL="$GIT_AUTHOR_EMAIL"
git config --global user.email "$GIT_AUTHOR_EMAIL"
```

### Install Homebrew formulae

When setting up a new Mac, you may want to install some common [Homebrew](http://brew.sh/) formulae:

```bash
brew bundle ~/Brewfile
```

### Install native apps with `brew cask`

You could also install native apps with [`brew cask`](https://github.com/phinze/homebrew-cask):

```bash
brew bundle ~/Caskfile
```

## Thanks to…

* [Mathias Bynens](https://mathiasbynens.be/)
* [Maxime Thirouin](http://moox.io)