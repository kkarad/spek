---
layout: other
title: Spek - Download
---

**Build Status**:
<a href="http://teamcity.jetbrains.com/viewType.html?buildTypeId=Spek_BuildAndTests">
<img src="http://teamcity.jetbrains.com/app/rest/builds/buildType:(id:Spek_BuildAndTests)/statusIcon"/>
</a>

### Source Code

If you want to download as source code, clone the [repository]({{ site.github }}).

### Binaries

Download the latest artifacts from the [Build Server](http://teamcity.jetbrains.com/viewType.html?buildTypeId=Spek_BuildAndTests)

### Maven and Gradle

Spek has not been released yet and as such is not made available on Maven Central. However you can download it from the [JetBrains Artifactory](http://repository.jetbrains.com).

To use it in Maven insert the following in your pom.xml file:


{% highlight xml %}
 
 <dependency>
     <groupId>org</groupId>
     <artifactId>spek</artifactId>
     <version>0.1-SNAPSHOT</version>
     <type>.xml</type>
 </dependency>

 <repositories>
    <repository>
      <id>jebrains-all</id>
      <url>http://repository.jetbrains.com/all</url>
    </repository>
  </repositories>

{% endhighlight %}

To use it in Gradle

{% highlight xml %}

testCompile 'org.spek:spek:0.1-SNAPSHOT'

{% endhighlight %}


