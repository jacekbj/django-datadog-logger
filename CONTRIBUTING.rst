.. highlight:: shell

============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every little bit
helps, and credit will always be given.

Get Started!
------------

Ready to contribute? Here's how to set up `ddl` for local development.

1. Fork the `ddl` repo on GitHub.
2. Clone your fork locally::

    $ git clone git@github.com:your_name_here/ddl.git

3. Install your local copy into a virtualenv. Assuming you have virtualenvwrapper installed, this is how you set up your fork for local development::

    $ python install .
    $ python install .[dev]

    For zsh: `pip install ."[dev]"`

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally.

5. When you're done making changes, check that your changes pass flake8 and the
   tests. Other versions of Python are checked with CI::

    $ make lint
    $ make test

6. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

7. Submit a pull request through the GitHub website.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python 3.9, 3.10, 3.11 and 3.12.


Deploying
---------

A reminder for the maintainers on how to deploy.
Make sure all your changes are committed (including an entry in HISTORY.rst).
Then create a Pull Request on Github with one of the following labels: patch, minor or major.
Github will bump version, create a new tag and deploy to PyPi if tests pass.
