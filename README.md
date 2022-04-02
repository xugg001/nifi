# nifi
nifi相关开发
#从模板创建nifi组件项目
mvn archetype:generate -DarchetypeGroupId=org.apache.nifi -DarchetypeArtifactId=nifi-processor-bundle-archetype

如果无法下载nifi-nar-maven-plugin，可以添加apache的maven仓库
<mirror>
    <id>apache-repo</id>
    <name>Apache Repository</name>
    <mirrorOf>central</mirrorOf>
    <url>https://repository.apache.org/content/repositories/releases</url>
</mirror>