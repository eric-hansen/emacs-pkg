# emacs-pkg

## What is this?
Emacs doesn't have a user-friendly way to install a package if it doesn't exist without user intervention.  This is quite the annoyance when you want to share your Emacs config with more than one machine or with another person.

## How to install
Right now you will have to clone this project to your Emacs directory (i.e.: ~/.emacs.d) like most packages.  However, this will be fetchable from MELPA soon.

## How to use
Whenever you decide to `require` a package, just call `pkg` intead.  This will do all the magic necessary.  So if you want to include a package called foo-bar, instead of doing `(require 'foo-bar)` just do `(pkg foo-bar)`.