# Txuritan's Repo

## Usage

### Maven
```xml
<repository>
    <name>Txuritan's Repo</name>
    <url>https://txuritan.github.io/maven-repository/</url>
</repository>
```

### Gradle
Normal Gradle
```groovy
repositories {
    maven {
        name "Txuritan's Repo"
        url "https://txuritan.github.io/maven-repository/"
    }
}
```

Gradle Kotlin DSL
```kotlin
import java.net.URI

repositories {
    maven {
        name = "Txuritan's Repo"
        url = URI("https://txuritan.github.io/maven-repository/")
    }
}
```

### SBT
```scala
resolvers += "Txuritan's Repo" at "https://txuritan.github.io/maven-repository/"
```

## Current Libraries
**Group** *Artifact* Version

  - **com**
    - **github**
      - **txuritan**
        - *txcore*
          - 1.11.2-17.3.21
    - **nagiik**
      - **metal**
        - *metalliferous*
          - 1.11.2-17.5.3.0001a
  - **vazkii**
    - **autoreglib**
      - *AutoRegLib*
        - 1.1-7
        - 1.1-8

