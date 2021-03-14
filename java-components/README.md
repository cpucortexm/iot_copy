# About java-components
This is the source repository for the Java components related to my Programming the Internet of Things book and Connected Devices IoT course. These are shell wrappers ONLY and are not a solution set (which is a separate repository, not yet released). For convenience to the reader, some basic functionality has already been implemented (such as configuration logic, consts, interfaces, a simple certificate file load utility, and test cases).

The code in this repository is largely comprised of shell classes that are designed to be implemented by the reader and are NOT solutions. These shell classes and their relationships respresent a notional design that aligns with the requirements listed in [Programming the IoT Requirements](https://github.com/orgs/programming-the-iot/projects/1). These requirements encapsulate the programming exercises presented in my book [Programming the Internet of Things: An Introduction to Building Integrated, Device to Cloud IoT Solutions](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401).

## How to use this repository
If you're reading [Programming the Internet of Things: An Introduction to Building Integrated, Device to Cloud IoT Solutions](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401), you'll see a tie-in with the exercises described in each chapter and this repository. Most of the code in the main src tree is NOT implemented by design. It's intended for you - as the reader of my book (and possibly a student in one of my IoT courses) - to implement by filling in the implementation details as you work through each exercise.

A solution set is available, although I haven't yet released it. Stay tuned for updates on this topic.

## This repository aligns to exercises Programming the Internet of Things
These components are all written in Java 11 (or higher), and correlate to the exercises designed for the Gateway Device Application (GDA) specified in my book [Programming the Internet of Things: An Introduction to Building Integrated, Device to Cloud IoT Solutions](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401).

## How to navigate the directory structure for this repository
The CURRENT* source repository is comprised of the following top level paths:
- [config](https://github.com/programming-the-iot/java-components/tree/alpha001/config): Contains basic configuration file(s).
- [exercises](https://github.com/programming-the-iot/java-components/tree/alpha001/exercises): Contains a directory structure for storing student lab module write-ups.
- [src/main/java](https://github.com/programming-the-iot/java-components/tree/alpha001/src/main/java): The main source tree for java-components. Keep in mind that most of these classes are shell representations ONLY and must be implemented as part of the exercises referenced above.
- [src/test/java](https://github.com/programming-the-iot/java-components/tree/alpha001/src/test/java): The test source tree for java-components. These are designed to perform very basic unit and integration testing of the implementation of the exercises referenced above. This tree is sectioned by part - part01, part02, part03, and part04 - which correspond to the structure of my book mentioned above.

Here are some other files at the top level that are important to review:
- [pom.xml](https://github.com/programming-the-iot/java-components/blob/alpha001/pom.xml): The Maven project configuration file, with relevant depedencies, etc.
- [README.md](https://github.com/programming-the-iot/java-components/blob/alpha001/README.md): This README.
- [LICENSE](https://github.com/programming-the-iot/java-components/blob/alpha001/LICENSE): The repository's LICENSE file.

Lastly, there are some '.' files pertaining to dev environment setup that might be useful (or not - if so, just delete them after cloning the repo):
- [.classpath](https://github.com/programming-the-iot/java-components/blob/alpha001/.classpath): The Eclipse IDE CLASSPATH configuration file for your Java environment that may / may not be useful for your own cloned instance.
- [.gitignore](https://github.com/programming-the-iot/java-components/blob/alpha001/.gitignore): The obligatory .gitignore that you should probably keep in place, with any additions that are relevant for your own cloned instance.
- [.project](https://github.com/programming-the-iot/java-components/blob/alpha001/.project): The Eclipse IDE project configuration file that may / may not be useful for your own cloned instance. Note that using this file to help create your Eclipse IDE project will result in the project name 'piot-java-components' (which can be changed, of course).
- [.settings/org.eclipse.jdt.core.prefs](https://github.com/programming-the-iot/java-components/blob/alpha001/.settings/org.eclipse.jdt.core.prefs): The Eclipse IDE settings file, which is only included to assist with setting up an Eclipse dev environment related to my IoT courses and book exercises, which may / may not be useful for your own cloned instance.

* NOTE: The directory structure and all files are subject to change based on feedback I receive from readers of my book and students in my IoT class, as well as improvements I find to be helpful for overall repo betterment.

# Other things to know

## Pull requests
PR's are disabled while the codebase is being developed.

## Updates
Much of this repository, and in particular unit and integration tests, will continue to evolve, so please check back regularly for potential updates.

# REFERENCES
This repository has external dependencies on other open source projects. I'm grateful to the open source community and authors / maintainers of the following libraries:

Core exercises:

- [californium-core](https://github.com/eclipse/californium)
  - Reference: Eclipse Foundation, Inc. californium. (2020) [Online]. Available. https://github.com/eclipse/californium.
- [californium/scandium-core](https://github.com/eclipse/californium/tree/master/scandium-core)
  - Reference: Eclipse Foundation, Inc. scandium-core. (2021) [Online]. Available. https://github.com/eclipse/californium/tree/master/scandium-core.
- [commons-cli](https://commons.apache.org/proper/commons-cli/)
  - Reference: The Apache Software Foundation. Commons CLI. (2019) [Online]. Available. https://commons.apache.org/proper/commons-cli/.
- [commons-configuration](commons.apache.org/proper/commons-configuration/)
  - Reference: The Apache Software Foundation. Commons Configuration. (2020) [Online]. Available: https://commons.apache.org/proper/commons-configuration/.
- [eclipse paho](https://www.eclipse.org/paho/)
  - Reference: Eclipse Foundation, Inc. paho-mqtt-java. (2020) [Online]. Available: https://github.com/eclipse/paho.mqtt.java.
- [gson](https://github.com/google/gson)
  - Reference: Google. Gson. (2008) [Online]. Available: https://github.com/google/gson.
- [javax mail](https://javaee.github.io/javamail/)
  - Reference: Oracle. JavaMail. (2020) [Online]. Available: https://javaee.github.io/javamail/.
- [jedis](https://github.com/redis/jedis)
  - Reference: J. Leibiusky. jedis. (2020) [Online]. Available: https://github.com/redis/jedis.
- [junit](https://github.com/junit-team/junit4/)
  - Reference: JUnit. JUnit. (2020) [Online]. Available: https://junit.org/junit4/.
- [ubidots](https://github.com/ubidots/ubidots-java)
  - Reference: G. Angulo et al. ubidots-java. (2020) [Online]. Available: https://github.com/ubidots/ubidots-java.

NOTE: This list will be updated as others are incorporated.

# DISCLAIMER
DISCLAIMER: This code base is still under active development - some tests and code samples may be broken.

# LICENSE
Please see [LICENSE](https://github.com/programming-the-iot/java-components/blob/alpha001/LICENSE) if you plan to use this code.
