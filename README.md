# Abstract Code

<div class="masonry">
	<div style="background: #dc90cbb8;">
	    <p><span style="font-size:25px"><b>Abstract Code</b> is a programming approach, where abstract language is used to build software as an alternative to low code and no code.</span>
	    <a href="#?id=about">Learn more</a>
	</p>
	</div>
	<!--div style="background: #b583cca4;">
	    <p><span style="font-size:25px"><b>Content</b> <br>
		<ul>
			<li><a>About</a></li>
			<li><a>Coding Basics</a></li>
			<li><a>Abstraction</a></li>
			<li><a>Abstract Language</a></li>
		</ul></span>
	</p>
	</div-->
	<!--div style="border: 1px solid #dc90cbb8; background: none;">
	    <a href="#?id=coding-basics"><span style="font-size:23px"><b>Coding Basics</b><br> <span style="color:#777777">understand basics of coding</span></span>
		</a>
	</div>
	<div style="border: 1px solid #dc90cbb8; background: none;">
	    <a href="#?id=abstraction"><span style="font-size:23px"><b>Read about abstraction</b><br> <span style="color:#777777">... in computers</span></span>
		</a>
	</div>
	<div style="border: 1px solid #dc90cbb8; background: none;">
	    <a href="#?id=abstract-language"><span style="font-size:23px"><b>Language Approachs</b><br> <span style="color:#777777">check out an abstract programing language</span></span>
		</a>
	</div-->
</div>

# About

Welcome to "Abstract Code" Programming. This publication is to show and discuss approaches for building software using ***real programming*** code in an abstract and versatile way. Approaches, that go beyond hard-core programming but also beyond "Low Code". You will:

* ***Learn*** about abstract ways to develop software
* ***See*** different approaches for different problems
* ***Develop*** software using abstract programming languages


Abstract Code Programing doesn't have an official definition. It is discussed here as a development approach that aims to provide a way to develop software using programming languages that are designed with abstract principles and are accessible even for non programmers. Projects, like the abstract programming language PUZZLE are developed and discussed.


## Why abstract code?


Usually, learning and understanding a programming language isn't so easy (except for pros). So in the last decades, different approaches have been born in order to make "creating software" available for non-professionals and easier for professionals. Common examples are Low Code Platforms, drag-n-drop programming tools or WYSIWYG software. These approaches all work with abstraction.

Abstraction has been around since computers were created. Abstraction works on the concept of removing complexity in order to make something simpler. The approaches mentioned above are offering a way to create something in a simpler fashion compared to writing compex programming code. The price, one has to pay here is missing capabilities. That is why oftentimes these tools focus on specific tasks or domains. Like tools for creating Graphical User Interfaces or tools for building business workflows.

***Abstract Code***, on the other side uses programming code instead of graphical tools. Opposed to typical general-purpose programming languages, the abtract code language is designed to be understandable, using abstract syntax. You will learn more about the language structure [here](LANGUAGE-GUIDE).


![Development Layers](assets/development-layers.png)



## The Approach

***"An abstract programming language"***

![Puzzle](assets/puzzle.png "Puzzle")

As part of this publication, some technologies that make abstract coding possible, are being created and discussed. There technologies are open source.


When we talk about abstract code, we need an abstract programming language. The PUZZLE project is an approach to  reate a real programmming language, that is designed with abstraction in mind. Along with the resources shown in this publication, PUZZLE will be discussed.


# Coding Basics

> The basics are a good point to start not only for non-programmers but also for professionals. This chapter features the main parts involved in programming:
***From "What is code?" over "What is a Computer?" to "How to run code?"***

---

## What is Code?

```javascript
var words = ["Hello", "World"];
var sentence = words.join(" ");
function printSentence(){
	console.log("The full sentence:", sentence);
}
printSentence();

```

Code, source code, computer code, program code. There are many names that can be used to describe it. But what exactly is code?

![Banner](../../assets/instruction.png "Banner")

In the computer world, a "code" is a set of instructions that tells a computer what to do. A code, for instance, can consist of the instruction to output a text on the screen of the computer. 
Sounds simple, but still there are open questions...

* How is an instruction (aka "code") passed to the computer
* What format should this "instruction" have?
* Where exactly shall the text be output?
* ***Where to start???***


## The computer

The first thing one needs in order to run code is a computer. Simple, right? No.

Computers, today exist in many, many shapes, variations, forms, and kinds. Computers can be as small as a nut 🥜 or as large as a house 🏠. Example Computers are:

* Pocket Calculators
* Smart Phones
* Laptops
* Microchips
* "Computers" as in Home-Computer

Since computers can be so different compared to each other, the way they work and the way they handle "code" is also very different. Computers run an operating system (Windows, macOS, Linux, ...). An operating system is the heart of every computer. It is basically the part that makes everything work. It's the ***bridge*** between the computer itself and whatever would like to input any instructions - like "code". 

