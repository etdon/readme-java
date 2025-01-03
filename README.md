<p align="center">  
    <img src="https://i.imgur.com/aByxoG0.png" width=830 height=207>    
</p>

<div align="center">

![Universal](https://img.shields.io/badge/Universal-white?style=for-the-badge&logo=github&label=Platform&color=%230173b3)
![Java](https://img.shields.io/badge/Java-white?style=for-the-badge&logo=github&label=Language&color=%23b07219)
![Kotlin](https://img.shields.io/badge/Kotlin-white?style=for-the-badge&logo=kotlin&label=Language&color=%237F52FF)
![Apache Maven](https://img.shields.io/badge/Apache%20Maven-white?style=for-the-badge&logo=apache-maven&label=Building&color=%23C71A36)
![Gradle](https://img.shields.io/badge/Gradle-white?style=for-the-badge&logo=gradle&label=Building&color=%2302303A)
![MIT](https://img.shields.io/badge/MIT-white?style=for-the-badge&logo=github&label=License&color=%233fb911)

</div>

## 🔰 Introduction

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent tincidunt lobortis est sit amet malesuada. Sed facilisis consectetur molestie. Vestibulum metus sapien, aliquet ac finibus quis, finibus vitae enim. Donec in lorem ut turpis varius commodo ut eu purus. Vivamus nec ligula purus. Nullam aliquet fermentum sem, nec iaculis neque accumsan ut. Sed elit turpis, pulvinar vitae dictum ut, tristique in metus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Morbi in dui sem. Suspendisse auctor velit nec massa semper, a mattis massa laoreet. Donec ut nibh fringilla, aliquam ex nec, suscipit nulla. Nullam id accumsan est, sit amet rutrum metus.

## 🚀 Getting Started

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

<details>
  <summary>Latest snapshot</summary>

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
    <version>1.0.1-SNAPSHOT</version>
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
    implementation 'ipsum.lorem:lorem-ipsum:1.0.1-SNAPSHOT'
}
```

</details>

## 📦 Building
The build management tool used for this project is [Apache Maven][build_tool]. Executing the following command will install the compiled artifact into your local repository if no critical issues occur during any of the lifecycle phases.
```
mvn clean install
```

## 🫴 Contributing
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent tincidunt lobortis est sit amet malesuada. Sed facilisis consectetur molestie. Vestibulum metus sapien, aliquet ac finibus quis, finibus vitae enim. Donec in lorem ut turpis varius commodo ut eu purus. Vivamus nec ligula purus. Nullam aliquet fermentum sem, nec iaculis neque accumsan ut. Sed elit turpis, pulvinar vitae dictum ut, tristique in metus.

## 📄 License
The `lorem-ipsum` project is licensed under the [Lorem ipsum License][license].
```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent tincidunt lobortis est sit amet malesuada.
Sed facilisis consectetur molestie. Vestibulum metus sapien, aliquet ac finibus quis, finibus vitae enim.
Donec in lorem ut turpis varius commodo ut eu purus. Vivamus nec ligula purus.
Nullam aliquet fermentum sem, nec iaculis neque accumsan ut.
```

[build_tool]: https://maven.apache.org/
[license]: https://choosealicense.com/licenses/
