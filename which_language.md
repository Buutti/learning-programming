Which language should I choose?
===============================
**The one most relevant to what you want to be doing.**

It's up to you.  Each has its good and bad sides,
and not everyone likes to express ideas in the same way.

Language is a tool to express ideas, programming languages
are no different.  And like with usual spoken languages,
it becomes easier and easier to learn new ones after the first.

Most programming languages are grammatically so similar,
that if you know how to program in one language, it's completely
possible you can already *read* several.

There are very few programmers who can only write in one
programming language, and it's useful to know a few since
they teach you different ways to approach same problems.

The key takeawat from this page is

**Don't stress too much about the choice, you can
switch later if you think something else suits you better,
it won't go to waste either way**

If you absolutely have zero clue, 3 of the more usual
starting languages are [Python](#python), [Javascript](#javascript)
and [C](#c)

Languages in this page are listed in alphabetical order


General things that should affect your choice of language
---------------------------------------------------------
### What you want to be doing
#### Learning about computers in general
#### Building a project you have an idea for
#### Landing a job

### Learning habits and goals
#### Learn by doing vs. theory-first
#### Fast vs. good

### Resources available
#### Internet tutorials
#### University courses
#### Online courses
#### Teachers
#### Books
#### Videos


For teachers
------------
Hopefully this is also useful to teachers as well as a resource to
maybe decide what language they want to keep their course in and
how to frame their courses.  If you are a teacher, feedback is
very welcome.


C
=
The lingua franca of programming languages, your toaster can
probably run software built with C.  If you code long enough
you will have to deal with C and learn at least some of it
in some point anyways.

Helps you understand what your computer hardware actually does
when you instruct it to do something

Usual usage
-----------
- Operating systems
- UNIX system layer
- Embedded
- Lingua franca to combine software written in other languages

Pros
----
- Quite simple feature set
- Common as dirt (basically omnipresent)
- Need to understand nuts/bolts of what is going on
- A lot of languages are heavily inspired by C
- Easy-ish to use from other languages

Cons
----
- Extremely easy to make mistakes
- Long time to get anything flashy going (can get boring)
- Need to understand nuts/bolts of what is going on
- Not necessarily the hottest language to advertise for headhunters

Recommended when
----------------
- You are more interested in the journey than the end result
- You want to learn computer internals
- You are interested in systems programming

Materials
---------


C#
===
Microsoft's response to Java. An Object oriented language used to make
errorproof enterprise applications. Is also used as a Scripting language
in the most popular game engine "Unity".

Usual usage
-----------
- Games (Unity, Monogame)
- Web applications
- Windows desktop applications

Pros
----
- Clear and logical syntax that is a good starting point for most other common languages
- Clear error messages that make it easy to find and see where you have made an error.
- Slightly more difficult to write something that is a total mess
- Easy to learn the basics of Object oriented programming

Cons
----
- You need to write more code than with some other languages which makes it slightly slower
- Even though cross-platform solutions exist C# is still very much a windows language
- C# is strongly object oriented so you won't learn other types of programming as much.


Recommended when
----------------
Materials
---------

C++
===
Started as a way to reduce perceived complexity of the C programs while
keeping compatibility to C code.  Has since diverged significantly from
the original "C with classes"

Internet tutorials for this language are almost always total garbage and
actively harmful, so requires either a teacher or a good book and a cabin
without Internet.

Protip:  *do not try to learn C to learn C++, it's a trap and you'll need
to unlearn a lot of C to be good at C++*

Usual usage
-----------
- Automation (vehicles, industrial, flight control...)
- Autonomous machines
- Embedded
- Game engines
- Low-level or performance-critical functionality for other languages
- CAD/Graphics software
- High-frequency trading

Pros
----
- Useful across the board
- Allows access to nuts and bolts of the system without requiring it

Cons
----
- Complex
- May take a long time to get anything flashy going (can get boring)
- Absolutely requires a good teacher or really good self-discipline plus a good book
- Even university courses on the language sometimes teach extremely outdated practices
- Most online courses are decades old and don't reflect the current best practices

Recommended when
----------------
- You want performance
- You want to learn the nuts and bolts
- You are interested in systems programming
- You have a teacher or a book to help you

Materials
---------


Python
======
Quite simple language originally written with the explicit goal
of teaching programming.  Used in plethora of things because of
its apparent simplicity

Usual usage
-----------
- Prototyping
- Small scale projects
- As an interface for AI libraries

Pros
----
- Actually designed with the goal of being easy to teach/learn

Cons
----
- Has more unique semantics, doesn't resemble other languages

Recommended when
----------------
- You still can't decide after reading this page

Materials
---------


Java
====
Usual usage
-----------
Pros
----
Cons
----
Recommended when
----------------
Materials
---------


Javascript
==========
Originally created for interactive components for web pages.
Since then has spread to plethora of different uses like mobile
development and desktop applications.

Over time many different frameworks have been created for the
language. This has led to an uncertainty of which one of these
frameworks should one have the knowledge of.

Nowadays, javascript web developers can also include web assembly
in their projects if they need their applications to run faster and/or
consume less memory.

Usual usage
-----------
- Web development (frontend and backend)
- Mobile development (React Native)
- Desktop applications (Electron)

Pros
----
- The most used language, so there are many learning resources available
- Dynamically typed: one less thing to worry about for starters
- Easy and fast to show things on screen
- Easy and fast to create interactive interfaces

Cons
----
- Due to backwards compatibility, there are obsolete ways to write JS that should be avoided
- Too many web development frameworks of which most don't actually improve the language
- Doesn't scale up well without WASM when a project requires a lot of computation power and/or memory
- React Native and Electron do not have native WASM like support

Recommended when
----------------
- You want to do anything web
- Quickly create interactive applications

Materials
---------
- [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)
- [JS for C & Python programmers](https://www.wooji-juice.com/blog/javascript-article.html)

Lua
===
A light, somewhat verbose scripting language where indentation doesn't matter.
Typically, the Lua virtual machine sits on top of a lower-level engine, providing an
easy-to-use scripting interface.

Usual usage
-----------
- Video game scripting & modding
- Game development (Love2D, Pico-8, TIC-80)
  
Pros
----
- Tiny & portable
- Short learning curve
- Fast for a scripting language

Cons
----
- Importing Lua packages can be cumbersome
- The community is split between different Lua versions
- Some idiosyncratic nonstandard features
- Tiny size means there are not many features out the box

Recommended when
----------------
- You want to add lightweight scripting on top of a video game engine
- You want to quickly piece together a tiny game or prototype

Materials
---------
- [Learn Lua in 15 minutes](http://tylerneylon.com/a/learn-lua/)
- [How to LÖVE](https://sheepolution.com/learn/book/contents)
  - learning Lua for making games with the Love2D framework
