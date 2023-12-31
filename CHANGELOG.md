# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

<!-- Format restrictions - see https://common-changelog.org and https://keepachangelog.com/ for details -->
<!-- Each Release must start with a line for the release version of exactly this format: ## [version] -->
<!-- The subsequent comment lines start with a space - not to irritate the release scripts parser!
 ## [major.minor.micro]
 <empty line> - optional sub sections may follow like:
 ### Added:
 - This feature was added
 <empty line>
 ### Changed:
 - This feature was changed
 <empty line>
 ### Removed:
 - This feature was removed
 <empty line>
 ### Fixed:
 - This issue was fixed
 <empty line>
 <empty line> - next line is the starting of the previous release
 ## [major.minor.micro]
 <empty line>
 <...>
 !!! In addition the compare URL links are to be maintained at the end of this CHANGELOG.md as follows.
     These links provide direct access to the GitHub compare vs. the previous release.
     The particular link of a released version will be copied to the release notes of a release accordingly.
     At the end of this file appropriate compare links have to be maintained for each release version in format:
 
  +-current release version
  |
  |                   +-URL to this repo    previous release version tag-+       +-current release version tag
  |                   |                                                  |       |
 [major.minor.micro]: https://github.com/mavenplugins/org-parent/compare/vM.N.u..vM.N.u
-->
<!--
## [Unreleased]

### Additions
- TBD

### Changes
- TBD

### Deprecated
- TBD

###	Removals
- TBD

### Fixes
- TBD

###	Security
- TBD
-->

## [Unreleased]

### Changes
- TBD


## [1]
<!-- !!! Align version in badge URLs as well !!! -->
[![1 Badge](https://img.shields.io/nexus/r/io.github.mavenplugins/org-parent?server=https://s01.oss.sonatype.org&label=Maven%20Central&queryOpt=:v=1)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/1)

### Summary
- Initial release

### Features
- Define common Maven plugin versions via properties
- Define Unleash plugins with groupId, artifactId and version via individual properties
- Profile based executions to sign and stage artifacts to Sonatype OSSRH and Maven Central
- Profiles being activated by system environment variables to leverage several CICD use cases

### Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>1</version>
  </parent>
  ```


<!--
## []

### NeverReleased
- This is just a dummy placeholder to make the parser of GHCICD/release-notes-from-changelog@v1 happy!
-->

[Unreleased]: https://github.com/mavenplugins/org-parent/compare/v1..HEAD
[1]: https://github.com/mavenplugins/org-parent/releases/tag/v1
