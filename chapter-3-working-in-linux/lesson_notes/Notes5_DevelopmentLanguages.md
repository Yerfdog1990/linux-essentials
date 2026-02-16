# 3.5 Development Languages

Linux has always had strong support for software development. Since Linux itself was created by programmers, it naturally includes:

* Programmable shells
* Powerful text editors
* Extensive development tools
* Support for modern programming languages

Many programming languages treat Linux as a **first-class platform**, meaning they are fully supported and optimized for it.

---

# Programming Languages Overview

A **programming language** allows developers to write instructions in a human-readable format. These instructions are eventually translated into machine code that the computer understands.

Programming languages fall into two main categories:

1. **Compiled languages**
2. **Interpreted languages**

---

## Compiled vs. Interpreted Languages

### Compiled Languages

* Entire program is translated into machine code before execution.
* Produces an executable file.
* Typically faster at runtime.

**Advantages:**

* High performance
* Efficient memory use
* Good for system-level programming

---

### Interpreted Languages

* Code is translated into machine instructions as the program runs.
* No separate compilation step required.
* Often more flexible and faster to develop in.

**Advantages:**

* Faster development cycle
* More built-in features
* Often require less code to accomplish tasks

---

# Compiled Languages in Linux

## C

Linux itself was written in **C**.

* C maps closely to machine code.
* Allows fine control over memory and performance.
* Produces small, efficient programs.
* Ideal for operating systems and performance-critical software.

Historically, when memory was limited (measured in kilobytes), C’s efficiency was essential. Even today, it remains important for high-speed, low-level programming.

---

## C++

**C++** extends C by adding object-oriented features.

* Supports object-oriented programming (OOP)
* Allows structured, modular design
* Widely used for applications and system software

---

## Objective-C

**Objective-C** took C in another direction and is heavily used in **Apple Inc.** products.

* Combines C with object-oriented capabilities
* Used in macOS and iOS development

---

## Java

**Java** uses a unique compiled model.

Instead of compiling directly to machine code:

1. Java compiles to bytecode.
2. Bytecode runs on a virtual machine called the JVM.

### Java Virtual Machine (JVM)

The JVM (Java Virtual Machine):

* Acts as a virtual CPU.
* Translates Java bytecode into native machine instructions.
* Allows Java programs to run on any system with a JVM.

### Advantages of Java’s Approach

* **Platform independence** (write once, run anywhere)
* Built-in services like memory management
* Centralized performance improvements (enhancing the JVM benefits all applications)

Although Java involves extra translation steps, the JVM is optimized and efficient.

---

# Interpreted Languages in Linux

Interpreted languages translate instructions as they execute. While this can require more processing power, the productivity gains often outweigh the cost.

Many interpreters are written in C or even Java—meaning interpreted languages may themselves run on the JVM.

---

## JavaScript

**JavaScript** is a high-level interpreted language and a core technology of the World Wide Web.

Important notes:

* Not the same as Java
* Used for interactive web features
* Cross-platform scripting language
* Continuously evolving for security and functionality
* Can be released under the GNU GPL

JavaScript libraries allow developers to create:

* Animations
* Interactive web pages
* Complex web applications
* Even server-side applications

---

## Object-Oriented Programming (OOP)

Object-oriented programming abstracts complex operations so users only deal with simple tasks.

Think of pressing a button on a machine that performs many hidden steps automatically—that’s the concept behind OOP.

Languages such as Java and C++ heavily use object-oriented design.

---

## Perl

**Perl** is an interpreted language.

Originally designed for:

* Text processing
* Text manipulation

Over time it became popular for:

* Systems administration
* Automation
* Web development

Perl remains widely used in scripting and automation tasks.

---

## PHP

**PHP** was built to create dynamic web pages.

How it works:

1. A PHP file is processed by a web server (such as Apache).
2. Special PHP tags mark executable code.
3. The server interprets the code.
4. The final output is sent to the user’s browser.

### Advantages

* Easy to learn
* Widely available
* Large ecosystem

Popular projects built with PHP include:

* **WordPress**
* **Cacti**
* Parts of **Facebook**

---

## Ruby

**Ruby** was influenced by Perl and shell scripting.

Features:

* Simplifies complex programming tasks
* Clean, readable syntax
* Strong web development presence

### Ruby on Rails

The **Ruby on Rails** framework makes building complex web applications easier and faster.

Ruby is also widely used in automation tools such as:

* Chef
* Puppet

These tools help manage large numbers of Linux systems efficiently.

---

## Python

**Python** is a popular scripting language.

Characteristics:

* Simple, readable syntax
* Makes complex tasks easier
* Widely used across industries

### Django Framework

The **Django** framework simplifies web application development.

### Strengths

* Excellent statistical and scientific capabilities
* Popular in academia
* Strong community support
* Versatile (automation, web development, data science)

---

# Libraries in Linux Development

A **library** is a collection of prewritten code that performs common tasks.

Instead of writing everything from scratch, developers use libraries to:

* Save time
* Reduce errors
* Increase reliability

---

## ImageMagick

**ImageMagick** is an image manipulation library.

It allows programmers to:

* Resize images
* Convert formats
* Apply transformations

It also includes command-line tools, enabling automation through shell scripts.

---

## OpenSSL

**OpenSSL** is a cryptographic library.

Used in:

* Web servers
* Secure communications
* Command-line tools

It provides a standard interface for adding encryption and security features to applications and scripts.

---

## The C Library

At a lower level is the **C library**.

It provides basic functions for:

* Reading and writing files
* Input/output operations
* Display management

The C library is foundational:

* Used directly by C programs
* Used indirectly by many other programming languages
* Forms a core part of Linux system functionality

---

# Key Takeaways

* Linux provides excellent support for software development.
* Programming languages are either compiled or interpreted.
* C remains essential for operating systems and performance-critical software.
* Java achieves platform independence using the JVM.
* Interpreted languages increase development speed and flexibility.
* Popular scripting languages include JavaScript, Perl, PHP, Ruby, and Python.
* Libraries like ImageMagick and OpenSSL simplify complex tasks.
* The C library provides foundational system-level functionality.

Understanding development languages in Linux helps administrators and developers:

* Automate system tasks
* Build web and enterprise applications
* Improve system performance
* Maintain secure and scalable environments

Programming languages are tools—Linux provides a powerful ecosystem for using those tools effectively.

---