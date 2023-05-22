# spring-boot-web-archetype

clone on local: mvn clone https://github.com/proteinshaikh/spring-boot-web-archetype.git
cd spring-boot-web-archetype
mvn clean install
mvn archetype:generate -DarchetypeGroupId=com.github.spring-boot-archetypes -DarchetypeArtifactId=spring-boot-web-quickstart  -DarchetypeVersion=1.0.0 -DgroupId=your.group.id -DartifactId=your.app.name  -Dversion=1.0.0-SNAPSHOT -DinteractiveMode=false
 
