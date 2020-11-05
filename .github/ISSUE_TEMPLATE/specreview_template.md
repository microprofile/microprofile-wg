---
name: Specification Review Issue
about: Start a request for a specification creation/plan/release... lifecycle review
title: \[MP Component] \[Version] Specification Review
labels: creation,plan,progress,release
assignees: ''
---

## Specification issue template
When creating a specification project lifecycle review, create issues in the [MicroProfile-WG repository](https://github.com/microprofile/microprofile-wg) with the content defined as follows.

- [ ] Specification name and version (two digit):
- [ ] Add a label from one of: `creation`, `plan`, `progress`, `release`
- [ ] The URL of the OSSRH staging repository for the spec (using the staging repository id):
      (eg, https://oss.sonatype.org/content/repositories/orgeclipsemicroprofile-1357/org/eclipse/microprofile/config/microprofile-config-spec/2.0-RC9/)
 - [ ] Specification PDF in the form of microprofile-_project_-spec-x.y.pdf where _project_ is the microprofile specification short project name (config, health, ...)
 - [ ] Specification HTML in the form of microprofile-_project_-spec-x.y.html
- [ ] The URL of the OSSRH staging repository for the API and Javadoc jar files (using the staging repository id):
      (eg, https://oss.sonatype.org/content/repositories/orgeclipsemicroprofile-1357/org/eclipse/microprofile/config/microprofile-config-api/2.0-RC9/)
- [ ] The URL of the OSSRH staging repository for the TCK (using the staging repository id):
      (eg, https://oss.sonatype.org/content/repositories/orgeclipsemicroprofile-1357/org/eclipse/microprofile/config/microprofile-config-tck/2.0-RC9/)

- [ ] For a [Release Review](https://www.eclipse.org/projects/handbook/#6_3_3_Release_Review):
   - [ ] Updated [release record](https://projects.eclipse.org/projects/technology.microprofile/governance) 
   - [ ] Generated IP Log (For the [microprofile platform release](https://projects.eclipse.org/projects/technology.microprofile/generate-iplog))
   - [ ] [Email to PMC](mailto:technology-pmc@eclipse.org)
   - [ ] Start release review by [emailing EMO](mailto:EMO@eclipse-foundation.org)
   - [ ] Summary that a Compatible Implementation is complete, passes the TCK, and that the TCK includes sufficient coverage of the specification.
- [ ] For a [Progress Review](https://www.eclipse.org/projects/handbook/#6_3_5_Progress_Review), that sufficient progress has been made on a Compatible Implementation and TCK, to ensure that the spec is implementable and testable.

Note: If any item does not apply, check it and mark N/A below it.
