# Nubis - Relase Managment

This is a document that helps explain all the process involved in Release Managment for the Nubis project. If you are not planning to make a Nubis release, you can safely ignore this document, unless you are curious.

## Milestones

Milestones are used to track a given Nubis release. Issues that will be part of that relase will be assigned to the corresponding Milestone.

### Format

All Milestones will be [semantic versions](http://semver.org/) in the form of vn.n.n, where v stands for 'v'ersion, as per GitHub's recommended naming practices.

There can also be an extra postfix to the version number, added to describe the type or release this represents, i.e.

 * v1.0.0-beta
 * v1.2.3-devel
 * v1.5.5-preview

 ### Code names

 Release code-names might be exist, but will be used for purely cosmetic purposes. The *Happy Panda* release would just be a name for the v1.5.0 release.

## Tags

Tags will be used to track releases of the Nubis Project.

All tags will be [semantic versions](http://semver.org/) in the form of vn.n.n, where v stands for 'v'ersion, as per GitHub's recommended naming practices.

All tags will be [GPG Signed](https://git-scm.com/book/tr/v2/Git-Tools-Signing-Your-Work) by the Release Manager, allowing anybody to verify their integrity.

Each Nubis repository is allowed to follow it's own minor release tagging schedule.

Major release bumps (i.e, from v0.9.2 to v1.0.0) will be coordinated across all repositories, to provide a consistent versionning scheme for each major Nubis Project release.