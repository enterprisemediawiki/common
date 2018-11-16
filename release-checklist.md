Release checklist
=================

The following is intended to be used to guide releases of EMW repositories.

Checklist
---------

1. Update `extension.json` or anywhere else the version number may be stated in code
2. Create release notes with "Release notes template" section below
3. Add release notes to RELEASE-NOTES.md in repository
4. Add release notes to body of GitHub release
5. Update mediawiki.org page(s)
6. Maybe announce on riot, mailing lists, etc

Release name and tag
--------------------

* Tag: X.Y.Z
* Title: {{REPOSITORY NAME}} X.Y.Z

Release notes template
----------------------

{{OPTIONALLY INSERT BRIEF DESCRIPTION OF RELEASE}}

### Commits since {{PREVIOUS RELEASE}}

* List
* Generated
* By
* `git log --oneline tags/{{PREVIOUS RELEASE TAG}}..{{THIS RELEASE COMMIT HASH/BRANCH/ETC}}

### Contributors

List, of, contributors, using, `git shortlog -sn tags/{{PREVIOUS RELEASE TAG}}..{{THIS RELEASE COMMIT HASH/BRANCH/ETC}}`
