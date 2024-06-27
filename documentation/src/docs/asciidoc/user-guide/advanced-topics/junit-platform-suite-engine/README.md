# JUnit Platform Suite Engine
* allows
    * about suites of tests | _any_ test engine
        * declarative definition &
        * execution
## Setup
* artifacts -- Check '../apendix/dependency-metadata'  <<dependency-metadata>> --
    * alternatives
        * alternative 1
            * `junit-platform-suite-api` / `<scope>test</scope>`
            * `junit-platform-suite-engine` / `<scope>test</scope>` & `<scope>runtime</scope>` -- TODO: Check if it's fine bot --
                * -> implementation of the `TestEngine` API -- for -- declarative test suites
        * alternative 2
            * `junit-platform-suite` /  `<scope>test</scope>`
            * 1+= other test engine & its dependencies | classpath
* Transitive Dependencies
    * `junit-platform-suite-commons` in _test_ scope
    * `junit-platform-launcher` in _test_ scope
    * `junit-platform-engine` in _test_ scope
    * `junit-platform-commons` in _test_ scope
    * `opentest4j` in _test_ scope

## Examples
* `@Suite`
    * if you mark a class with `@Suite` -> test suite on the JUnit Platform
        * -> you can control it via  -- Check [suite-api-package](https://javadoc.io/doc/org.junit.platform/junit-platform-suite-api/latest/org/junit/platform/suite/api/package-summary.html) --
            * selector annotations
            * filter annotations
    * Check '{testDir}/example/SuiteDemo.java'
      * Go to `../documentation` and run `mvn test`
        * Problems:
          * Problems1: "package org.junit.jupiter.api.extension does not exist"
            * Solution: TODO:
