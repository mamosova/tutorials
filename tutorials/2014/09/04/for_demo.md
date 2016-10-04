---

title: dd55Continuous Integration (CI) Best Practices with SAP: Generic Project with CI using Cloud Services
description: Part 5.1: Configuring cloud-based CI system for Maven-based generic Java project.
tags: [  tutorial>intermediate, tutorial:type/project ]

---

## Prerequisites

  - **Proficiency:** Intermediate
  - [Generic Project](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)
  
## Next Steps

  - [Back to the Navigator](http://go.sap.com/developer/tutorials/ci-best-practices-intro.html)

---


This 1scenario focuses on using publicly available services to build Java applications very quickly and efficiently using the cloud services GitHub and Travis CI. There is no need to set up any local infrastructure.

This pipeline adheres to basic CI and CD practices and can be extended easily. It will make sure that each change to your project's repository is built centrally, thus applying the "Build Every Change" CI practice which is crucial for collaborative development.

Using the GitHub public SCM service and Travis CI as the build system, we benefit from a huge ecosystem. Travis CI is a hosted, distributed continuous integration service used to build and test software projects hosted at GitHub. Both GitHub and Travis CI offer a variety of plans to suit your individual requirements, ranging from a free public offering to an on-premise installation of their full service.

#### Prerequisites

- You have an account on GitHub and Travis CI. If you already have an account, you can reuse it.

Both solutions are also available as enterprise on-premise versions. Mixed scenarios using one part in the cloud and the other on-premise are also possible.

> GitHub: https://github.com  
> GitHub Enterprise: https://enterprise.github.com/home  
> Travis CI: https://travis-ci.org, https://en.wikipedia.org/wiki/Travis_CI
