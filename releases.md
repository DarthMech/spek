---
layout: default
title: Spek - Releases
---

## Releases

**Current release**: <a href="{{ site.data.release.latest.notes }}">{{ site.data.release.latest.version }}</a> Build: {{ site.data.release.latest.build }}. Works with Kotlin {{ site.data.release.latest.kotlinVersion }}

The current stable release of Spek. 

**Prior releases**

<ul>
{% for entry in site.data.releases.list %}
<li><a href="{{ entry.notes }}">{{ entry.version }}</a> Build: {{ entry.build }}. Kotlin: {{ entry.kotlinVersion }}</li>
{% endfor %}
</ul>

## Fire hose

<a href="http://teamcity.jetbrains.com/viewType.html?buildTypeId=Spek_BuildAndTests">
<img src="http://teamcity.jetbrains.com/app/rest/builds/buildType:(id:Spek_BuildAndTests)/statusIcon"/>
</a>

The master branch on GitHub is the active development branch. Stability is not guaranteed. 
 
### Source Code

If you want to download as source code, clone the [repository](https://github.com/jetbrains/spek).

### Binaries

Download the latest artifacts from the [Build Server](https://teamcity.jetbrains.com/viewLog.html?buildId=853167&tab=buildResultsDiv&buildTypeId=Spek_BuildAndTests)


### Maven and Gradle

Spek is available on [Bintray](https://bintray.com/jetbrains/spek/spek) and [Maven Central](http://search.maven.org/).

For more information on how to set up your project using Maven or Gradle, please see [Setting up](http://jetbrains.github.io/spek/docs/latest/#_setting_up) in the documentation.
