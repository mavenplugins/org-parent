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

### 🚨 Removed
- TBD

### 💥 Breaking
- TBD

### 📢 Deprecated
- TBD

### 🚀 New Features
- TBD

### 🐛 Fixes
- TBD

### ✨ Improvements
- TBD

### 🔧 Internal Changes
- TBD

### 🚦 Tests
- TBD

### 📦 Updates
- TBD

### 🔒 Security
- TBD

### 📝 Documentation Updates
- TBD
-->

## [Unreleased]
<!-- !!! Align version in badge URLs as well !!! -->
[![13 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=13)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/13)

### Summary
- TBD

### 📦 Updates
- TBD

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>12</version>
  </parent>
  ```


## [13]
<!-- !!! Align version in badge URLs as well !!! -->
[![13 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=13)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/13)

### Summary
- Update `org.sonatype.central:central-publishing-maven-plugin` to `io.github.mavenplugins:central-publishing-maven-plugin`
- Update `version.central-publishing-maven-plugin -> 1.1.0`
- Update `version.unleash-maven-plugin -> 3.3.1`
- Update Maven Central staging progress timeout per state:
  - Validated timeout: 1817s
  - Published timeout: 7268s

### 📦 Updates
- Update property `<version.unleash-maven-plugin>3.3.1</version.unleash-maven-plugin>`
- Update property `<version.central-publishing-maven-plugin>1.1.0</version.central-publishing-maven-plugin>`
- Update `org.sonatype.central:central-publishing-maven-plugin` to `io.github.mavenplugins:central-publishing-maven-plugin`
- Add property `<staging.validatedProgressTimeoutSeconds>1817</staging.validatedProgressTimeoutSeconds>`
- Add property `<staging.publishedProgressTimeoutSeconds>7268</staging.publishedProgressTimeoutSeconds>`

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>13</version>
  </parent>
  ```


## [12]
<!-- !!! Align version in badge URLs as well !!! -->
[![12 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=12)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/12)

### Summary
- Migrate to publish artifacts via Sonatype Maven Central Portal API
  - replace `nexus-staging-maven-plugin` by `central-publishing-maven-plugin`
- Update `version.unleash-maven-plugin -> 3.3.0`
- Add `version.central-publishing-maven-plugin -> 0.8.0`

### 📦 Updates
- Update property `<version.unleash-maven-plugin>3.3.0</version.unleash-maven-plugin>`
- Add property `<version.central-publishing-maven-plugin>0.8.0</version.central-publishing-maven-plugin>`

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>12</version>
  </parent>
  ```


## [11]
<!-- !!! Align version in badge URLs as well !!! -->
[![11 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=11)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/11)

### Summary
- Update `version.unleash-maven-plugin -> 3.2.1`
- Update `version.unleash-scm-provider-git -> 3.3.0`
- Update `version.unleash-scm-provider-svn -> 3.0.2`
- Update `version.cdi-plugin-hooks -> 0.2.1`

### 📦 Updates
- Update property `<version.unleash-maven-plugin>3.2.1</version.unleash-maven-plugin>`
- Update property `<version.unleash-scm-provider-git>3.3.0</version.unleash-scm-provider-git>`
- Update property `<version.unleash-scm-provider-svn>3.3.0</version.unleash-scm-provider-svn>`
- Update property `<version.cdi-plugin-hooks>0.2.1</version.cdi-plugin-hooks>`

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>11</version>
  </parent>
  ```


## [10]
<!-- !!! Align version in badge URLs as well !!! -->
[![10 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=10)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/10)

### Summary
- Fix vulnerability warning on ant:
  - Update `version.maven-antrun-plugin -> 3.1.0`
  - Update `version.antrun.ant -> 1.10.15`

