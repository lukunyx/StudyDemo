maven-archetypes-demo
=====================
     
# 1安装到本地

	mvn clean install
     
     
# 2生成到本地archetype文件中

	mvn archetype:crawl 

# 3.替换或者安装
    mvn install:install-file -DgroupId=org.apache.maven.archetypes -DartifactId=maven-archetype-quickstart -Dversion=1.1 -Dpackaging=jar -Dfile=d:\down\maven-archetype-quickstart-1.1.jar