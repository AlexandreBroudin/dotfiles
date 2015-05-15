# Install GNU core utilities (those that come with OS X are outdated).
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
brew 'coreutils'

# Install some other useful utilities like `sponge`.
brew 'moreutils'

# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed.
brew 'findutils'

# Install GNU `sed`, overwriting the built-in `sed`.
brew 'gnu-sed', args: ['with-default-names']

# Install Bash 4.
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before
# running `chsh`.
brew 'bash'
tap 'homebrew/versions'
brew 'bash-completion2'

# Install `wget` with IRI support.
brew 'wget', args: ['with-iri']

# Install more recent versions of some OS X tools.
brew 'vim', args: ['override-system-vi']
brew 'grep'
brew 'openssh'
brew 'screen'
brew 'php55', args: ['with-gmp']

# Install font tools.
tap 'bramstein/webfonttools'
brew 'sfnt2woff'
brew 'sfnt2woff-zopfli'
brew 'woff2'

# Install other useful binaries.
brew 'git'
brew 'node'
brew 'tree'

# Install native apps

brew 'caskroom/cask/brew-cask'
tap 'caskroom/versions'

cask 'iterm2'

cask 'google-chrome-canary'

cask 'firefoxdeveloperedition'

cask 'imagealpha'
cask 'imageoptim'

cask 'sublime-text3'
cask 'atom'

cask 'the-unarchiver'
cask 'unrarx'
cask 'virtualbox'
cask 'sequel-pro'
cask 'spectacle'
cask 'cloud'
cask 'xscope'
cask 'flux'

cask 'sketch'
cask 'sketch-tool'

cask 'xquartz'
