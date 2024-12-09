* `RepetitionInfo` 
  * uses
    * inject information about the current repetition of a repeated test | 
      * `@RepeatedTest`
      * `@BeforeEach`
        * ONLY if the corresponding test method -- is of type -- `@RepeatedTest`
          * otherwise -> `org.junit.jupiter.api.extension.ParameterResolutionException` 
      * `@AfterEach`
        * ONLY if the corresponding test method -- is of type -- `@RepeatedTest`
          * otherwise -> `org.junit.jupiter.api.extension.ParameterResolutionException`
  * if a method parameter -- is of type -- `RepetitionInfo` -> JUnit -- will supply an -- instance of `RepetitionInfo` / corresponding to the 
    * current repeated test
  * TODO: