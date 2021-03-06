# Awesome refactoring

This repository is a curated list of refactoring-related resources.
Maintained by [Gregory Witek](https://www.gwitek.com/) as part of my work on [Refactoring Python Code](http://refactoringpython.com)

## Definition

There are a few definitions of refactoring (in practice very similar). The most popular is a 2-part definition by Martin Fowler:

_Refactoring (noun)_: a change made to the internal structure of software to make it easier to understand and cheaper to modify without changing its observable behavior.

_Refactoring (verb)_: to restructure software by applying a series of refactorings without changing its observable behavior.

## Books

* [Refactoring: Improving the Design of Existing Code](https://martinfowler.com/books/refactoring.html) by Martin Fowler and Kent Beck - *the* refactoring book, that presented the concept of refactoring to wider audience. Available in 2 editions: 1st contains examples in Java, 2nd in JavaScript. Must-read for any adept of software engineering
* [Refactoring Workbook](https://www.pearson.com/store/p/refactoring-workbook/P100001822014) by William C. Wake - a workbook that uses the 1st edition of "Refactoring" book as a reference
* [Refactoring to Patterns](https://www.goodreads.com/book/show/85041.Refactoring_to_Patterns) by Joshua Kerievsky - combines the practice of refactoring with object-oriented design patterns. The book presents real-life problems and solutions showing a total of 27 refactoring techniques
* [Refactoring: Ruby Edition](https://martinfowler.com/books/refactoringRubyEd.html) by Jay Fields, Shane Harvie, and Martin Fowler, with Kent Beck - the Ruby-specific edition of the original "Refactoring" book with a few techniques added and of course examples adapted so that they're more useful in Ruby
* [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) by Nate Mara (currently in early access program, as of March 2021) - this book focuses on iterative adoption of Rust via its interop mechanisms
* [Refactoring at Scale](https://www.oreilly.com/library/view/refactoring-at-scale/9781492075523/) by Maude Lemaire - this book talks about refactoring in large and complex codebases, with examples from author's experience at Slack
* [Refactoring TypeScript: Keeping Your Code Healthy](https://leanpub.com/refactoringtypescript) by James Hickey
* [Refactoring JavaScript: Turning Bad Code Into Good Code](https://refactoringjs.com/) by Evan Burchard
* [Refactoring for Software Design Smells](http://www.designsmells.com/) by Girish Suryanarayana, Ganesh Samarthyam, and Tushar Sharma
* [Refactoring to Collections](https://laravel-news.com/refactoring-to-collections) by Adam Wathan - this book (+ videos) focus on refactoring PHP code to use modern collection library (used, among others, by Laravel framework)
* [Refactoring Databases: Evolutionary Database Design](https://www.databaserefactoring.com/) by Pramod Sadalage - this book talks about refactoring on the database level instead of code level, 

## Websites

* [Refactoring.com](https://www.refactoring.com/) - part of [Martin Fowler's website](https://martinfowler.com/), contains a catalog of 60+ techniques; free version provides simple examples, paid version contains description, mechanics and more. Most of tecnhiques are available in the "Refactoring" book.
* [Refactoring Guru](https://refactoring.guru) - contains 60+ techniques, each with description, implementation and a simple example + around 20 code smells with description and suggested refactorings that help to get rid of it

## Articles

* [It's Not Refactoring, It's Untangling](http://www.codypowell.com/taods/2013/03/its-not-refactoring-its-untangling.html), by Cody Powell
* [What Are We Doing with All These Tests? (And, Refactoring)](https://www.obeythetestinggoat.com/book/chapter_philosophy_and_refactoring.html) by Harry J. W. Percival - this is part of the [Test-Driven Development with Python](https://www.obeythetestinggoat.com/pages/book.html) book that talks primarily about TDD, but also covers the topic of refactoring
* [Examples of Refactoring PHP Code for Better Readability](https://deliciousbrains.com/refactoring-php-code-better-readability/) by Gilbert Pellegrom - a few refactoring techniques with examples in PHP
* [Let's Not Misuse Refactoring](https://thoughtbot.com/blog/lets-not-misuse-refactoring) by German Velasco - interesting article that explores what do we really mean when we say that refactoring does not change observable behaviour of our code
* [Code Refactoring](https://devopedia.org/code-refactoring) by Arvind Padmanabhan - Devopedia article describing the concept and history of refactoring; it also provides answers to some common questions about the topic
* [Refactoring by the Book](https://www.thoughtworks.com/insights/blog/refactoring-book) by Marcos Matos - the article talks about refactoring while keeping tests green (almost) the whole time

## Others

* [How to justify code refactoring time?](https://softwareengineering.stackexchange.com/questions/157928/how-to-justify-code-refactoring-time) - discussion and advice on justifying refactoring (Stack Exchange)
* [History of Refactoring](https://wiki.c2.com/?HistoryOfRefactoring) - C2 wiki post about beginnings of refactoring (I am not sure how accurate it is regarding the first use of the term "refactoring")
