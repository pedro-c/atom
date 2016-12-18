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
1. Write short units of code:
   * Atom as a bad perfomance on this test. Maybe we can explain this results based on the fact that atom is a open-source project. So, we have a lot of contributors that have different styles of programming.
2. Write simple units of code:
   * Atom also has a bad result on this test. So, bettercodehub software measure complexity by counting the number of possible paths through a piece of code. The greater the number of paths, the more complex a piece of code is.  I think these results have the same explanation from the previous point, but we can add a little more, if we look to the files that bettercodehub indicates that don´t have simple units of code, most of them are build, script files.
3. Write code once:
   * The first positive result. Atom has very little code duplicated. If we analyze the results we can see that most of the duplicated code comes from a file called text-editor-component-spec.js , a file with many lines and big units. The purpose of this file is to test the rendering of the text editor. Therefore, it is not a core software file.
4. Keep unit interfaces small:
   * Another good result from atom software. We can explain this results based on the two programming languages ​​most used in the atom. This languages are javascript and typescript, two objected-oriented programming languages, this types of languages are very good to keep the number of parameters low, using and abusing objects.
5. Separate concerns in modules:
   *
6. Couple architecture components loosely;
7. Keep architecture components balanced;
8. Keep your codebase small;
9. Automate tests;
10. Write clean code;


[![BCH compliance](https://bettercodehub.com/edge/badge/pedro-c/atom)](https://bettercodehub.com)

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
