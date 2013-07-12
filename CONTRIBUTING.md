Contributing to PHP-Resque
==========================

(Shamelessly & proudly adapted from [Resque](https://github.com/resque/resque))

First of all: thank you! We appreciate any help you can give PHP-Resque.

1. [Fork](https://help.github.com/articles/fork-a-repo) PHP-Resque
2. Create a topic branch - `git checkout -b my_branch`
3. Push to your branch - `git push origin my_branch`
4. Create a [Pull Request](http://help.github.com/pull-requests/) from your
   branch
5. That's it!

If you're not doing some sort of refactoring, a CHANGELOG entry is appropriate.
Please include them in pull requests adding features or fixing bugs.

Oh, and 80 character columns, please!

Branches
--------

The `1-x-stable` branch is what is currently being released as `1.x.y`.

The `master` branch is what will become 2.0.

It's suggested that you make your pull request against the master branch by
default, and backport the fix with a second pull request where applicable.

Tests
-----

We use PHPUnit for testing, you'll find a bunch of tests in `test/`.
Make sure they pass when you submit a pull request.

Please include aditional tests with your pull request if necessary.

Documentation
-------------

Writing docs is really important. We use yard to generate our documentation.
Please include docs in your pull requests.

Bugs & Feature Requests
-----------------------

You can file bugs on the [issues
tracker](https://github.com/chrisboulton/php-resque/issues), and tag them with
'bug'.

When filing a bug, please follow these tips to help us help you:

### Good report structure

Please include the following four things in your report:

1. What you did.
2. What you expected to happen.
3. What happened instead.
4. What version of PHP-Resque you're using.

The more information the better.

### Reproduction

If possible, please provide some sort of executable reproduction of the issue.
Your application has a lot of things in it, and it might be a complex
interaction between components that causes the issue.

To reproduce the issue, please make a simple job that demonstrates the essence
of the issue. If the basic job doesn't demonstrate the issue, try including the
sources/libs your application uses (if possible), even if it doesn't seem
directly relevant.
