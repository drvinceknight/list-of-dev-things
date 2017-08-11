# List of things to learn to be able to do Python development

## Python

There are a variety of sources of excellent tutorials etc on the web. In general
aim to write small files that do one thing well and that combine to form a
library. This modularity helps with testing and contribution.

Here are some python resources:

- [My first year course](http://vknight.org/Computing_for_mathematics/) - Very
  much basics.
- [A list of other
  resources](http://vknight.org/Computing_for_mathematics/Other/AlternativeResources/)
- [A list of free Python books](http://pythonbooks.revolunet.com/)

Please add more here via PR.

## PEP8

There is an accepted convention for writing Python code, take a look at it
[here](https://www.python.org/dev/peps/pep-0008/).

## Testing

In general the testing environment used for Python libraries is called unit
testing:

- [The official documentation for the unittest library](https://docs.python.org/2/library/unittest.html)
- [The hitchiker's guide to python section on unit
  testing](http://docs.python-guide.org/en/latest/writing/tests/)

[This is a great video series on test driven
development.](https://www.youtube.com/playlist?list=PL5859017B018F03F4)

## Structure of a library

A python library is in essence a directory with `__init__.py` files (which are
sometimes empty) in various sub directories.

[This
link](https://the-hitchhikers-guide-to-packaging.readthedocs.org/en/latest/creation.html#arranging-your-file-and-directory-structure)
gives a good overview.

## Packaging

[Here](https://the-hitchhikers-guide-to-packaging.readthedocs.org/en/latest/)
is a great overview of how to package a library. This enables everyone to use
your code.

## Virtual environments

[pip](https://pip.pypa.io/en/latest/installing.html) is an amazing tool that
allows you to quickly and efficiently obtain various different python packages.

A virtual environment allows you to have a variety of Python environments with
different packages installed. This is useful when working with others as it
ensures that you are using the same tools (thanks to a `requirement.txt` file).

[Here](http://simononsoftware.com/virtualenv-tutorial) is a good overview.

## Documentation

Writing documentation is a big part of writing code. The easiest way to do this
for Python libraries (hosted on github) is through
[readthedocs](https://readthedocs.org/). Take a look at the tutorials available
there.
