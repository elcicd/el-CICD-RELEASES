# el-CICD-RELEASES

Release repository for the el-CICD project.

This document is part of the el-CICD project, a complete CICD COTS solution for the OKD Container Platform.

Choose the release version, download the tar.xz artifact, and decompress the tar.xz file for a ready-to-configure version of el-CICD.  [Contents of the tzr.xz are listed below](#contents-of-release-tarxz).

**If you are new to el-CICD, we strongly suggest you work through the tutorial, which provides a broad understanding of how to configure, bootstrap, and use el-CICD and its numerous features.**

See [`el-CICD-docs`](https://github.com/elcicd/el-CICD-docs) project for full project documentation, including the tutorial.

Copyright (C) 2021 Evan "Hippy" Slatis  
email: hippyod -at- yahoo -dot- com

## Contents of Release tar.xz

The following source code and documentation directories are contained in the release tar.xz:

* [**el-CICD**](https://github.com/elcicd/el-CICD): The main el-CICD functional code.
* [**el-CICD-config**](https://github.com/elcicd/el-CICD-config): el-CICD configuration, where end users configure el-CICD.
* [**el-CICD-docs**](https://github.com/elcicd/el-CICD-docs): All relevant el-CICD documentation.

The source code for the following demonstration microservices and libraries for use with the tutorial should also be included:

* [**Test-CICD1**](https://github.com/elcicd/Test-CICD1): Demonstrates Release Regions for Python microservice.
* [**Test-CICD1-lib**](https://github.com/elcicd/Test-CICD1-lib): Demonstrates library build for Python library.
* [**test_CICD2**](https://github.com/elcicd/test_CICD2): Demonstrates custom OKD Templates for Python library.
* [**TeSt-CiCd3**](https://github.com/elcicd/TeSt-CiCd3): Demonstrates Python CronJob.
* [**Test_CICD4**](https://github.com/elcicd/Test_CICD4): Demonstrates multiple deployments of same Python microservice, environment specific patching, and an environment specific DB deployments.
* [**test-cicd-R**](https://github.com/elcicd/test-cicd-R): Demonstrates R microservice.
* [**test-cicd-stationdemo**](https://github.com/elcicd/test-cicd-stationdemo): Demonstrates Kubernetes Deployment, Ingress, Readiness Probe, and Java Maven build for Spring Boot microservice.
* [**test-cicd-stationdemo-lib**](https://github.com/elcicd/test-cicd-stationdemo-lib): Demonstrates library build for Java Maven Spring Boot library.

There is also an empty directory, **cicd-secrets**, which is meant to hold your credentials when bootstrapping.

## License

el-CICD is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation; either version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful, but **WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE**.  See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this library; if not, write to

```
    The Free Software Foundation, Inc.
    51 Franklin Street
    Fifth Floor
    Boston, MA
        02110-1301
```

This document is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode). To view a copy of this license, visit

http://creativecommons.org/licenses/by/4.0/

or send a letter to

```
  Creative Commons
  PO Box 1866
  Mountain View, CA
      94042, USA.
```
