* == annotations -- for configuring a -- test suite | JUnit Platform
  * to run the test suites | JUnit4
    * `@RunWith(JUnitPlatform.class)` + "junit-platform-runner"
  * to run the test suites | JUnit5
    * `@Suite` + "junit-platform-suite-engine"
* other annotations
  * `@Select*` & `@Exclude*` -- control the -- contents of the suite 
  * `@Configuration*` -- pass -- additional configuration | suite