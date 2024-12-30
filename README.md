<p align="center">  
    <img src="https://i.imgur.com/SL6evf0.png" width=1012 height=306>    
</p>

## 🔰 Introduction

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent tincidunt lobortis est sit amet malesuada. Sed facilisis consectetur molestie. Vestibulum metus sapien, aliquet ac finibus quis, finibus vitae enim. Donec in lorem ut turpis varius commodo ut eu purus. Vivamus nec ligula purus. Nullam aliquet fermentum sem, nec iaculis neque accumsan ut. Sed elit turpis, pulvinar vitae dictum ut, tristique in metus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Morbi in dui sem. Suspendisse auctor velit nec massa semper, a mattis massa laoreet. Donec ut nibh fringilla, aliquam ex nec, suscipit nulla. Nullam id accumsan est, sit amet rutrum metus.

## :t Getting Started

> [!IMPORTANT]
> Requirements:
> - Java 21 (LTS)

🪶 Maven:
```xml
<repository>
    <id>lorem-ipsum</id>
    <url>https://lorem.ipsum/</url>
</repository>
```

```xml
<dependency>
    <groupId>ipsum.lorem</groupId>
    <artifactId>lorem-ipsum</artifactId>
    <version>1.0.0</version>
</dependency>
```

🐘 Gradle:
```groovy
maven {         
    url = uri("https://lorem.ipsum/")
}
```

```groovy
dependencies {
    implementation 'ipsum.lorem:lorem-ipsum:1.0.0'
}
```

## Building
The build management tool used for this project is [Apache Maven](https://maven.apache.org/). Executing the following command will install the compiled artifact into your local repository if no critical issues occur during any of the lifecycle phases.
```
mvn clean install
```
