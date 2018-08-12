# About

Maven repository hosting external dependencies for https://github.com/buchen/portfolio

## Content

### [SWTChart](http://www.swtchart.org/)

Library: org.swtchart_0.10.0.jar

License: [Eclipse Public License v1.0](http://www.eclipse.org/legal/epl-v10.html)

```xml
<dependency>
  <groupId>org.swtchart</groupId>
  <artifactId>org.swtchart</artifactId>
  <version>0.10.0</version>
</dependency>
```

### [TreeMapLib](http://code.google.com/p/treemaplib/) (Core)

Library: tm_core_0.0.4.jar

License: [Eclipse Public License v1.0](http://www.eclipse.org/legal/epl-v10.html)

```xml
<dependency>
  <groupId>de.engehausen</groupId>
  <artifactId>de.engehausen.treemap</artifactId>
  <version>0.0.4</version>
</dependency>
```

### [TreeMapLib](http://code.google.com/p/treemaplib/) (SWT)

Library: tm_swt_0.0.5.jar

License: [Eclipse Public License v1.0](http://www.eclipse.org/legal/epl-v10.html)

```xml
<dependency>
  <groupId>de.engehausen</groupId>
  <artifactId>de.engehausen.treemap.swt</artifactId>
  <version>0.0.5</version>
</dependency>
```

### [Fix Info.plist Maven Plugin](https://github.com/buchen/fix-info-plist-maven-plugin)
License: [Eclipse Public License v1.0](http://www.eclipse.org/legal/epl-v10.html)

```xml
<plugin>
  <groupId>name.abuchen</groupId>
  <artifactId>fix-info-plist-maven-plugin</artifactId>
  <version>1.3</version>
</plugin>
```

## Usage

Used by adding a new repository:

```xml
<repository>
	<id>portfolio-non-maven-dependencies</id>
	<url>http://buchen.github.io/maven-repo</url>
</repository>
```
