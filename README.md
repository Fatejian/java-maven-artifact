# How to Become Rich

### Usage

Add the following to `pom.xml`:

```
<project ...>

    ...

    <repositories>
        <repository>
            <id>github-rich-repo</id>
            <name>The Rich Repository on Github</name>
            <url>https://fatejian.github.io/java-maven-artifact/maven-repo/</url>
        </repository>
    </repositories>

    <dependencies>
        <dependency>
            <groupId>com.itranswarp.rich</groupId>
            <artifactId>how-to-become-rich</artifactId>
            <version>1.0.0</version>
        </dependency>
    </dependencies>

    ...

</project>
```

### Sample code

```
Millionaire millionaire = new Millionaire();
System.out.println(millionaire.howToBecomeRich());
```
