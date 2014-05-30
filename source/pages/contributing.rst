.. _contributing:

===========================
Contributing to the Project
===========================

1. Roles and Responsibilities
=============================
There are four main roles for contributing, based on the `YUI Contributor Model <https://github.com/yui/yui3/wiki/Contributor-Model#2-roles-and-responsibilities>`_. They are outlined below.

1.1. Users
----------
Users are community members who have a need for the project. Anyone can be a User; there are no special requirements. Common User contributions include evangelizing the project (e.g., display a link on a website and raise awareness through word-of-mouth), informing developers of strengths and weaknesses from a new user perspective, or providing moral support (a "thank you" goes a long way).

Users who continue to engage with the project and its community will often become more and more involved. Such Users may find themselves becoming Contributors, as described in the next section.

1.2. Contributors
-----------------
Contributors are community members who contribute in concrete ways to the project, most often in the form of code and/or documentation. Anyone can become a Contributor, and contributions can take many forms. There is no expectation of commitment to the project, no specific skill requirements, and no selection process.

As Contributors gain experience and familiarity with the project, their profile within, and commitment to, the community will increase. At some stage, they may find themselves being nominated for committership by an existing Committer.

1.3. Committers
---------------
Committers are community members who have shown that they are committed to the continued development of the project through ongoing engagement with the community. Committers are given push access to the project's GitHub repo and must abide by the project's Contribution Standards, including milestones such as feature complete and code freeze.

While committership indicates a valued member of the community who has demonstrated a healthy respect for the project's aims and objectives, their work continues to be reviewed by Reviewers (see below) before acceptance in an official release.

To become a Committer, one must have shown a willingness and ability to participate in the project as a team player. Typically, a potential Committer will need to show that they have an understanding of and alignment with the project, its objectives, and its strategy. They will also have provided valuable contributions to the project over a period of time and, specifically, a minimum of 8 qualifying pull requests. What's a qualifying pull request? One that carries significant technical weight and requires little effort to accept because it’s well documented and tested.

New Committers can be nominated by any existing Committer. Once they have been nominated, there will be a discussion and vote by the Reviewers. While there is no formal system in place for this right now, Reviewers will try to use their best judgement, always keeping the project's best interests in mind.

It is important to recognize that committership is a privilege, not a right. That privilege must be earned and once earned it can be removed by the Reviewers (see next section) in extreme circumstances. However, under normal circumstances committership exists for as long as the Committer wishes to continue engaging with the project.

A Committer who shows an above-average level of contribution to the project, particularly with respect to its strategic direction and long-term health, may be nominated to become a Reviewer, described below.

1.4. Reviewers
--------------
Reviewers are individuals identified as "project admins" for the project on GitHub. Reviewers have additional responsibilities over and above those of a Committer. These responsibilities ensure the smooth running of the project. Reviewers are expected to review code contributions, approve changes to this document, and manage the copyrights within the project outputs.

Reviewers' contributions can be reviewed by other Reviewers, but this is not explicitly required. Reviewers do not have significant authority over other members of the community, although it is the Reviewers that vote on new Committers. They also make decisions when community consensus cannot be reached.

A Committer is invited to become a Reviewer by existing Reviewers. An existing Committer may be considered for Reviewer status only after they have submitted 40 qualifying pull requests of technical significance that have been accepted without significant rework into the project. A nomination will result in discussion and then a vote by the existing Reviewers.

2. GitHub
=========

2.1. Forking
------------
To begin working on the project, you need to grab the latest code first. This can be done by `forking <https://help.github.com/articles/fork-a-repo>`_ the repository.

2.1. Pull Requests
------------------
All contributions to this project must be made through `Pull Requests <https://help.github.com/articles/using-pull-requests>`_. Pull requests are reviewed on a first come first serve basis by at least one of the Reviewers. In order to be accepted, the submitted code must meet the following criteria:
   * It must be apparently free of bugs, or if intractable bugs are present and the code is still useful, bugs must be clearly documented and relevant `issues <https://github.com/AnthonyReid99/VisualGit/issues>`_ must be created on GitHub
   * It must meet all of the coding and documenting conventions laid out in these documents
   * It must integrate well with existing code

2.2. Pulling from Upstream
--------------------------
To get the latest changes from the original repository, you need to `pull from upstream <https://help.github.com/articles/fork-a-repo#pull-in-upstream-changes>`_.

2.3. Issue Tracking
-------------------
GitHub's `Issues <https://guides.github.com/features/issues/>`_ system will be used to track known bugs and issues, as well as manage feature requests.

3. Git
======

3.1. Committing
---------------

3.1.1. Commit Messages
######################

Commit messages consist of:
   * A short summary of changes made to be limited to 50 characters in width. This line should not end with a period, and should always be followed by a blank line.
   * Additional paragraphs providing more detail, separated by blank lines, and limited to 72 characters in width.
   * Bullet points may also be used, and may be indicated by a '*' or a '-'
* The commit message should be written in the imperative tone, that is, as if commanding somebody to make your changes
   * Good: "Fix the time zone bug and change the path"
   * Bad: "Fixed the time zone bug and changed the path"
For more on why this is good practice, check out `this article <http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html>`_.

3.1.2. Commit Size
##################
Commits should address one issue at a time. Those that contain multiple unrelated changes should be split appropriately. Adjacent commits that each contain partial changes related to the same feature should be squashed together. Read up on `rewriting commit history <http://git-scm.com/book/en/Git-Tools-Rewriting-History>`_ for more on managing commit size.