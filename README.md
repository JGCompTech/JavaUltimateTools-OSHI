# JavaUltimateTools OSHI v2.0.0
[![Build Status](https://travis-ci.org/JGCompTech/JavaUltimateTools-OSHI.svg?branch=master)](https://travis-ci.org/JGCompTech/JavaUltimateTools-OSHI) [![CircleCI](https://circleci.com/gh/JGCompTech/JavaUltimateTools-OSHI.svg?style=svg)](https://circleci.com/gh/JGCompTech/JavaUltimateTools-OSHI) [![Language grade: Java](https://img.shields.io/lgtm/grade/java/g/JGCompTech/JavaUltimateTools-OSHI.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/JGCompTech/JavaUltimateTools-OSHI/context:java) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.jgcomptech.tools/java-ultimate-tools-oshi/badge.svg?style=flat-square)](https://maven-badges.herokuapp.com/maven-central/com.jgcomptech.tools/java-ultimate-tools-oshi/) [![Javadocs](http://www.javadoc.io/badge/com.jgcomptech.tools/java-ultimate-tools-oshi.svg?style=flat-square)](http://www.javadoc.io/doc/com.jgcomptech.tools/java-ultimate-tools-oshi)

Java Ultimate Tools OSHI allows management and the return of read-only info about your computer’s OS and hardware. It contains the following:
- Operating System Info - The OS Info classes return info about the currently installed OS and software.
The retrievable info includes, Name, Version including build number, Manufacturer, If OS is a server, If OS is 32 or 64 bit
and Enhanced info from the registry if running a Windows OS.
- Hardware Info - The Hardware Info classes return info about the currently installed hardware.
The retrievable info includes, BIOS Release Date, Version and Vendor, Internal and External IP Address, OEM Name and Product Name,
Processor Name and Number of Cores, RAM size and Hard Drive Info.
- And Much More!

**NOTE: This Project Has Now Been Updated To Use Java 11!!!**

**NOTE: This project used to be merged with the [JavaUltimateTools](https://github.com/JGCompTech/JavaUltimateTools) project but, to allow for ease of development process and the ability to update each section sepeately, it made sense to create seperate libraries.
This project has a dependancy on the JavaUltimateTools base library and, if using a package manager, will be auto-imported.**

# Development
Want to contribute? Great!
Any help with development is greatly appreciated. If you want to add something or fix any issues please submit a pull request and if it is helpful it may be merged. Please check out our [Code of Conduct for Contributors](https://github.com/JGCompTech/JavaUltimateTools/blob/master/code-of-conduct.md).

# Documentation
The documentation for JUT is currently a work in progress and new changes will be occurring soon.
To access the documentation site go to: [https://javatools.jgcomptech.com](https://javatools.jgcomptech.com).
If you would like to view the JavaDoc info, it is hosted at [github.io(Current GitHub Branch)](https://jgcomptech.github.io/JavaUltimateTools-OSHI/) and at [javadoc.io(Current Maven Release)](http://www.javadoc.io/doc/com.jgcomptech.tools/java-ultimate-tools-oshi). The github.io version is what is stored in the doc folder in the project.

# Download
**[Download v2.0.0](https://github.com/JGCompTech/JavaUltimateTools-Databases/releases/tag/v2.0.0)**

The changelog can be found [here](https://javatools.jgcomptech.com/changelog/)

# Using with Maven
If you are familiar with [Maven](http://maven.apache.org), add the following XML
fragments into your pom.xml file. With those settings, your Maven will automatically download our library into your local Maven repository, since our libraries are synchronized with the [Maven central repository](http://repo1.maven.org/maven2/com/jgcomptech/tools/java-ultimate-tools/).

    <dependencies>
       <dependency>
          <groupId>com.jgcomptech.tools</groupId>
         <artifactId>java-ultimate-tools-oshi</artifactId>
         <version>2.0.0</version>
       </dependency>
    </dependencies>

# License
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

JavaUltimateTools by J&G CompTech is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

&copy;2020 J&amp;G CompTech