### 🔒 Security
- Update property `<version.maven-antrun-plugin>3.1.0</version.maven-antrun-plugin>`
- Update property `<version.antrun.ant>1.10.15</version.antrun.ant>`

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>10</version>
  </parent>
  ```


## [9]
<!-- !!! Align version in badge URLs as well !!! -->
[![9 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=9)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/9)

### Summary
- Update `version.unleash-maven-plugin -> 3.2.0`
- Update `version.unleash-scm-provider-git -> 3.2.0`
- Add dependency `org.codehaus.mojo:extra-enforcer-rules:1.9.0` to Maven enforcer plugin

### 📦 Updates
- Update property `<version.unleash-maven-plugin>3.2.0</version.unleash-maven-plugin>`
- Update property `<version.unleash-scm-provider-git>3.2.0</version.unleash-scm-provider-git>`
- Add property `<version.extra-enforcer-rules>1.9.0</version.extra-enforcer-rules>`
- Add dependency `org.codehaus.mojo:extra-enforcer-rules:1.9.0` to Maven enforcer plugin

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>9</version>
  </parent>
  ```


## [8]
<!-- !!! Align version in badge URLs as well !!! -->
[![8 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=8)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/8)

### Summary
- Update `version.unleash-maven-plugin -> 3.1.0`
- Update `version.nexus-staging-maven-plugin -> 1.7.0`

### Changes
- Update property `<version.unleash-maven-plugin>3.1.0</version.unleash-maven-plugin>`
- Update property `<version.nexus-staging-maven-plugin>1.7.0</version.nexus-staging-maven-plugin>`

### Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>8</version>
  </parent>
  ```


## [7]
<!-- !!! Align version in badge URLs as well !!! -->
[![7 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=7)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/7)

### Summary
- Update `version.unleash-maven-plugin -> 3.0.3`

### Changes
- Update property `<version.unleash-maven-plugin>3.0.3</version.unleash-maven-plugin>`

### Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>7</version>
  </parent>
  ```


## [6]
<!-- !!! Align version in badge URLs as well !!! -->
[![6 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=6)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/6)

### Summary
- Update `version.unleash-maven-plugin -> 3.0.1`
- Update `version.unleash-scm-provider-git -> 3.0.1`
- Update `version.unleash-scm-provider-svn -> 3.0.1`
- Update `version.cdi-plugin-hooks -> 0.2.0`

### Changes
- Update property `<version.unleash-maven-plugin>3.0.1</version.unleash-maven-plugin>`
- Update property `<version.unleash-scm-provider-git>3.0.1</version.unleash-scm-provider-git>`
- Update property `<version.unleash-scm-provider-svn>3.0.1</version.unleash-scm-provider-svn>`
- Update property `<version.cdi-plugin-hooks>0.2.0</version.cdi-plugin-hooks>`

### Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>6</version>
  </parent>
  ```


## [5]
<!-- !!! Align version in badge URLs as well !!! -->
[![5 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=5)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/5)

### Summary
- Update `version.unleash-maven-plugin -> 3.0.0`
- Update `version.unleash-scm-provider-git -> 3.0.0`
- Update `version.unleash-scm-provider-svn -> 3.0.0`
- Update `version.cdi-plugin-hooks -> 0.2.0`

### Changes
- Update property `<version.unleash-maven-plugin>3.0.0</version.unleash-maven-plugin>`
- Update property `<version.unleash-scm-provider-git>3.0.0</version.unleash-scm-provider-git>`
- Update property `<version.unleash-scm-provider-svn>3.0.0</version.unleash-scm-provider-svn>`
- Update property `<version.cdi-plugin-hooks>0.2.0</version.cdi-plugin-hooks>`

### Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>5</version>
  </parent>
  ```


## [4]
<!-- !!! Align version in badge URLs as well !!! -->
[![4 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=4)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/4)

### Summary
- Update `version.unleash-maven-plugin -> 2.11.0`
- Update `version.unleash-scm-provider-git -> 2.4.0`
- Update `version.cdi-plugin-hooks -> 0.1.2`

