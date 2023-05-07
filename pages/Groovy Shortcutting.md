- #Groovy
- ```groovy
  apply plugin: 'application'
  apply(plugin: 'application)
  // is equal to
  apply([ plugin: 'application'])
  // and it means
  Map map = new HashMap();
  map.put( "plugins", "application" )
  ```