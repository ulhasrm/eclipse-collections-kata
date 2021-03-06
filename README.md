<!--
  ~ Copyright (c) 2019 Goldman Sachs and others.
  ~ All rights reserved. This program and the accompanying materials
  ~ are made available under the terms of the Eclipse Public License v1.0
  ~ and Eclipse Distribution License v. 1.0 which accompany this distribution.
  ~ The Eclipse Public License is available at http://www.eclipse.org/legal/epl-v10.html
  ~ and the Eclipse Distribution License is available at
  ~ http://www.eclipse.org/org/documents/edl-v10.php.
  -->
[![][travis img]][travis]
[![][license-epl img]][license-epl]
[![][license-edl img]][license-edl]

<a href="https://www.eclipse.org/collections/"><img src="https://github.com/eclipse/eclipse-collections-kata/blob/master/docs/shared/eclipse-collections-logo.png" height="50%" width="50%"></a>
  
Eclipse Collections Kata 
========================
A [kata](https://en.wikipedia.org/wiki/Kata) is an exercise in martial arts. 
A [code kata](http://codekata.com/) is an exercise in programming which helps hone your skills through practice and repetition. 
The Eclipse Collections Kata is a fun way to help you learn idiomatic Eclipse Collections usage. 
This particular kata is set up as a series of unit tests which fail. 
Your task is to make them pass, using Eclipse Collections.

Initialize Kata
---------------
Clone this repo or simply download and extract the master [zip file](https://github.com/eclipse/eclipse-collections-kata/archive/master.zip), 
then follow the instructions below for your IDE/platform. 


### Eclipse users

You can import the project from "Import" => "General" => "Existing Projects into Workspace".
Select "eclipse-collections-kata" directory as root directory, 
make sure to choose "Search for nested projects" option and finish.
### IntelliJ IDEA users

Initialize IntelliJ IDEA project with the command below. 

You can open the project from "File" => "Open..." => choose "eclipse-collections-kata" folder.

### NetBeans users

##### Linux/Mac/Windows:

_open as a Maven project_

You can open the project directly from "File" => "Open Project..." => choose "eclipse-collections-kata" folder.
In the "Open Project" dialog you might select the option "Open Required Projects" to automatically open the two modules.

Work on Kata exercises
----------------------
There are two separate katas under different directories (Company Kata and Pet Kata).

```
company-kata/src/tests
pet-kata/src/tests
```

To get started, you can refer to slides for the [Instruction and Pet Kata](http://eclipse.github.io/eclipse-collections-kata/) to learn how to set-up Kata, basic features of Eclipse Collections corresponding to each Pet Kata exercise and then solutions. 

To learn wider range of functionalities, slides for [Company Kata](http://eclipse.github.io/eclipse-collections-kata/company-kata) are now available online as well. 

Check out the [pet kata solutions module tests](https://github.com/eclipse/eclipse-collections-kata/tree/master/pet-kata-solutions/src/test/java/org/eclipse/collections/petkata) for your reference.

Enjoy happy learning with Eclipse Collections Kata!


Reference Guide
---------------
The [Eclipse Collections Reference Guide](https://github.com/eclipse/eclipse-collections/blob/master/docs/guide.md) is a great way to get an overview of the extensive features available in the framework.


Presentations
-------------
The [API Design of Eclipse Collections](http://eclipse.github.io/eclipse-collections-kata/api-design) covers the design 
decisions that went into making Eclipse Collections and guiding its evolution from Java 4 through Java 9. 
The content of the presentation is also available in a convenient to read [markdown format](https://github.com/eclipse/eclipse-collections-kata/blob/master/docs/api-design/slides.md). 

[travis]:https://travis-ci.org/eclipse/eclipse-collections-kata
[travis img]:https://travis-ci.org/eclipse/eclipse-collections-kata.svg?branch=master

[license-epl]:LICENSE-EPL-1.0.txt
[license-epl img]:https://img.shields.io/badge/License-EPL-blue.svg

[license-edl]:LICENSE-EDL-1.0.txt
[license-edl img]:https://img.shields.io/badge/License-EDL-blue.svg
