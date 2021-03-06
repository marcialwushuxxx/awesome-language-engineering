# Awesome Language Engineering [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![alan_behind](https://user-images.githubusercontent.com/4667129/31479957-bc003858-aecf-11e7-91ae-f8a1faab66da.jpg)](https://github.com/NLKNguyen/awesome-language-engineering)
> A curated list of useful resources for computer language engineering and theory

Whether you want to create a text-processor, a parser, a language application, a DSL (Domain Specific Language), or a full-fledged programming language with compiler and tooling, this page serves as a directory map to point you to the right direction.

Better yet, help others finding their way by contributing to this page with the resources that you think useful.

## Contents

- [Tools](#tools)
- [Books](#books)
- [Articles](#articles)


# Tools

Just like other domains, knowing the available tools that are tried-and-true will save you a lot of time and efforts. Furthermore, you will also learn the emerging techniques that are adopted in different tools which make the skills more transferable.

### [ANTLR](http://www.antlr.org/) (ANother Tool for Language Recognition) 
A powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build and walk parse trees.

Describe language lexical and grammar specification in a declarative file format `.g4` (Lex/Yacc format alike), and the generator can create a parser for the following target languages: Java, C#, Python, JavaScript, Go, C++, Swift ([see update](https://github.com/antlr/antlr4/blob/master/doc/targets.md))

*Learning materials*:

* Book: [The Definitive ANTLR 4 Reference](https://www.amazon.com/Definitive-ANTLR-4-Reference/dp/1934356999/ref=la_B001JS3O0U_1_2?s=books&ie=UTF8&qid=1503464537&sr=1-2): Build your own languages with ANTLR v4

    <img src="http://ecx.images-amazon.com/images/I/81Dfq1fw4QL._SY344_BO1,204,203,200_.jpg" width="200px"/>

* Doc: [Supported Documentation](https://github.com/antlr/antlr4/blob/master/doc/index.md) for the above books

* Web: [ANTLR Mega Tuotrial](https://tomassetti.me/antlr-mega-tutorial/): A comprehensive tutorial that explains all you need to know to understand language design fundamentals and use ANTLR effectively. There is PDF version. All free.

* Video: [Terence Parr - ANTLR4](https://vimeo.com/59285751): Dr. Terence Parr introduces the latest (and last) revision of his parser generator, ANTLR



### [MPS](https://www.jetbrains.com/mps/) (Meta Programming System)

With JetBrains MPS, you can define custom editors for any new language and make using these DSLs simpler. Even domain experts, who are not familiar with traditional programming, can easily work in MPS with domain-specific languages designed around their domain-specific terminology.

*Learning materials*:

* Book: [The MPS Language Workbench Volume I](https://www.amazon.com/MPS-Language-Workbench-Programming-System/dp/153053335X/ref=sr_1_1?ie=UTF8&qid=1505363569&sr=8-1&keywords=jetbrains+MPS):  a simple introduction to the JetBrains MPS language workbench and a complete reference manual

    <img src="http://ecx.images-amazon.com/images/I/61nWg7s%2BBML._SY344_BO1,204,203,200_.jpg" width="200px"/>
    
* Book: [The MPS Language Workbench Volume II](https://www.amazon.com/MPS-Language-Workbench-II-Programming/dp/1532805373/ref=sr_1_2?ie=UTF8&qid=1505363569&sr=8-2&keywords=jetbrains+MPS): how to customize the MPS platform to better integrate it with the needs of your languages

    <img src="http://ecx.images-amazon.com/images/I/51prOmwgvJL._SY344_BO1,204,203,200_.jpg" width="200px"/>

### [Xtext](https://eclipse.org/Xtext/)

Xtext is a framework by Eclipse for development of programming languages and domain-specific languages. With Xtext you define your language using a powerful grammar language. As a result you get a full infrastructure, including parser, linker, typechecker, compiler as well as editing support for Eclipse, IntelliJ IDEA and your favorite web browser.

*Learning materials*:

* Book: [Implementing Domain-Specific Languages with Xtext and Xtend](https://www.amazon.com/Implementing-Domain-Specific-Languages-Xtext-Xtend-ebook/dp/B01CSLI6HM/ref=sr_1_1?ie=UTF8&qid=1505686814&sr=8-1&keywords=xtext): learn how to implement a DSL with Xtext and Xtend using easy-to-understand examples and best practices

    <img src="http://ecx.images-amazon.com/images/I/51ZNzHPhaDL._SY344_BO1,204,203,200_.jpg" width="200px"/>


### [Sirius](https://eclipse.org/Xtext/)

Sirius is an Eclipse project which allows you to easily create your own graphical modeling workbench by leveraging the Eclipse Modeling technologies, including EMF and GMF.

*Learning materials*:

* Web: [Official Guide](http://www.eclipse.org/sirius/getstarted.html): provides an introduction to Sirius and a series of tutorials to get started building your own graphical modeling tool



### [Flex](https://github.com/westes/flex) and [Bison](https://www.gnu.org/software/bison/)

Flex and Bison are aging unix utilities that help you write very fast parsers for almost arbitrary file formats. Lex and Yacc are the original tools; Flex and Bison are their almost completely compatible newer versions.

*Learning materials*:

* Web: [Flex & Bison Tutorial](http://aquamentus.com/flex_bison.html): this webpage is supposed to be a tutorial for complete novices needing to use Flex and Bison for some real project.

* Book: [Flex & Bison](https://www.amazon.com/flex-bison-Text-Processing-Tools/dp/0596155972/ref=sr_1_1?ie=UTF8&qid=1505766504&sr=8-1&keywords=flex+and+bison): explains how to use flex and bison to solve your problems quickly. This is the update from the original Lex & Yacc book described below.

    <img src="http://ecx.images-amazon.com/images/I/51fLgJUN2bL._SY344_BO1,204,203,200_.jpg" width="200px"/>

* Book: [Lex & Yacc](https://www.amazon.com/lex-yacc-Doug-Brown/dp/1565920007/ref=sr_1_1?ie=UTF8&qid=1505766519&sr=8-1&keywords=lex+and+yacc): shows you how to use two Unix utilities, lex and yacc, in program development. These tools help programmers build compilers and interpreters, but they also have a wider range of applications.

    <img src="http://ecx.images-amazon.com/images/I/510OFPELhPL._SY344_BO1,204,203,200_.jpg" width="200px"/>

### [Kaitai Struct](http://kaitai.io/#quick-start) 

A parser generator for reading binary data. This is a declarative language for specifying data structure of binary data in order to generate parser (in multiple target languages) that handles reading binary file formats, network stream packet formats, etc. It comes with a compiler, an IDE, a visualizer, and library of format specs.

Describe binary structure specification in a declarative file format `.ksy` (YAML alike), and the generator can create a parser for the following target languages: C++/STL, C#, Java, JavaScript, Perl, PHP, Python, Ruby ([see update](http://kaitai.io/))

### [Sed](https://www.gnu.org/software/sed/) and [Awk](https://www.gnu.org/software/gawk/)

Sed and Awk are two text processing programs that are mainstays of the UNIX programmer's toolbox. 

- Sed is a stream editor (non-interactive) to do common text editing jobs like search/extract/replace/insert.
- Awk is a whole programming language ideal for handling data extraction, reporting, and data-reformatting jobs.

Both are command-line interface programs that can be used independently or together nicely for many text processing purposes. They are great for recognizing and extracting information from text input. For simple language recognition tasks, perhaps they are the best tools for the job with the least effort due to their simplicity and targeted use cases. Sed and Awk are part of most, if not all, Linux/Unix/macOS distributions. They are available to download for Windows as well.

*Learning materials*:

* Doc:
    * [Sed official manual](https://www.gnu.org/software/sed/manual/)
    * [Awk official manual](https://www.gnu.org/software/gawk/manual/)
* Web:
    * [Sed tutorial](http://www.grymoire.com/Unix/Sed.html)
    * [Awk tutorial](http://www.grymoire.com/Unix/Awk.html)
    * [Handy Sed one-liners](http://www.pement.org/sed/sed1line.txt)    
    * [Handy Awk one-liners](http://pement.org/awk/awk1line.txt)
    * [Awk by Example](https://www.ibm.com/developerworks/library/l-awk1/)
* Course:
    * [Lynda.com Sed Essential Training](https://www.lynda.com/SED-tutorials/SED-Essential-Training/359472-2.html)
    * [Lynda.com Awk Essential Training](https://www.lynda.com/Linux-tutorials/AWK-Essential-Training/162719-2.html)
    
* Book:

    * [Sed & Awk](https://www.amazon.com/sed-awk-Dale-Dougherty/dp/1565922255/ref=sr_1_2?ie=UTF8&qid=1508814582&sr=8-2&keywords=sed)
        
        <img src="http://ecx.images-amazon.com/images/I/51zGTApa8%2BL._SY344_BO1,204,203,200_.jpg" width="200px"/>
        
    * [The AWK Programming Language](https://www.amazon.com/AWK-Programming-Language-Alfred-Aho/dp/020107981X/ref=sr_1_4?ie=UTF8&qid=1508814604&sr=8-4&keywords=awk)

        <img src="http://ecx.images-amazon.com/images/I/41WxQ-gPjWL._SY344_BO1,204,203,200_.jpg" width="200px"/>

    * [Effective awk Programming](https://www.amazon.com/Effective-awk-Programming-Universal-Processing-ebook/dp/B00U8232XM/ref=sr_1_1?ie=UTF8&qid=1508814604&sr=8-1&keywords=awk)

        <img src="http://ecx.images-amazon.com/images/I/51x1OBaPbVL._SY344_BO1,204,203,200_.jpg" width="200px"/>
        
# More Resources

# Books

### **[DSL Engineering](https://www.amazon.com/DSL-Engineering-Designing-Implementing-Domain-Specific/dp/1481218581/ref=sr_1_3?ie=UTF8&qid=1505967419&sr=8-3&keywords=domain+specific+languages)**

*Designing, Implementing and Using Domain-Specific Languages*

<img src="http://ecx.images-amazon.com/images/I/415XWbrmA8L._SY344_BO1,204,203,200_.jpg" width="200px"/>

The definitive resource on domain-specific languages: based on years of real-world experience, relying on modern language workbenches and full of examples. Domain-Specific Languages are programming languages specialized for a particular application domain.


### **[Language Implementation Patterns](https://www.amazon.com/Language-Implementation-Patterns-Domain-Specific-Programming/dp/193435645X/ref=la_B001JS3O0U_1_1?s=books&ie=UTF8&qid=1503464537&sr=1-1)**

*Create Your Own Domain-Specific and General Programming Languages*

<img src="http://ecx.images-amazon.com/images/I/81fc0FiuhtL._SY344_BO1,204,203,200_.jpg" width="200px"/>

Written by the author of ANTLR, and it is also the tool used in the book, but the general concepts apply regardless of what you use.

### **[Compilers: Principles, Techniques, and Tools](https://www.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811/)** 

<img src="http://ecx.images-amazon.com/images/I/51Bug87tM%2BL._SY344_BO1,204,203,200_.jpg" width="200px"/>

A classic compiler book that is known to professors, students, and developers worldwide as the "Dragon Book"


# Articles

**General:**

* [Five Questions About Language Design](http://www.paulgraham.com/langdes.html)
* [Designing the next programming language? Understand how people learn!](http://www.theenterprisearchitect.eu/blog/2013/02/14/designing-the-next-programming-language-understand-how-people-learn/)
* [So you want to write your own language?](http://www.drdobbs.com/architecture-and-design/so-you-want-to-write-your-own-language/240165488)
* [Generations of programming languages](http://www.byte-notes.com/generation-programming-languages)
* [Turing Completeness](https://en.wikipedia.org/wiki/Turing_completeness)


**Paradigms:**

* [Programming Paradigms for Dummies: What Every Programmer Should Know](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf)
* [Paradigms of programming languages](http://cs.lmu.edu/~ray/notes/paradigms/)


**Type Systems**

* [Type Systems](http://lucacardelli.name/Papers/TypeSystems.pdf)
* [Static vs. Dynamic Type Checking](https://thesocietea.org/2015/11/programming-concepts-static-vs-dynamic-type-checking/)



# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nikyle Nguyen](https://github.com/NLKNguyen/) has waived all copyright and related or neighboring rights to this work.
