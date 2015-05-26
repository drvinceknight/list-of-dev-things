# List of things to learn

A repository containing lists of concepts, tutorials etc to be able to do development.

I often take on students at the beginning of their coding 'careers' and this
repository is meant to be a list of things that they should learn/take a look at
before getting started. **Pull
requests welcome**.

In general the development I do is either for [sagemath](http://sagemath.org/)
or to build [python](https://www.python.org/) libraries.

## General concepts

Here are some basic language agnostic things:

### Text editor

Get a good text editor.

- I like to use [vim](http://www.vim.org/) but this has been historically referred to as having a steep
  learning curve. The plugins and ability to work right in the terminal are a
  huge strengths.
- Here are two other options if you prefer to make use of your mouse:
    - [atom](https://atom.io/) - has a bunch of plugins and can be hacked easily
      using css etc...
    - [sublime](http://www.sublimetext.com/) - a favorite of many. I can't say
      I've used it myself.

There are various other options (please do add them via pull request).

**Choose a good editor and most importanly realise that it is a very powerful
tool that (if you have chosen a good one) will do far more than just edit
text.**

### Terminal

The terminal is an interface to your computer that allows you to do a variety of
things through text based commands. This might seem archaic but once you are
used to it you will not want to use anything else. Developing a graphical user
interface is a step that a lot of great software has not taken so you would be
surprised by the amount of great tools available to you on the _command line_
(another word for terminal).

If you are using a linux machine you are probably familiar with a good terminal
tool. If you are using Mac OS then take a look at
[iterm2](https://www.iterm2.com/).
If you are using Windows take a look at the section at the end of this file.

### Git and github

When doing software development you need to use a 'version control' system.
This allows you to keep track of what you're doing and also to 'merge' your
changes in to the changes of others.

The most popular version control system at the moment is one called
[git](https://git-scm.com/). It comes with a bit of a learning curve but here
are some videos/tutorial to get you started:

- [What's so good about git](https://www.youtube.com/watch?v=OiiZIVb-rZ4)
- [Advanced git](https://www.youtube.com/watch?v=4EOZvow1mk4)

When using git it is helpful to have 'remote repositories' a good place for this
is a website called [github](https://github.com/). This is used by coders all
over the world to share code (and easily contribute to other's code).

It is worth setting up an account on github. Here are a few things that might be
helpful:

- [Don't be afraid to
  commit](https://dont-be-afraid-to-commit.readthedocs.org/en/latest/)
- [Contributing to the Axelrod
  library](https://www.youtube.com/watch?v=5kOUVdktxAo)

### Testing

When writing code it is very important to write automated tests. This is a good
book that takes you through the concepts for Django and Python:
[http://chimera.labs.oreilly.com/books/1234000000754](http://chimera.labs.oreilly.com/books/1234000000754)
but I need to find some better (smaller tutorials).

When using tests and github it's great to also use
[travis](https://travis-ci.org/).

### Windows

If you are using Windows I know very little about how to help you. I would
recommend using [cloud.sagemath](https://cloud.sagemath.com/) which gives you a
linux environment in the cloud with a terminal, text editor and various other
things.
