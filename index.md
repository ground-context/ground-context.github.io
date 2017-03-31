---
title: Ground - Open-source, vendor-neutral data context services.
layout: default
---

<img src="assets/images/logo.png" alt="Ground" width="25%" /><br/>

[![Build Status](https://travis-ci.org/ground-context/ground.svg?branch=master)](https://travis-ci.org/ground-context/ground)
[![codecov](https://codecov.io/gh/ground-context/ground/branch/master/graph/badge.svg)](https://codecov.io/gh/ground-context/ground)
[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


Ground is an open-source, vendor-neutral data context service under development
in [UC Berkeley](https://berkeley.edu)'s [RISE
Lab](http://rise.cs.berkeley.edu). *Data context* is all of the information
surrounding the use of data in an organization, and Ground enables users to
understand **what** data they have, **who** is using that data, **when** and
**how** data is changing, and to & from **where** the data is moving. We
believe that data context services are broadly applicable, including use cases
in data inventory, model-specific interpretation, workflow reproducibility,
interoperability, and collective governance.  Ground is based on a versioned,
graph data model. To learn more about the design principles behind Ground,
please look at our [CIDR 2017](http://cidrdb.org/cidr2017)
[publication](http://cidrdb.org/cidr2017/papers/p111-hellerstein-cidr17.pdf).

The Ground project is a community effort and includes collaborators from
[Capital One](https://capitalone.com), [Awake
Networks](http://www.awakenetworks.com/), [Skyhigh
Networks](https://www.skyhighnetworks.com/),
[LinkedIn](https://www.linkedin.com), [Cloudera](https://www.cloudera.com), and
[Trifacta](http://www.trifacta.com).

## Getting Started

We currently do not have any releases for the project. To get started with the
project, you can download and build from source:

```bash
$ git clone https://github.com/ground-context/ground
$ cd ground
$ mvn clean package -DskipTests
# start the server; configuration options can be found in conf/config.yml
$ java -jar target/ground-0.1-SNAPSHOT.jar server conf/config.yml
```

## Contributing

The project is currently in a pre-alpha stage. We welcome any and all input,
contributions, and feedback. The easiest way to get in touch is to [open an
issue on Github](https://github.com/ground-context/ground/issues/new) or to
submit a pull request. You can also email vikrams AT berkeley DOT edu.

You can find a list of open issues on the [Ground
JIRA](ground.atlassian.net/projects/GROUND/issues).

