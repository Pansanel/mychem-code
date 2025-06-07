Contributing to Mychem
======================

Thank you for taking the time to contriube to this project.
The maintainers greatly appreciate the interest of contributors
and rely on continued engagement with the community to ensure that
this project remains useful.
We would like to take steps to put contributos in the best possible
position to have their contributions accepted.
Please take a few moments to read this short guide on how to
contribute; bear in mind that contributions regarding how to best
contribute are also welcome.

Feedback and Questions
----------------------

If you wish to discuss anything related to the project, please open an
issue on: https://github.com/mychem/mychem-code/issues.

The maintainers will sometimes move closed issues off of GitHub to the
documentation if it make sens and could be benificial to a wider
community.


Kind of Contributions
---------------------

The maintainers recognise that contributions can be made in many forms,
depending on the skills, experience and perspectives of interested
parties. Contributions may come in the form of:

- Feature or documentation requests, where they describe a need or gap

- Authoring or review of releases

- Direct authorship of code or documentation

- Identifying and fixing bugs


Submitting Issues
-----------------

Not every contribution comes in the form of code. Submitting,
confirming, and triaging issues is an important task for any project.
At Mychem we use GitHub to track all project issues.


Contribution Process
--------------------

Before proposing a contribution via pull request, please ensure that
an issue is open describing the need for your contribution.
You will need to refer to this issue number when you submit the pull
request. Please note:

- It is recommended to make pull requests against release candidate
  branches, whenever features are involved, in stead of against the
  master branch.

- Pull requests to the master branch can be made in the case obvious
  fixes.

We have a 3 step process for contributions:

1. Fork the project if you have not, and commit changes to a git
   branch

2. Create a GitHub Pull Request for your change, following the
   instructions in the pull request template.

3. Perform a code review with the maintainers on the pull request.


Pull Request Requirements
+++++++++++++++++++++++++

1. Explain your contribution in plain language. To assist the
   maintainers in understanding and appreciating your pull request,
   please use the template to explain why you are making this
   contribution, rather than just what the contribution entails.

2. We expect tests to pass before peer review will begin.


Code Review Process
+++++++++++++++++++

Code review takes place in GitHub pull requests.
See `this article <https://help.github.com/articles/about-pull-requests/>`_
if you're not familiar with GitHub Pull Requests.

Once you open a pull request, maintainers will review your code using
the built-in code review process in Github PRs. The process at this
point is as follows:

1. A maintainer will review your code and merge it if no changes are
   necessary. Your change will be merged into the repository's `master`
   branch.

2. If want your contribution to motivate your inclusion in the
   authorship, please add a line to that effect in the pull request.

3. If a maintainer has feedback or questions on your changes they
   will set request changes in the review and provide an explanation.


Obvious Fix Policy
++++++++++++++++++

Small contributions, such as fixing spelling errors, where the content
is small enough to not be considered intellectual property can be made
against the master branch.

As a rule of thumb, changes are obvious fixes if they do not introduce
any new functionality or creative thinking. Assuming the change does
not affect functionality, some common obvious fix examples include the
following:

- Spelling / grammar fixes

- Typo correction, white space and formatting changes

- Comment clean up

- Bug fixes that change default return values or error codes stored
  in constants

- Adding logging messages or debugging output

- Changes to 'metadata' files like Gemfile, .gitignore, build scripts,
  etc.

- Moving source files from one directory or package to another

**Note: whenever you invoke the "obvious fix" rule, please say so in
your commit message.**


Using git
---------

For collaboration purposes, it is best if you create a GitHub account
and fork the repository to your own account. Once you do this you will
be able to push your changes to your GitHub repository for others to
see and use, and it will be easier to send pull requests.


Branches and Commits
++++++++++++++++++++

You should submit your patch as a git branch named after the Github
issue, such as ``#3``. This is called a ``topic branch`` and allows users
to associate a branch of code with the ticket.

It is a best practice to have your commit message have a summary
line that includes the ticket number, followed by an empty line and
then a brief description of the commit. This also helps other
contributors understand the purpose of changes to the code.


Release Cycle
+++++++++++++

We follow the `Semantic Versioning <https://semver.org/>`_ as far as
applicable. This pattern says that software versions should take an
``X.Y.Z`` pattern where:

- X is a major release, which may not be fully compatible with prior
  major releases

- Y is a minor release, which adds both new features and bug fixes

- Z is a patch release, which adds just bug fixes

Releases are generally performed after any bugfix / feature
enhancement pull request merge. You can watch the Github repository for
updates.
The latest release will always point to the master branch, while
release candidates will be done in version-specific branches, such as
``v0.2.0-rc``.


Publishing Releases
+++++++++++++++++++

Major releases are published in Zenodo, using the GitHub integration.
The ``codemeta.json`` file must be updated prior to each release,
accurately describing the research object, and properly recognising
author and contributor metadata.


Acknowledmegent
---------------

This file has been modified from the Chef Cookbook Contributing Guide.
