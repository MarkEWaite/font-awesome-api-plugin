# Font Awesome Jenkins Plugin

[![Jenkins Plugin](https://img.shields.io/jenkins/plugin/v/font-awesome-api.svg?label=latest%20version)](https://plugins.jenkins.io/font-awesome-api)
[![Jenkins Version](https://img.shields.io/badge/Jenkins-2.138.4-green.svg?label=min.%20Jenkins)](https://jenkins.io/download/)
![JDK8](https://img.shields.io/badge/jdk-8-yellow.svg?label=min.%20JDK)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Provides [Font Awesome](https://fontawesome.com) for Jenkins Plugins.

This plugin contains the latest [WebJars](https://www.webjars.org) release and corresponding Jenkins UI elements. 

## How to use the plugin

In order to use this JS library, add a maven dependency to your pom:
```xml
<dependency>
  <groupId>io.jenkins.plugins</groupId>
  <artifactId>font-awesome-api</artifactId>
  <version>[latest version]</version>
</dependency>
```

Then you can use Font Awesome SVG icons in your jelly files using the following snippet:
```xml
<j:jelly xmlns:fa="/font-awesome" >
  
  [...]
  <fa:svg-icon name="check-double" class="no-issues-banner"/>
  [...]

</j:jelly>
```
 
You can find several examples of Jenkins views that use Font Awesome in the 
[Warnings Next Generation plugin](https://github.com/jenkinsci/warnings-ng-plugin).

[![Jenkins](https://ci.jenkins.io/job/Plugins/job/font-awesome-api-plugin/job/master/badge/icon)](https://ci.jenkins.io/job/Plugins/job/font-awesome-api-plugin/job/master/)
[![GitHub Actions](https://github.com/jenkinsci/font-awesome-api-plugin/workflows/GitHub%20Actions/badge.svg)](https://github.com/jenkinsci/font-awesome-api-plugin/actions)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/jenkinsci/font-awesome-api-plugin.svg)](https://github.com/jenkinsci/font-awesome-api-plugin/pulls)
