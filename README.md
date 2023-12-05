# fj-lib-dep

Help generating dependency libraries

## Quickstart

Copy default artifact dependencies

`mvn clean install -P copy-dep`

Copy custom artifact dependencies

`mvn clean install -P copy-dep -DtargetGroupId=org.apache.xmlgraphics -DtargetArtifactId=fop -DtargetVersion=2.9`

output will be in folder :

`target/dependencies/`