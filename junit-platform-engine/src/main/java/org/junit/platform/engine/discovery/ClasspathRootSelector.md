* := `DiscoverySelector` / selects a classpath root
  * uses
    * `TestEngine` searches for class or resources | this classpath
  * class path must be | `Thread.getContextClassLoader()` 's class path / thread used by this selector