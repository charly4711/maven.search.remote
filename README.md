NetBeans plugin to search Maven artifacts directly in the Maven Central Repository.

Using this plugin will save you about 1GB of disk space.

Download plugin from your IDE's Plugin Portal or manually from http://plugins.netbeans.org/plugin/68415/maven-remote-search

[JAXEnter article about the plugin](https://jaxenter.com/netbeans/keep-netbeans-nimble-with-maven-remote-search)

Notes:
 * To use it, disable Maven indexing in NB preferences, then
   * have Maven central as a direct repo, i. e. no mirrors
   * When searching the repo from the Services tab, make sure to check the name checkbox
   * When adding a Maven dependency, use as you would normally

