# Purpose of explicit numbering of versions

Usually, I number historical versions of a document for easy future
reference to its content.

# What is updated from version to version

There are five important aspects of a current document that may change
in the future versions, but may need to be preserved for re-use:
-   new section,
-   new idea,
-   new supportive materials (figure, table, reference, quote),
-   new phrasing,
-   new editorial changes.

Usually, different people work on these aspects separately.

# Using Git-branching model

Using *release* as a metaphor for a current version of an article, I can
say that release branches support preparation of a new article release:
approving new features, editing for style, proof-reading, last-minute
dotting of i’s and crossing t’s, and preparing meta-data for a release
(version number, dates, authors, etc.).

GH *Feature branches* will be used to introduce new sections, insert new
ideas, add new supportive material, revise phrasing, and copy editing.
These updates could be used for the next release, or for future
releases. The target release dates for these features releases may be
unknown at that point, and these updates will be either used or
discarded. The importance of having *feature branches* though is having
collaborators involved in parallel activities. (I wrote both books in
this way, where up to 5 people were working in parallel during 2-3
years).

Minor edits of the current releases will not be leading to changing
their versions.

# Naming convention
