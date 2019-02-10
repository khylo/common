Common files

To include add following to your build file.
Note jitpack run s the following command
mvn clean install -DskipTests

*Gradle*
```Gradle
  repositories {
        jcenter()
        maven { url "https://jitpack.io" }
   }
   
   dependencies {
         compile 'com.github.jitpack:gradle-simple:1.0'
   }
```

*Maven*
```Maven
<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>

<dependency>
			<groupId>com.github.khylo</groupId>
			<artifactId>common</artifactId>
			<version>master-SNAPSHOT</version>
		</dependency>   
```
