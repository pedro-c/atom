# Assignment 4

<a name="index"/>
## Index
1. [Introduction](#introduction)
2. [Software Maintainability](#software-maintainability)
3. [Implementation of a Feature](#Implementation-of-a-Feature)
  1. [Identification](#identification)
  2. [Implementation](#implementation)
  3. [Pull Request](#pull-request)
4. [Conclusion](#conclusion)

<a name="introduction"/>
## Introduction

<a name="software-maintainability"/>
## Software Maintainability

What is Software Maintainability?
>Software maintainability is defined as the degree to which an application is understood, repaired, or enhanced. Software maintainability is important because it is approximately 75% of the cost related to a project!

To discuss atom software maintainability, we use SIG metrics. There are eight different metrics. To measure how atom software does in relation to this metrics we use [Better Code Hub](https://bettercodehub.com). These are the results:

[![BCH compliance](https://bettercodehub.com/edge/badge/pedro-c/atom)](https://bettercodehub.com)

1. Write short units of code:
   * Atom as a bad perfomance on this test. Maybe we can explain this results based on the fact that atom is a open-source project. So, we have a lot of contributors that have different styles of programming.
2. Write simple units of code:
   * Atom also has a bad result on this test. So, bettercodehub software measure complexity by counting the number of possible paths through a piece of code. The greater the number of paths, the more complex a piece of code is.  I think these results have the same explanation from the previous point, but we can add a little more, if we look to the files that bettercodehub indicates that don´t have simple units of code, most of them are build, script files.
3. Write code once:
   * The first positive result. Atom has very little code duplicated. If we analyze the results we can see that most of the duplicated code comes from a file called text-editor-component-spec.js , a file with many lines and big units. The purpose of this file is to test the rendering of the text editor. Therefore, it is not a core software file.
4. Keep unit interfaces small:
   * Another good result from atom software. We can explain this results based on the two programming languages ​​most used in the atom. This languages are javascript and typescript, two objected-oriented programming languages, this types of languages are very good to keep the number of parameters low, using and abusing objects.
5. Separate concerns in modules:
   * Almost a perfect result. Atom is very well splitted in modules, is very easy to realize that, just browse the source code of the atom and you will notice a lot of folders with different functionality. This code division allows to reduce responsibilities of large modules, dividing responsibilities to smaller modules.
6. Couple architecture components loosely:
   * Good result from atom here. The explain here is very similar to the previous point. Atom reaches this by minimizing the relative amount of code within modules that is exposed to (receive calls from) modules in other components. And independent components allow isolated maintenance.
7. Keep architecture components balanced:
   * Another positive result. This is accomplish based on the atom components architeture. A well-balanced software architecture is one with not too many and not too few components, with sizes that are approximately equal. And atom is very well divided, and is very easy to locate code and doing a isolated maintenance.
8. Keep your codebase small:
   * Another good result. For a very large project like atom is, their codebase is very small. A small codebase allows a better maintainability and its easy to understand for a programmer.
9. Automate tests:
   * A negative result from atom here. Bettercodehub software says that atom has 0% test code percentage. This is a lie, atom code is well covered with tests, like was explain on the previous [report](https://github.com/pedro-c/atom/blob/ESOF-Docs/ESOF%20-%20docs/4%20-%20Verification%20and%20Validation.md). Bettercodehub software most likely do not recognize software testing on websites, and atom uses three websites to test their software.
10. Write clean code:
     * To finish, another good result. By navigating on atom source code we understand why. Atom code doesn´t has useless comments, commented code blocks, magic constants, and so on.

After analyzing the results on atom software we can conclude that atom code is very maintainable and allows new implementation very easily.A very good result given that the atom is a open-source project.

PS: If you cannot open the results on the bettercodehub website use this [link](https://github.com/pedro-c/atom/blob/ESOF-Docs/ESOF%20-%20docs/res/atomBetterCodeHubAnalysis.pdf)

<a name="Implementation-of-a-Feature"/>
## Implementation of a Feature

<a name="identification"/>
### Identification

<a name="implementation"/>
### Implementation

<a name="pull-request"/>
### Pull Request

<a name="conclusion"/>
## Conclusion


## Contributions

  Maria João Mira Paulo : 25%;

  Nuno Ramos : 25%;

  Pedro Costa : 25%;

  Ricardo Neves : 25%;