Operating systems, depending on the kind of computer they run on, can either be quite extensive or very basic. Home-Computers run extensive operating systems, since they have to offer a lot of features. Microchips, on the other hand, run more basic operating systems, since they oftentimes have a specific job to perform and don't need many features.

However, every operating system works on the ***IPO*** Principle:

***Input, Processing, Output***

Code is actually the most simple example of an IPO.

The code is the ***input***. The computer then ***processes*** the code and performs the instructions in it. As a result, an ***output*** is generated by the computer.

## Write code

Let's write some code... But wait, how?

As we have learned, a code is a set of instructions, that tell a computer, what to do. But what do these instructions look like?

If we would like to output a text on the computer, what doest the code look like, that achieves this?

This is where programming languages come in.

In real life, people use a "language" to communicate to each other. 

Person A tells Person B to "hand over the cup of tea". This is the instruction. Person B hands over the cup of tea. That's the processing. In the end, Person A has the cup of tea. This is the output of this whole instruction. Language was used to execute the communication. 

Code is Language. And just like in real life, there are many different languages. They use different words, syntax and semantics.

Common Programming Lnguages are: Python, Java, JavaScript or C.

> Code itself is just a text. A sequence of words and tokens, that together form the instructions for the computer.


Example 1: A code that outputs a text on the terminal, written in Python.

```python
print("Hello")
```

Example 2: The same code, written in Java.

```java
System.out.print("Hello");
```

Example 3: The same code, written in Puzzle.

```puzzle
print Hello
```
As you can see, these examples all do the same, but look very different.

## Input/Output

> Stupid question: where is code inserted into the computer?

Code is nothing but a text. This text somehow needs to be inserted somewhere for the computer to process - but where? 

Code can be input directly via the ***command line interface*** or saved as file(s) that will be passed to the [language/runtime](...).

> A ***Command line interface***, or ***CLI*** is a text based program that is part of the operating system. A CLI takes code (typically single commands) as input and writes text as output.


### Output channels

***The possible output of a code is bound to the output capabilities of the computer***. If a computer has a display attached, graphic output is available. If we're talking about a microchip, that doesn't have a screen, the output would be the blink of a light or something.

![Banner](../../assets/devices-output.png "Banner")


The result of what a code does typically has some output. An output can be whatever the computer has to offer:

* Output on the screen - if a screen is available
	* graphic output (user interface)
	* text output (terminal)
* Output via devices
	* printer
	* sound
	* ...
* Output via network
	* communication with other computers

Whatever output mechanisms are available, the input is the same across all types of computers: ***code***


## Run code

Once a code is written, the next step is to pass it to the computer to run it. This step again is different from language to language. 

In order to run a code, the computer needs to "know" the language. So the "language" itself must be installed on the computer. Once installed, the operating system will introduce the language as a "program", that is used to execute the code.

TBC...

# Existing Approaches

## Abstraction

> The goal of "abstracting" [...] is to reduce complexity by removing unnecessary information [<cite>[1]</cite>]

The concept of abstraction itself has been used in computers ever since they were created. Computers work on complex concepts that are split into different layers.

> Abstraction is done with Layers. Each Layer makes the usage of it's underlying layer simpler.

Everbody knows, computers only understand 0 and 1. Programming, however is not done by using zeros and ones. It is done by using readable code. So there must be something in between, something that somehow translates code into 1 and 0. This is where layers join the game. 

Layers are here to abstract the layer beneath it. Computers work on many, many layers. So from a user input, like the press of a key on the keyboard, many different layers are involved, before that command reaches the 1 and 0 level.

![Layers](../../assets/layers2.png "Layers")

