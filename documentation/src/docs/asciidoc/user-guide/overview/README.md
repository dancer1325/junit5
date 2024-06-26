* JUnit5
  * == JUnit Platform + JUnit Jupiter + JUnit Vintage
    * JUnit Platform
      * allows
        * launching testing frameworks | JVM
      * provides
        * `{TestEngine}` API
          * uses
            * develop a testing framework
        * Console Launcher
          * uses
            * launching the console from the CLI
        * JUnit-Platform-Suite-Engine
          * uses
            * run custom test suite -- via -- >= 1 test engines
      * there is first-class support of it, in IDEs
    * JUnit Jupiter
      * == programming model + extension model
        * uses
          * writing tests & extensions
      * provides
        * `{TestEngine}`
          * uses
            * run Jupiter-based tests
    * JUnit Vintage
      * provides
        * `{TestEngine}`
          * uses
            * run JUnit3 & JUnit4 -based tests
      * requirements
        * JUnit 4.12+
  * TODO:
  * [features](https://junit.org/junit5/docs/current/user-guide/#overview-getting-started-features)
* TODO: