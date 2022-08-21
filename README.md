# Visual Paradigm plugin's template
## What is it
Template project of Visual Paradigm's plugin. Include:
* openapi.jar from Visual Paradigm 16.3
* Gradle build script with custom tasks, main of them:
  * vpInstallPlugin - install plugin into Visual Paradigm
  * vpCopyClasses - copy only classes, for hot-reload
* Template of plugin.xml

Plugin uses Kotlin as program language!

## How to use
1. Clone this repository
2. In settings.gradle.kts change project name
3. Develop your plugin and use Gradle task vpInstallPlugin to install it.

