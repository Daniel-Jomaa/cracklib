Release Process
===============

Follow semantic versioning standard if at all possible: https://semver.org/ (MAJOR.MINOR.PATCH-PRE)

During development, pick next planned version - increment patch level, and add "-dev"

Before publication, add in NEWS for example "2.9.x" or "master" or "dev" and only when it is the commit
for announcement, the moment to change the new version.

At time of release, create ONE commit with all version numbers update in files and named for example "X.X.X".
Create a tag of the name "vX.Y.Z" pointed to that commit and produce releases at that point

After the release, commit a change to put versions back to MAJOR.MINOR.(PATCH+1)-dev
