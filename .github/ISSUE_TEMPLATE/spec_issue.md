---
name: Specification Review Issue
about: Start a request for a specification release
title: '[MP Component] [Version] Specification Review'
labels: 'Release Review'
assignees: ''

---

**Specification issue template**

When creating a specification project release review, create an issue in the [MicroProfile-WG repository](https://github.com/microprofile/microprofile-wg) repo with the content defined as follows.
- [ ] Specification name and version
- [ ] Add the label `Release Review`
- [ ] Naming conventions for artifacts:
   - [ ] Specification PDF in the form of microprofile-_project_-spec-_version_.pdf
   - [ ] Specification HTML in the form of microprofile-_project_-spec-_version_.html
   - _project_ is the microprofile specification short project name (config, health, ...)
   - _version_ is the two digit x.y version of the specification
<p>

- [ ] The Nexus Staging links (orgeclipsemicroprofile-NNNN where NNNN is the staging repository id) (eg, https://<i></i>oss.sonatype.org/content/repositories/orgeclipsemicroprofile-NNNN/org/eclipse/microprofile/config/) which contain all the binaries and relevant documentation:
   - [ ] [Staging Repo](add link)
   - [ ] [Spec PDF](add link)
   - [ ] [Spec HTML](add link)
   - [ ] [Javadoc](add link)
   - [ ] [API Jar](add link)
   - [ ] [TCK Jar](add link)
<p>

- [ ] A link in the Eclipse downloads sections is still available for specs and apidocs:
   - [ ] https://download.eclipse.org/microprofile/staging/microprofile-_project_-_version_/
   - [ ] An apidocs directory containing the javadoc associated with the API jar.
<p>

- [ ] Summary that a Compatible Implementation is complete, passes the TCK, and that the TCK includes sufficient coverage of the specification.
     - [ ] [Compatible Certification Request] (add link of Compatible Certification Request in the corresponding spec repo (e.g. MicroProfile Config))
<p>

- [ ] [Release Review](https://www.eclipse.org/projects/handbook/#release-review)
  - [ ] Follow [governance process](https://projects.eclipse.org/projects/technology.microprofile/governance) and create/update release record
    - [Component Release Record](add link to the release record)
  - [ ] [Email to PMC](mailto:technology-pmc@eclipse.org) (more info [here](https://docs.google.com/document/d/1DFuh3rINWAZQpHpXnB_QM02tAXlI4KwbLjVBk9rX9HA/edit))
  - [ ] Start release review by [emailing EMO](mailto:EMO@eclipse-foundation.org) (more info [here](https://docs.google.com/document/d/1euy5ezuSpa6Xn4qV7MTXCWCMJIn16GYiiO-U7H6R-1w/edit)) 
  - [ ] A member of Steering Committee initiates the ballot by sending an email to [microprofile-wg] (mailto:microprofile-wg@eclipse.org) (more info [here](https://docs.google.com/document/d/1ivzeL4mdqZPwyQR6e5GtCv81F_ZfLOpsg8FaZUoDDuc/edit#heading=h.6e35ro9vzyji))
   - [ ] After the voting has ended, email [microprofile-wg] (mailto:microprofile-wg@eclipse.org) with the ballot result (more info [here](https://docs.google.com/document/d/1wISp-yRzQZNOHULNekxxg1U18be3v-3CRUswklcpmr8/edit))
  