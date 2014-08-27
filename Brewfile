# Install command-line tools using Homebrew
# Usage: `brew bundle Brewfile`

# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install some other useful utilities like `sponge`
install moreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed
install findutils
# Install GNU `sed`, overwriting the built-in `sed`
install gnu-sed --default-names
# Install Bash 4
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before running `chsh`.
install bash
install bash-completion

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install vim --override-system-vi
install homebrew/dupes/grep
install homebrew/dupes/screen


# Install other useful binaries
install git
install node
install ghostscript
install redis
install ttfautohint fontforge --with-python

# Install PHP

install php55

curl -s http://php-osx.liip.ch/install.sh | bash -s 5.5

# To have launchd start php55 at login
ln -sfv /usr/local/opt/php55/*.plist ~/Library/LaunchAgents

#Then to load php55 now

launchctl load ~/Library/LaunchAgents/homebrew.mxcl.php55.plist

install mysql

# Install Composer (global)

install homebrew/php/composer
ln -sfv /usr/local/opt/mysql/*.plist ~/Library/LaunchAgents
launchctl load ~/Library/LaunchAgents/homebrew.mxcl.mysql.plist


install homebrew/versions/lua52

# Remove outdated versions from the cellar
cleanup