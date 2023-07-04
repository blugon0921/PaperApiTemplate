# PaperApiTemplate

[![ItemHelper](https://img.shields.io/badge/PaperApiTemplate-1.0.0-blue.svg)]()
<br><br>
[![Java](https://img.shields.io/badge/Java-17-FF7700.svg?logo=java)]()
[![Kotlin](https://img.shields.io/badge/Kotlin-1.8.21-186FCC.svg?logo=kotlin)]()
[![PaperMC](https://img.shields.io/badge/PaperMC-1.20.1-222222.svg)]()


<br>
<br>

### Use API


## Maven
```xml
<repositories>
    <repository>
        <id>kr.blugon</id>
        <url>https://repo.blugon.kr/repository/maven-public/</url>
    </repository>
</repositories>

<dependencies>
    <dependency>
        <groupId>kr.blugon</groupId>
        <artifactId>PaperApiTemplate</artifactId>
        <version>VERSION</version>
    </dependency>
</dependencies>
```


## Groovy
```gradle
repositories {
    maven { 'https://repo.blugon.kr/repository/maven-public/' }
}

dependencies {
    implementation 'kr.blugon:PaperApiTemplate:VERSION'
}
```

## Kotlin DSL
```gradle
repositories {
    maven("https://repo.blugon.kr/repository/maven-public/")
}

dependencies {
    implementation("kr.blugon:PaperApiTemplate:VERSION")
}
```
