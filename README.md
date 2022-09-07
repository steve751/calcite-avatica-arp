<!--
{% comment %}
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to you under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
{% endcomment %}
-->
[![Build Status](https://travis-ci.org/apache/calcite-avatica.svg?branch=main)](https://travis-ci.org/apache/calcite-avatica)
[![CI Status](https://github.com/apache/calcite-avatica/workflows/CI/badge.svg)](https://github.com/apache/calcite-avatica/actions)

# Druid Dremio ARP compatable JDBC

This Fork of Apache Calcite -- Avatica is intended for generating a JDBC driver for Apache Druid that is compatable with the Dremio ARP framework. See:  [Creating an ARP Connector](https://www.dremio.com/resources/tutorials/how-to-create-an-arp-connector/).

Current: [Druid ARP Connector](https://github.com/steve751/dremio-druid-connector).

# Quickstart JDBC Build :

$ git clone "https://github.com/steve751/calcite-avatica-arp"

$ cd calcite-avatica-arp

$ ./gradlew build

JDBC will be created as : calcite-avatica-arp/shaded/core/build/libs/avatica-x.x.x-SNAPSHOT-shadow.jar

# Apache Calcite -- Avatica

Apache Calcite's Avatica is a framework for building database drivers.

Avatica is a sub-project of [Apache Calcite](https://calcite.apache.org).

For more details, see the [home page](https://calcite.apache.org/avatica).

Release notes for all published versions are available on the [history
page](https://calcite.apache.org/avatica/docs/history.html).

