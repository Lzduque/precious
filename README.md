## PRECIOUS

This project was born from one idea: Solve a Problem. What problem? Make computing easy again. That was the original idea that cought our attention when watching Joe's Armstrong presentation "The Forgotten Ideas in Computer Science - Code BEAM SF 2018".

With our years of experience in the industry, we could both easily relate to this.
We are certainly not the first developers to discover this problem. Many tried over the years to create frameworks or DSLs to try and unify at least some of the functions of a web app:

> Most Web applications are based on a conventional three tier architecture, in which the presentation, application logic, and data management are developed and maintained in separate tiers. The main disadvantage of this architecture is that it requires expertise in multiple programming languages, programming paradigms, and data models used in each tier. A single expert rarely masters all the technologies and concepts involved.

> Unifying the client side (presentation tier) and server side (logic and data tiers) programming under a single model can simplify the Web application development and particularly reduce the skill set required from a developer. Reducing the number of technologies involved also makes an application more secure, as in general each technology is one more compromise in the overall application security. Generally, a unified model can be based on either server side or client side concepts."

Markku Laine, Denis Shestakov, Petri Vuorimaa - XForms DB: An Extensible Web Application Framework Built upon Declarative W3C Standards

After a lot of research we decided to aproach the problem by developing our own tool: our very own [DSL](https://en.wikipedia.org/wiki/Domain-specific_language).

## DSL Rules/Manifesto

-   One language to rule them all - CSS, HTML, JavaScript, SQL; everything will be solved by only one language, abstracting away everything else.
-   The compiler is an important and helpful tool for development.
-   Everything that can be abstracted away and automated will be. This is not a framework to be tinkered with. Very straightforward, but with a lot of internal flexibility in terms of the final product.
-   The client project's file structure is fixed and pre-defined, aiming at efficiency and organization, but very intuitive.
-   There is no pre-requisite for knowing how to make web apps when using this framework. Coding experience is encouraged, since logic is key to any app development.
-   The language's syntax should be simple - minimum use of symbols giving new meanings to code - and easy to learn if you know English.
-   There is only "one flavour" of code. This language does not aim for concise code necessarily; the aim is to write clean, but understandable code. There is no need to encourage multiple ways to write the same piece of code.
-   Responsive design is the default. There are pre-defined styling themes in the framework that can be used right out of the box, and new themes can be added.

## Contributors

- [Leticia Duque](https://github.com/Lzduque)
- [Tim Johns](https://github.com/SlimTim10)

## What is going on now

-   We are still in the reaserch phase, but some trial with the language syntax has begun. Right now we are deciding on the internal structure, which is going to change our approach related to the syntax.