### Changes
- Update property `<version.unleash-maven-plugin>2.11.0</version.unleash-maven-plugin>`
- Add property `<groupId.unleash-scm-provider-git>${groupId.unleash-scm-provider}</groupId.unleash-scm-provider-git>`
- Rename property `artifactId.unleash-scm-provider` -> `artifactId.unleash-scm-provider-git`
- Rename property `version.unleash-scm-provider` -> `version.unleash-scm-provider-git`
- Update property `<version.unleash-scm-provider-git>2.4.0</version.unleash-scm-provider-git>`
- Add property `<groupId.unleash-scm-provider-svn>${groupId.unleash-scm-provider}</groupId.unleash-scm-provider-svn>`
- Add property `<artifactId.unleash-scm-provider-svn>unleash-scm-provider-svn</artifactId.unleash-scm-provider-svn>`
- Add property `<version.unleash-scm-provider-svn>2.2.0</version.unleash-scm-provider-svn>`
- Update property `<version.cdi-plugin-hooks>0.1.2</version.cdi-plugin-hooks>`

### Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>4</version>
  </parent>
  ```


## [3]
<!-- !!! Align version in badge URLs as well !!! -->
[![3 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=3)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/3)

### Summary
- Fix profile `m2e`

### Fixes
- Fix profile `m2e`:
  - update activating property `m2e.version` -> `osgi.requiredJavaVersion`
  - add plugins `maven-plugin-plugin` and `plexus-component-metadata` to m2e lifecycle mapping

### Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>3</version>
  </parent>
  ```


## [2]
<!-- !!! Align version in badge URLs as well !!! -->
[![2 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=2)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/2)

### Summary
- Default groupId for all unleash plugins is now `io.github.mavenplugins`

### Changes
- Add plugin management configuration for `maven-compiler-plugin`
- Default version for `maven-compiler-plugin` is `3.12.1`
- Update property `<groupId.unleash.common>io.github.mavenplugins</groupId.unleash.common>`
- Add usage of `maven-enforcer-plugin` to enforce a minimum Maven version for building
- Add a config for `org.eclipse.m2e:lifecycle-mapping`

### Features
- Define common Maven plugin versions via properties
- Define Unleash plugins with groupId, artifactId and version via individual properties
- Profile based executions to sign and stage artifacts to Sonatype OSSRH or Maven Central
- Profiles being activated by system environment variables to leverage several CICD use cases

### Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>org-parent</artifactId>
    <version>2</version>
  </parent>
  ```


## [1]
<!-- !!! Align version in badge URLs as well !!! -->
[![1 Badge](https://img.shields.io/maven-central/v/io.github.mavenplugins/org-parent?label=Maven%20Central&filter=1)](https://central.sonatype.com/artifact/io.github.mavenplugins/org-parent/1)

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

[Unreleased]: https://github.com/mavenplugins/org-parent/compare/v13..HEAD
[13]: https://github.com/mavenplugins/org-parent/compare/v12..v13
[12]: https://github.com/mavenplugins/org-parent/compare/v11..v12
[11]: https://github.com/mavenplugins/org-parent/compare/v10..v11
[10]: https://github.com/mavenplugins/org-parent/compare/v9..v10
[9]: https://github.com/mavenplugins/org-parent/compare/v8..v9
[8]: https://github.com/mavenplugins/org-parent/compare/v7..v8
[7]: https://github.com/mavenplugins/org-parent/compare/v6..v7
[6]: https://github.com/mavenplugins/org-parent/compare/v5..v6
[5]: https://github.com/mavenplugins/org-parent/compare/v4..v5
[4]: https://github.com/mavenplugins/org-parent/compare/v3..v4
[3]: https://github.com/mavenplugins/org-parent/compare/v2..v3
[2]: https://github.com/mavenplugins/org-parent/compare/v1..v2
[1]: https://github.com/mavenplugins/org-parent/releases/tag/v1
