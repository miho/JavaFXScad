JFXScad
==========

[![Build Status](https://travis-ci.org/miho/JFXScad.svg?branch=master)](https://travis-ci.org/miho/JFXScad)

JavaFX 3D Printing IDE based on [JCSG](https://github.com/miho/JCSG).

![](/resources/img/screenshot-03.png)

![](http://thingiverse-production.s3.amazonaws.com/renders/0c/a0/c0/dc/53/IMG_20140329_201814_preview_featured.jpg)

## How to Build JFXScad

### Requirements

- Java >= 1.8
- Internet connection (dependencies are downloaded automatically)
- IDE: [Gradle](http://www.gradle.org/) Plugin (not necessary for command line usage)

### IDE (with Gradle Plugin)

Open the `JFXScad` [Gradle](http://www.gradle.org/) project in your favourite IDE (tested with NetBeans 8) and build it
by calling the `assemble` task.

### IDE (without Gradle Plugin)

#### Eclipse

Call the `eclipse` task from the command line and import the project to your workspace.

#### IntelliJ

Call the `idea` task from the command line and open the project.

### Command Line
Navigate to the [Gradle](http://www.gradle.org/) project (e.g., `path/to/JFXScad`) and enter the following command

#### Bash (Linux/OS X/Cygwin/other Unix-like shell)

    sh gradlew assemble
    
#### Windows (CMD)

    gradlew assemble
