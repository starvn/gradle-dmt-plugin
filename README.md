# Gradle DMT Plugin

[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-white.svg)](https://sonarcloud.io/dashboard?id=starvn_gradle-dmt-plugin)

## Introduction

A Gradle plugin that provides Maven like dependency management and exclusions. The
plugin provides a DSL to configure dependency management directly and by importing
existing Maven boms. Based on the configured dependency management, the plugin will
control the versions of your project's direct and transitive dependencies and will honour
any exclusions declared in the poms of your project's dependencies and any imported boms.

## Licence

Gradle DMT Plugin is open source software released under the [Apache 2.0 License][7].

[7]: https://www.apache.org/licenses/LICENSE-2.0.html