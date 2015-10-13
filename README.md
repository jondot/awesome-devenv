# Awesome Dev Env [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome tools, resources and workflow tips making an awesome development environment.

Inspired by [awesome-go](https://github.com/avelino/awesome-go), which was in turn inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

[Guidelines](https://github.com/jondot/awesome-devenv/blob/master/CONTRIBUTING.md) tweaked and adapted from `awesome-go` - thanks!

But in short:

* List is alphabetically sorted
* If you think an item shouldn't be here [open an issue](https://github.com/jondot/awesome-devenv/issues/new)


Many thanks to everyone on the [contributor list](https://github.com/jondot/awesome-devenv/graphs/contributors) :)


# Content

_Note: for an OS specific tool, please do your best to mark with `OSX/WIN/*NIX/LIN`_



- [Admins](#admins)
- [Benchmarking](#benchmarking)
- [Data](#data)
- [Diagnostics](#diagnostics)
- [Desktop](#desktop)
- [Dotfiles](#dotfiles)
- [Editors](#editors)
  - [Sublime Text](#sublime)
  - [Vim](#vim)
  - [IntelliJ](#intellij)
- [Git](#git)
- [Presentation](#presentation)
- [Shell](#shell)
- [Text](#text)
- [Terminal](#terminal)
- [Workflow](#workflow)


## Admins
*Tools to manage databases, permissions, etc.*

* [MongoHub](https://github.com/fotonauts/MongoHub-Mac/releases) - Native OSx client for mongo
* [Robomongo](http://robomongo.org/) - a cross platform Admin for MongoDB


## Benchmarking
*Tools to benchmark your code or services*

* [apachebench (ab)](http://httpd.apache.org/docs/2.2/programs/ab.html)
* [boom](https://github.com/rakyll/boom)
* [httperf](http://www.hpl.hp.com/research/linux/httperf/)
* [phantomas](https://github.com/macbre/phantomas) - website perf evaluation tool
* [siege](http://www.joedog.org/siege-home/)
* [Vegeta](https://github.com/tsenart/vegeta)
* [wrk](https://github.com/wg/wrk)
* [redis-faina](https://github.com/Instagram/redis-faina) Instagram's Redis counter/timing stats based on the MONITOR command


## Data
*Tools for handling online and offline data*

* [s3cmd](https://github.com/s3tools/s3cmd) - the S3 CLI tool for Amazon


## Diagnostics
*Tools for checking diagnosing your system while you work*

* [glances](https://github.com/nicolargo/glances)
* [nmon](http://nmon.sourceforge.net/pmwiki.php)


## Desktop
*Tools for improving and hacking around with your vanilla desktop*

* [Alfred](http://www.alfredapp.com/) - OSX productivity app `/OSX/`
* [hydra](https://github.com/sdegutis/hydra) - script your desktop
  `/OSX/`
* [Keycastr](https://github.com/sdeken/keycastr) - show your keys while
  presenting/casting `/OSX/`


## Dotfiles

* [dotfiles.github.io](https://dotfiles.github.io/) - Collected dotfile resources. Has sections with dotfile bootstraps and lists of frameworks for various shells and editors.
* [Zach Holman's](https://github.com/holman/dotfiles) - oh-my-zsh, osx, Zsh, vi, Ruby, Git, and more
* [Mathias Bynens's](https://github.com/mathiasbynens/dotfiles) - .files, including ~/.osx — sensible hacker defaults for OS X
* [Thoughtbot's](https://github.com/thoughtbot/dotfiles) - A set of vim, zsh, git, and tmux configuration files
* [Paul Miller's](https://github.com/paulmillr/dotfiles) - Colourful & robust OS X configuration files and utilities


## Editors
*Only awesome tools and addons for your favorite editor*

### Vim

* [Powerline](https://github.com/Lokaltog/powerline) - improved status bar for your buffers.
* [snipmate](https://github.com/garbas/vim-snipmate) - textual snippets compatiable with Textmate snippets.
* [The Ultimate Vim Distribution](http://vim.spf13.com/) - spf13-vim is a distribution of vim plugins and resources for Vim, GVim and MacVim.

### Sublime Text 3

* [AdvancedNewFile](https://github.com/skuroda/Sublime-AdvancedNewFile) - File creation plugin.
* [Emmet](https://github.com/sergeche/emmet-sublime)
* [Git Gutter](https://github.com/jisaacks/GitGutter) - display changed/added lines in the margin of the editor window.
* [jsFormat](https://github.com/jdc0589/JsFormat) - Javascript formatting.
* [LiveReload](https://github.com/dz0ny/LiveReload-sublimetext2) - LiveReload plugin.
* [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing) - Markdown syntax understanding and good color schemes.
* [Package Control](https://sublime.wbond.net/installation) - The Sublime Text package manager.
* [RubyTest](https://github.com/maltize/sublime-text-2-ruby-tests) - Plugin for running Ruby tests.
* [Side Bar Enhancments](https://github.com/titoBouzout/SideBarEnhancements) - Enhancements to Sublime Text sidebar. Files and folders.
* [Sublime Git](https://github.com/kemayo/sublime-text-git) - Git Integration for Sublime.
* [Sublime Linter](https://github.com/SublimeLinter/SublimeLinter3/) - Interactive code linting.
* [TrailingSpaces](https://github.com/SublimeText/TrailingSpaces) - Highlight trailing spaces and delete them in a flash.

### Intellij

* [keymap](https://github.com/jondot/keymaps/) - a hybrid Vim/ReSharper/Intellij keymap


## Git
*Tools and addons for making an awesome Git experience*

* [awesome-github](https://github.com/fffaraz/awesome-github) - Faraz Fallahi maintains a curated list of GitHub & Git resources.
* [gh](https://github.com/jingweno/gh) - Fast GitHub command line client (hub port to Go)
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - collected git helper scripts
* [git-extras](https://github.com/visionmedia/git-extras) - GIT utilities -- repo summary, repl, changelog population, author commit percentages and more
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - ZSH plugin, adds a gitit command that opens the current directory on github in your current branch
* [git-semver](https://github.com/markchalloner/git-semver) - A git plugin to make Semantic Versioning 2.0.0 and Change Log management easier.
* [git-sweep](https://github.com/arc90/git-sweep) - safely removes branches that have been merged into the master
* [git-up](https://github.com/aanand/git-up) - a better 'git pull'
* [hub](https://hub.github.com/) - git CLI wrapper which makes working with GitHub easier
* [scm_breeze](https://github.com/ndbroadbent/scm_breeze) Streamline your git workflow


## Presentation
*Tools for presenting your work*

* [bespoke.js](https://github.com/markdalgleish/bespoke.js) - DIY Presentation Micro-Framework
* [impress.js](https://github.com/impress/impress.js) - presentation framework based on the power of CSS3 transforms and transitions
* [remark](https://github.com/gnab/remark) - markdown based presentation on your browser
* [reveal.js](https://github.com/hakimel/reveal.js/) - markdown based presentation on your browser
* [deck.js](https://github.com/imakewebthings/deck.js) - markdown based presentation on your browser
* [vimdeck](https://github.com/tybenz/vimdeck) - present inside your Vim


## Shell
*Tools for having an awesome shell environment*

* [awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) - List of zsh plugins usable with [zgen](https://github.com/tarjoilija/zgen) and other [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/) compatible zsh frameworks
* [fish-shell](https://github.com/fish-shell/fish-shell) - The user-friendly command line shell
* [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) - Framework for managing your fish shell configuration inspired by oh-my-zsh.
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/) - A community driven framework for managing zsh configuration.
* [zgen](https://github.com/tarjoilija/zgen) - Faster framework for managing your zsh configuration, backward compatible with oh-my-zsh plugins
* [zsh](http://www.zsh.org/) - A shell designed for interactive use, although it is also a powerful scripting language.
* [shellcheck](https://github.com/koalaman/shellcheck) - Lint for shell. Will find deprecated and/or dangerous usage in shell scripts
* [zsh quickstart kit](https://github.com/unixorn/zsh-quickstart-kit) - Quick intro for getting set up with zsh and zgen

## Text
*Tools for working with text files - search, replace, processing*

* [ack](https://github.com/petdance/ack2) - the Perl based
  better-than-grep tool.
* [ag](https://github.com/ggreer/the_silver_searcher) - A C based code-searching tool similar to ack, but faster
* [peco](https://github.com/peco/peco) - interactive filtering, like interactive Grep


## Terminal
*Tools and addons for terminal and terminal work*

* [autojump](https://github.com/joelthelion/autojump) - remembers your
  folders and jump to them based on partial recall (e.g. `j proj` will jump
to `/home/Users/yourself/projects`.
* [fasd](https://github.com/clvv/fasd) Command-line productivity booster, offers quick access to files and directories.
* [homebrew](http://brew.sh) - Makes it easy to install open source packages on an `OS X` system with a single command.
* [httpie](http://httpie.org/) A command line HTTP client, a user-friendly cURL replacement.
* [iTerm2](http://www.iterm2.com/) - a great terminal replacement `/OSX/`
* [jq](https://stedolan.github.io/jq/) - a lightweight and flexible command-line JSON processor
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) - the
  incredible ZSH addon.
* [Pipe Viewer](http://www.ivarch.com/programs/pv.shtml) - a tool for monitoring the progress of data through a pipeline
* [tmux](http://tmux.sourceforge.net/) the awesome terminal multiplexer.


## Workflow
*Tools and addons which improve your daily workflow with code*

* [fswatch](https://github.com/alandipert/fswatch) - a watch tool which
  will emit FS events and you can run commands on demand with. Note -
`fswatch-run` too.
* [guard](https://github.com/guard/guard) - FS watch tool with a huge ecosystem of plugins
* [LiveReload](http://livereload.com/) - FS watch and preprocessor as a desktop app for `/OSX/` and `/WIN/` with complementary browser extensions
  * [guard-livereload](https://github.com/guard/guard-livereload) - Guard plugin compatible with LiveReload's browser extensions
* [watchman](https://github.com/facebook/watchman) - Facebook's better
  `watch` - note it works as a service.
