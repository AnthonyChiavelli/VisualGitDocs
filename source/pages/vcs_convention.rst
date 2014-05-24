.. _vcs_convention:

============================================
2. VCS Convention
============================================

2.1 Github
============================================

2.1.1 Pull Requests
--------------------------------------------
* All contributions to this project must be made through pull requests
* In order to be accepted, the submitted code must meet the following criteria
   * It must be apparently free of bugs, or if intractable bugs are present and the code is still useful, bugs must be clearly documented and relevant issues must be created on github
   * It must meet all of the coding convention laid out in these documents
   * It must integrate well with existing code
* Pull requests are accepted on a first come first serve basis. 

2.1.2 Issue Tracking
--------------------------------------------
* Github's issue tracking system will be used to track known bugs and issues

2.2 Git
============================================

2.2.1 Commiting
--------------------------------------------

2.2.1.1 Commit Messages
############################################

* Commit messages consist of:
   * A short summary of changes made to be limited to 50 characters in width. This line should not end with a period.
   * A blank line
   * Additional paragraphs providing more detail, separated by blank lines, and limited to 72 characters in width.
   * Bullet points may also be used, and may be indicated by a '*' or a '-'
* The commit message should be written in the imperative tone, that is, as if commanding somebody to make your changes
   * Good: "Fix the time zone bug and change the path"
   * Bad: "Fixed the time zone bug and changed the path"

2.2.1.2 Commit Size
############################################
* Commits should address one issue at a time.
* Those that contain multiple unrelated changes should be split appropriately.
* Adjacent commits that each contain partial changes related to the same feature should be squashed together