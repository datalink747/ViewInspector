View Inspector Plugin
=====================

[ ![Download](https://api.bintray.com/packages/xfumihiro/maven/ViewInspector/images/download.svg) ](https://bintray.com/xfumihiro/maven/ViewInspector/_latestVersion)

View inspection toolbar for android development.

![](images/sample.gif)

Features
--------

- Boundary
  - show outlines
  - show margins
  - show paddings

- Layer
  - [Scalpel](https://github.com/JakeWharton/scalpel) features

- Event
  - [Probe](https://github.com/lucasr/probe) features
  - Profile View Tree

- Logging
  - show view life-cycle events in logcat
![](images/log_view_event.png)

- Absolute ZERO effects on non-debug builds

Usage
-----

```groovy
buildscript {
  repositories {
    jcenter() // or mavenCentral()
  }

  dependencies {
    classpath 'com.github.xfumihiro.view-inspector:view-inspector-plugin:0.1.1'
  }
}

apply plugin: 'com.android.application'
apply plugin: 'view-inspector'
```

Snapshots of the development version are available in [Sonatype's `snapshots` repository][snap].

Inspirations & Dependencies
---------------------------
[Scalpel](https://github.com/JakeWharton/scalpel) by Jake Wharton

[Probe](https://github.com/lucasr/probe) by Lucas Rocha

[this article](https://sriramramani.wordpress.com/2015/05/06/custom-viewgroups/) by
Sriram Ramani

Toolbar fashion : [Telecine](https://github.com/JakeWharton/Telecine) by Jake Wharton

License
-------

    Copyright 2015 Fumihiro Xue

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

[snap]: https://oss.sonatype.org/content/repositories/snapshots/