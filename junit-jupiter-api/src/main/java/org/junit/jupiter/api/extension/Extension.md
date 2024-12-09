* == marker interface -- for -- ALL extensions
  * marker == NO methods nor fields
  * ways to register an `Extension`
    * <em>declaratively</em> -- via -- `@ExtendWith`
      * requirements for the extension implementation
        * <em>default constructor</em> / NOT required to be `public`
    * <em>programmatically</em> -- via -- `@RegisterExtension`
      * requirements for the extension implementation
        * constructors
          * typically `public`, UNLESS the extension -- provides -- `static` factory methods
        * builder API -- as an alternative to -- constructors
      * <em>automatically</em> -- via -- `java.util.ServiceLoader` mechanism
        * requirements for the extension implementation
          * <em>default constructor</em> / MUST be `public`
