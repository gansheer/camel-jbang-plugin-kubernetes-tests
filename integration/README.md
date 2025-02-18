# How to use for WIP

jbang alias add --name citrus /home/gfournie/work/sources/gansheer/citrus/tools/jbang/src/main/java/main/CitrusJBang.java
jbang alias add -Dcamel.jbang.version=4.11.0-SNAPSHOT --name camel /home/gfournie/work/sources/github/camel/dsl/camel-jbang/camel-jbang-main/src/main/jbang/main/CamelJBang.java

jbang --fresh --deps=org.citrusframework:citrus-camel:4.6.0-SNAPSHOT --deps=org.citrusframework:citrus-kubernetes:4.6.0-SNAPSHOT citrus run route.it.yaml