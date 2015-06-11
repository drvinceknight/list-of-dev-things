# List of things to learn

[![Join the chat at https://gitter.im/drvinceknight/list-of-dev-things](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/drvinceknight/list-of-dev-things?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

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
    - [geany](http://www.geany.org/) - friendly though mighty and cross-platform.

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

[Here](http://cli.learncodethehardway.org/book/) is a good tutorial.

### Git and github

When doing software development you need to use a 'version control' system.
This allows you to keep track of what you're doing and also to 'merge' your
changes in to the changes of others.

The most popular version control system at the moment is one called
[git](https://git-scm.com/). It comes with a bit of a learning curve but here
are some videos/tutorial to get you started.

This is probably worth reading first (it gives an overall description of what version control is):

- [The git parable](http://tom.preston-werner.com/2009/05/19/the-git-parable.html)

Here are some tutorials:

- [Pro Git](https://progit.org/)
- [What's so good about git](https://www.youtube.com/watch?v=OiiZIVb-rZ4)
- [Advanced git](https://www.youtube.com/watch?v=4EOZvow1mk4)

Although you'll want to become proficient at driving Git via the command line, it can often be useful to have a graphical tool for those occasions when you are uncertain of the correct command. [SourceTree](https://www.atlassian.com/software/sourcetree/overview) is a free, cross platform desktop Git client which you may find useful.

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

### Markup languages

Markdown is a language worth learning to be able to neatly write on github
issues etc...

- [This video](https://www.youtube.com/watch?v=6A5EpqqDOdk) is probably the easiest way to do this (note that you will just
write markdown in your preferred editor).
- You can also read the [github flavoured markdown
  documentation](https://help.github.com/articles/github-flavored-markdown/).

There are various other markup languages (html, LaTeX, rest etc...) but I do not
consider them to be fundamental (they will be listed where relevant in this
repository).

### Windows

If you are using Windows, you have several choices for your terminal program:

- The original Command Prompt runs commands and scripts in the MS-DOS scripting language. It's old, but there's lots of material online to help you
- Windows Powershell is built into all modern versions of Windows and gives you a far superior, modern, object-oriented scripting language and a far better terminal.
- If you want to use a Linux based interface to your Windows machine, you can install [Cygwin](https://www.cygwin.com/) which will give you most of the common Linux tools and commands.
- You could also use [cloud.sagemath](https://cloud.sagemath.com/) which gives you a linux environment in the cloud with a terminal, text editor and various other things.

For your text editor, both [atom](https://atom.io/), [sublime](http://www.sublimetext.com/) and [geany](http://www.geany.org/) will all work perfectly. If you are using Cygwin, you can also use Vim.

### Using the cloud

If you are using Windows and/or have other reasons you can do a lot of
development right in your web browser.

There are a variety of options but I am a big fan of
[cloud.sagemath](https://cloud.sagemath.com/). In particular if you want to
develop for [sagemath](http://sagemath.org/) this is an excellent option.

### Communication

There are various tools I like to use for communicating during a project.

- Quick text based messages:
    - I particularly like [google hangouts](https://plus.google.com/hangouts):
    light weight and has a mobile app (which is very useful when I can only
    respond whilst running between meetings).
    - Another great option is [gitter](https://gitter.im). Again, has a mobile app and also interfaces very nicely with github repositories. You can find the gitter room for this repository [here](https://gitter.im/drvinceknight/list-of-dev-things).
    - [irc](http://en.wikipedia.org/wiki/Internet_Relay_Chat) is very popular in the open source world. I can't say I'm the
      biggest fan but it's a great place to drop in and speak to people.

- github issues. When using github for a project it comes with a nice interface
  to raise a so called 'issue' which allows for a public record of a
  conversation. This is very helpful and worthwhile in a development process as
  at some point down the line it might be helpful to remember why something was
  decided. It's always good to open an issue for a feature before starting to
  work on it.

- Emails (they do a job).

- Virtual meetings: Very rarely are face to face meetings a regular requirement.
  I like to use hangouts for these but again there are a variety of options.

- urls: when working remotely it's very helpful to be able to just paste link to
  something that brings it up in the receivers browser. There are various tools
  for this:
    - Github (just grab the link from the particular file)
    - [Gists](https://gist.github.com/) (for throw away pieces of code)
    - Dropbox (if you have something in a dropbox folder you can use the 'share
      a link feature' - this is partcilarly helpful and quick for screenshots)

## Contributing to this repository

I would be delighted for contributions to this repository:

- If you are a student who has worked with me and feel that I am leaving
  something out or indeed that there are useful tutorials/videos etc then please
  do add them via pull request.
- All other contributions are of course welcome, please keep in mind that I am
  attempting to build a fairly generic list for students assuming only a very
  basic knowledge of writing code.

Please do raise an issue if you're not sure if something is worth having.
