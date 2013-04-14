% Auto-Complete - An Intelligent auto-completion extension for Emacs

[![Build Status](https://secure.travis-ci.org/auto-complete/auto-complete.png)](http://travis-ci.org/auto-complete/auto-complete)

# What is Auto-Complete?

Auto-Complete is an intelligent auto-completion extension for
Emacs. It extends the standard Emacs completion interface and provides
an environment that allows users to concentrate more on their own
work.

# Features

* Visual interface
* Reduce overhead of completion by using statistic method
* Extensibility

# Screenshots

![](doc/ac.png "Auto Completion")

![](doc/ac-fuzzy.png "Fuzzy Completion")

![](doc/ac-isearch.png "Increamental Search")

# Demo Video

* [YouTube](http://www.youtube.com/watch?v=rGVVnDxwJYE)

# Install

First clone `auto-complete` into the `tmp` folder:

```
$ cd /tmp
$ git clone https://github.com/auto-complete/auto-complete
```

In Emacs, execute the following:

```
M-x load-file
```

and load `/tmp/auto-complete/etc/install.el`.

The installation process finally asks you to copy the following in your `.emacs` file:

```
(require 'auto-complete-config)
(ac-config-default)
```

`eval-buffer` or restart Emacs, and that’s it!

# User Manual

[Auto-Complete User Manual](doc/manual.html)

# Development

* <http://github.com/auto-complete/auto-complete>

# Reporting Bugs

Visit
[Auto-Complete Issue Tracker](https://github.com/auto-complete/auto-complete/issues)
and create a new issue.

License
-------

This software is distributed under the term of GPLv3.