<small>([Image source](https://lh6.googleusercontent.com/proxy/erajlo1MU6tYmH76em7xwahjWRRec_jwCYDUM_E0bdOLQNMWEHfQM6AwzbVBqDMUG8vX3rxYu2EgS_ekD2CvvxGD3qor-i6eZyCSBVe_G-8BjKyhjN1B7wxwBx982YuyqAoB=w1823-h1193))</small>


Every programming code runs on a pretty high layer of that stack, meaning that code is a layer of abstraction that is fairly simple, compared to the 0 and 1 layer. 

Therefore a programmer usually doesn't have to deal with zeroes and ones.


[1]: https://techterms.com/definition/abstraction#:~:text=In%20computer%20science%2C%20abstraction%20has,of%20computers%20in%20abstract%20terms.

## Abstract Approaches

***"Programing isn't always just done with code."***

Of course, code is the most common way to program software. But there are other ways to develop software beyond code.

> Code is a set of instructions that tell a computer what to do, remember? These "instructions", however can also be described in other ways as well - beyond code.


Code is also the lowest level to describe there instructions. But over time, people have found ways to make software development possible not just by writing code, but by providing more abstract ways to program - beyond code. Common examples range from "No Code" to "Low Code".

* ***No Code*** doesn't require writing any code. Typically programming is done by using WYSIWYG Tools
* ***Low Code*** does require writing code, but not necesseraly. This is typically a mix of code and WYSIWYG tools.

## WYSIWYG programming tools

WYSISWG stands for "What You See Is What You Get". Tools that work on this principle allow the user (here: programmer) to create something in the same way it will appear in the result. [<cite>[2]</cite>]

What that means is that programming is done using graphical tools that let's the user create something by using drag'n drop, clicking an writing.

[2]: https://www.dictionary.com/browse/wysiwyg

## No Code

## Low Code


## Abstract Code

> First of all, there is no official definition of "Abstract Code". I'll be using this term to describe the principle of this publication.

When you google "Abstract Code", you'll mainly find results that have to do with the concept of [Abstraction](...).
And the Idea of Abstraction is actually a good point to start. You can read more about abstraction [here]().

What the concept of this publication is about, is finding a way to develop software without the (full) complexity of general purpose programming languages while still having the (full) flexibility of general purpose programming languages.

Naturally, the above statement sounds conflicting -  and hard to achieve. And it is.
This is why concepts, like Low Code Programming have evolved in the last couple of years.

Let's talk about the three main conpepts of abstract code programing. These concepts actually represent the name of this whole thing:

* Abstract (as in abstraction)
* Code (computer code)
* Programming (the process of coding)


# Abstract Language

What is a language at all? A Language is a communication format, most notably used by us people. It is used to transfer information from one person to another.

Computers work on the same principle. (Programming-) Language is used to transfer information from a user (developer) to the computer. The computer then processes that information.


## Language philosophy

Every programming language, just like every real (spoken) language is based upon two principles:

* Syntax (structure)
* Meaning (semantics)

Syntax is the grammar. It defines that the word "hello" is written as "hello", not "hleo".

Semanticy defines, that the word "hello" means "hello", not "peanut butter".

Every programming language comes with a predefined set of words and defines, how these words are written. Just like the english language comes with all the english words and how they are spelled. Each word, or the combination of different words form a meaning (semantics). 

> For instance, the phrase ***"how are you?"*** in english means that <u>one participator</u> in the communication is interested in how the <u>other patricipator</u> is doing. Thats the meaning of the combination of these words. 

> In a programming language the phrase ***"print('hello')"*** means that <u>one participator</u> of the communication (the developer) is handing over the information to display the text "hello" to the <u>other participator</u> (the computer).


## The challenges

When trying to create a simple programming language as an alternative to low code platforms, some challenges occur:

***Learning***

Learning a language is harder than learning how to use an existing software.

***Intuitivity***

Development platforms themselves are software applications. Software applications are intuitive. Languages are not...

***Handling***




## Abstract language structure

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


## PUZZLE Language

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

**Simple syntax**

The syntax of PUZZLE is heavily based on natural language. 
A quick example:
```puzzle
print Hello
```

**Dynamic semantics**

Even different semantics in the shape of different word orders for the same meaning are possible.

**Textual abstraction**

Pretty much any complex functionality can be abstracted in text: a word or phrase.

**Easily customizable**

At the base of the language lies a dynamic configuration which allows one to define custom syntax and semanticy in order to execute some functionality.

**Extendable**

Custom syntax can be published as modules. Any other PUZZLE user can use these modules. 

Modules can be used over the web or from a local file.

```puzzle
use https://domain.com/email.js;

use email.js;
```

**Platform independent**

The PUZZLE language itself is written in JavaScript, meaning that any PUZZLE code runs, where JavaScript runs.

> JavaScript (and PUZZLE) runs on pretty much any device. From Microprocessors, Smartphones, Desktops to Servers and Clouds.

**Versatile**

Since PUZZLE is a programming language, the capabilities are versatile. It is not restricted to anything specific. You can create Graphical Interfaces, Server Code, Websites, Desktop Apps, Workflows or embedded Applications.

## Language "building blocks"

Programming means passing a set of instructions to a computer. These instructions are written with programming code. Every programming code follows a certain structure that makes it easier for a computer to understand and easier for a developer to write and read. Pretty much every programming language is structured like this:

![Code Structure](../../assets/code-structure.png)

### Code files

Code is typically saved into files. Each file contains the programming code. If the software requires a lot of code, it is split up into multiple files for readability, maintainability and structure. Code files can be referenced amongst each other.

### Statements

Inside a file, code is split up into different statements. A statement is a single (or multiple) instruction that a computer processes individually. Statements are seperated fromeach other using a delimeter. Many languages use a semicolon for this and so does PUZZLE.

An example with PUZZLE:
```puzzle

print "hello World" ;

<--------------->  <->
    Statement    Delimeter

```

### Blocks

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

### Runtime

Code needs to be executed somewhere and somehow.

### functions

- built in

### data

### conditions

### loops

### algorythms

### Comments

Comments are a very important part of programming code. Comments are parts of a code, that are not processed and interpreted! They are used to define additional information about the code itself. In most languages, comments are initiated with `//`

```puzzle
// This is a comment, that will not be processed
print "This is a statement that will be processed."
```


