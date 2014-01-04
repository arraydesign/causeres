Purpose of explicit numbering of versions
=========================================

Usually, I number historical versions of a document for easy future reference to
its content.

What is updated from version to version
=======================================

There are five important aspects of a current document that may change in the
future versions, but may need to be preserved for re-use: new section, new idea,
new supportive materials (figure, table, reference), new phrasing, new editorial
changes.  Usually, different people work on it separately.

Using Git-branching model
=========================

Using "release" as a metaphor for a document's current version, I can say that
release branches support preparation of a new article release: approving new features, editing for
style, last-minute dotting of i’s and crossing t’s, and preparing meta-data for
a release (version number, build dates, etc.).

Feature branches will be used to introduce new sections, insert new ideas, add
new supportive material, revise for phrasing, and editing. These could be used
for the next release, and for future releases. The target release for these
features may be unknown at that point, and will be either used or discarded. The
importance of having feature branches though is having people involved in
parallel activities. (I wrote both books this way, where up to 5 people were
working in parallel during 2-3 years).

Naming convention
=================










