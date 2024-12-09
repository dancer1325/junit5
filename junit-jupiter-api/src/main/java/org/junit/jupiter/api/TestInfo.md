* `TestInfo`
  * uses
    * inject information about the current test or container | 
      * `@Test`
      * `@RepeatedTest`,
      * `@ParameterizedTest`
      * `@TestFactory`
      * `@BeforeEach`
      * `@AfterEach`
      * `@BeforeAll`
      * `@AfterAll`
  * if a method parameter -- is of type -- `TestInfo` -> JUnit -- will supply an -- instance of `TestInfo` / corresponding to the 
    * current test or
    * current container
  * `String getDisplayName();`
    * display name
      * of the current
        * test or
        * container
      * allowed
        * default one
          * TODO:
        * custom configured
          * TODO:
    * TODO: