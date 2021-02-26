# Language Guide

> This chapter shows and discusses "abstract code" with the PUZZLE programing language

# An abstract language

What is a language at all? A Language is a communication format, most notably used by us people. It is used to transfer information from one person to another.

Computers work on the same principle. (Programming-) Language is used to transfer information from a user (developer) to the computer. The computer then processes that information.

# Language philosophy

Every programming language, just like every real (spoken) language is based upon two principles:

* Syntax (structure)
* Meaning (semantics)

Syntax is the grammar. It defines that the word "hello" is written as "hello", not "hleo".

Semanticy defines, that the word "hello" means "hello", not "peanut butter".

Every programming language comes with a predefined set of words and defines, how these words are written. Just like the english language comes with all the english words and how they are spelled. Each word, or the combination of different words form a meaning (semantics). 

> For instance, the phrase ***"how are you?"*** in english means that <u>one participator</u> in the communication is interested in how the <u>other patricipator</u> is doing. Thats the meaning of the combination of these words. 

> In a programming language the phrase ***"print('hello')"*** means that <u>one participator</u> of the communication (the developer) is handing over the information to display the text "hello" to the <u>other participator</u> (the computer).


# Abstract language structure

So, what is an abstract programming language? It's a real programming language, that uses abstraction in both syntax and semantics.

Most programming languages use real words in their syntax definitions, like `if`, `else`, `function`, `print`. And these languages put these words together in a logical way (in order to form a meaning - semantics):

Example: a condition

```javascript
if(3 > 2) {
	console.log('yes')
} else {
	console.log('no')
}
```

This piece of code checks if the number 3 is larger than the number 2. If is's really larger, it outputs the word 'yes'. If otherwise, it outputs the word 'no'.

This code comes with different parts. It contains:

* Words: `if`, `else`, `console`, `log`
* Dots: "console`.`log"
* Brackets: `(`, `)`, `{`, `}`
* Line Breaks

Wouldn't it be easier if that code was something like this:

```puzzle
if 3 is larger than 2 then print yes otherwise print no
```

Of course, this is way easier to understand, since we use "natural language". The challenge in natural language, howewer is that phrases with the same meaning (semantics) can be expressed using different structures (syntax).

* How are you?
* How are you doing?
* How is it going?

These phrases all mean the same, but are written differently.

The condition above could also be written in different ways.

```puzzle
if 3 is larger than 2, print yes,otherwise print no.
```


```puzzle
if 3 is bigger than 2 print yes. if it is not print no.
```

```puzzle
if the number 3 is larger than the number 2 print yes. if it is not print no.
```

Different syntax is easy to understand for humans, but not so easy for a computer! Computers need predictable syntax within a code in order to understand it. So in an abstract coding language, it should be possible to write code in different ways while still having the same meaning.

> An abstract programming language should be capable of understanding a phrase with certain words missing and/or a different word order. The most important words, however must be present (like 'if' or 'print')


# What is PUZZLE?

The PUZZLE project is a programming language, that ***abstracts functionality using simple words and phrases***

> It's an abstract programming language

The whole language is based on an extendable, dynamic language configuration, making it easy to build custom syntax and semantics. In this configuration, single identifiers (words) can be defined, dynamically combined and connected. Each word or phrase (a combination of words, either in a specific order or not) can be mapped to the execution of a more complex functionality, implemented in the background.


PUZZLE's key features are:

* Simple syntax
* Dynamic semantics
* Textual abstraction for more complex functionalities
* Easily customizable
* Extendable
* Runs on many platforms
* Can be used to build many things

## Simple syntax

The syntax of PUZZLE is heavily based on natural language. 
A quick example:
```puzzle
print Hello
```

## Dynamic semantics

Even different semantics in the shape of different word orders for the same meaning are possible.

## Textual abstraction

Pretty much any complex functionality can be abstracted in text: a word or phrase.

## Easily customizable

At the base of the language lies a dynamic configuration which allows one to define custom syntax and semanticy in order to execute some functionality.

## Extendable

Custom syntax can be published as modules. Any other PUZZLE user can use these modules. 

Modules can be used over the web or from a local file.

```puzzle
use https://domain.com/email.js;

use email.js;
```

## Platform independent

The PUZZLE language itself is written in JavaScript, meaning that any PUZZLE code runs, where JavaScript runs.

> JavaScript (and PUZZLE) runs on pretty much any device. From Microprocessors, Smartphones, Desktops to Servers and Clouds.

## Versatile

Since PUZZLE is a programming language, the capabilities are versatile. It is not restricted to anything specific. You can create Graphical Interfaces, Server Code, Websites, Desktop Apps, Workflows or embedded Applications.

# Language concepts

Programming means passing a set of instructions to a computer. These instructions are written with programming code. Every programming code follows a certain structure that makes it easier for a computer to understand and easier for a developer to write and read. Pretty much every programming language is structured like this:

![Code Structure](../../assets/code-structure.png)

## Code files

Code is typically saved into files. Each file contains the programming code. If the software requires a lot of code, it is split up into multiple files for readability, maintainability and structure. Code files can be referenced amongst each other.

## Statements

Inside a file, code is split up into different statements. A statement is a single (or multiple) instruction that a computer processes individually. Statements are seperated fromeach other using a delimeter. Many languages use a semicolon for this and so does PUZZLE.

An example with PUZZLE:
```puzzle

print "hello World" ;

<--------------->  <->
    Statement    Delimeter

```



# Building Blocks

Blocks are also a way to isolate instructions. A Block allows to span statements over multiple lines and can contain multiple statements. In PUZZLE, each block is processed individually...

In most programming languages, blocks are wrapped in different kinds of brackets - (...), {...}, [...].

```puzzle

print (			   ᐱ
	hello World	   |  Block
);				    ᐯ

<->
Delimeter

```

PUZZLE allows `(, {, ", '` for creating blocks. The following blocks are interpreted equal to one another:

```puzzle

print (   
	hello World
);

print "   
	hello World
";

print {   
	hello World
};

print ' 
	hello World
';

```

## Runtime

Code needs to be executed somewhere and somehow.

## functions

- built in

## data

## conditions

## loops

## algorythms

## Comments

Comments are a very important part of programming code. Comments are parts of a code, that are not processed and interpreted! They are used to define additional information about the code itself. In most languages, comments are initiated with `//`

```puzzle
// This is a comment, that will not be processed
print "This is a statement that will be processed."
```

