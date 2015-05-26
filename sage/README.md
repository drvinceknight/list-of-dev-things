# List of things to learn to be able to do Sage development

Here are some specific things for the development of Sage:

- Doctests: The sage library uses doctests as it's testing framework. This means
  that tests are written in a particular way right in to the docstrings of the
  code. You can read about doctesting the Sage library
  [here](http://doc.sagemath.org/html/en/reference/doctest/index.html).
- Sphinx: The documentation for Sage uses Sphinx. It is worth learning how this
  language's syntax. [Here](http://sphinx-doc.org/) is the Sphinx documentation.
- [Trac](http://trac.sagemath.org/): This is how Sage development is managed. The general process is
  something like this:
    1. Find a feature/bug you want to implement/fix in Sage
    2. Open a ticket on trac
    3. Write code on a branch (checked out from the `develop` branch)
    4. Push commits to the trac server: `git push trac:u/[username]/[something]`
    5. On trac set the Branch file to `u/[username]/[something]`
    6. Wait for review
    7. Discuss
    8. Repeat steps 3-7
    9. Virtual high five your reviewer and celebrate
