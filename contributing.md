---
title: Contribution Guidelines
authors:
  - Julio Valcarcel
  - Zack Orndorff
---

We would love for you to contribute to this collection of resources. In order
to keep this organized and maintainable we ask that you follow these guidelines
below. 

## Getting started 

The first thing you will need to contribute is a git client. On Linux all you
need to do is use your distro's package manager to install the git package. On
Windows or OS X you will need to go to the [git download page][1] and get either
the command line package or a GUI client.

First you will need to <a href="#" data-toggle="tooltip"
data-original-title="{{site.data.glossary.git_fork}}">fork</a> the project.
To fork the project first login to (or create) your GitHub account. Once you're
logged you can [fork][2] the repository. Now you can clone your copy of the
repository and make your changes. Once you are done submit a <a href="#"
data-toggle="tooltip" data-original-title="{{site.data.glossary.git_pull_request}}">
pull request</a>. 
 
For more information on how to fork a repository on GitHub please review their
[documentation][3] and for submitting pull requests [here][4].

## Adding a page

### Content

To add a new page, first figure out what section you want to add to. Currently,
we're trying to structure our URLs like
`umbccd.umbc.edu/resources/path/the-topic/`. As a result, our folder structure
has to mirror that. So for instance, for the Intro to Security section, there's
an intro folder. To add a page to that section, you would add a new folder
corresponding to the path you want it to have, then the actual content goes in
a index.md file within that new folder.

### Navigation

To add to the left hand side navigation, you'll need to add a few lines to
`\_data/sidebars/home_sidebar.yml`. It should be fairly straightforward.


[1]: https://git-scm.com/downloads
[2]: https://github.com/UMBCCyberDawgs/resources#fork-destination-box
[3]: https://help.github.com/articles/fork-a-repo/
[4]: https://help.github.com/articles/using-pull-requests/ 
