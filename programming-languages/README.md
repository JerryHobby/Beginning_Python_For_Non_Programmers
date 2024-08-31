# Programming Languages

There are a lot of programming languages and they all have strengths and weaknesses.  But they all have some things in common.

All programming languages are a series of instructions that take information and analyze it and change it and finally produce some output.  You can break it down like this:

**DATA** - All the information a program needs to understand.  This information can come from a file, from a user clicking a button or filling in a form, or it can be stored inside the program itself.  For a simple example, a calculator has to know what numbers you want to calculate.  The numbers are keyed in and those numbers are calculated.   In the world of computers, there are two major types of data.  There are strings and there are numbers.   Strings are letters, words, sentences, etc.  Numbers are just numbers.  They can be added, subtracted, etc.

**OPERATIONS** - These are the functions that you can use on the data you have.  A calculator understands how to add, subtract, divide, multiply, amongst other things.   Computer programs can do all that and more.  Other common operations include printing to the screen, reading from a file, etc.

**LOGIC/FLOW CONTROL** - These are the parts of the language that let you decide what to do next.  For example, you might want to do something a certain number of times.  Perhaps you want to read the lines from a file until you have read everything in the file.  Once you reach the end, stop trying to read more lines from the file.   These includes commands such as IF, WHILE, LOOP, EXIT.

Every programming language has DATA, OPERATIONS, and LOGIC.  It's amazing how much every language has in common.  Once you learn one language, it's easier to learn the next.

## The Differences&#x20;

Each programming language has a syntax.  That means how each line in the source code is written.  In Python you construct each line following certain rules.  In other languages the rules are different.  One line of code in Python will look different compared to other languages even though they do the same thing.

Some languages are much harder to read and make sense of.  Python is much easier so that is why it is a good first language.

### Compiled versus Interpreted Languages

The code you write cannot be understood by the operating system directly.  It has to be converted into the binary code that the operating system, or hardware, can understand.

There are two approaches to this. &#x20;

#### Compiled Languages

A compiler reads the program you wrote and converts it into a binary package that the operating system can understand.  The process of compiling is also useful for detecting problems in your code.  Compiled languages also have the security that no one can read your source code. &#x20;

Compiled languages have some drawbacks.  You may have to compile different binaries for different types of computers.

#### Interpreted Languages

These languages remain in the original source code format.  An interpreter program is used to convert it every time the program is run.  Python, HTML, JavaScript, are all interpreted.  Because of that, they all need some form of interpreter to be installed.  HTML and JavaScript will run in a web browser.  Python requires the Python program to be installed.

Since these are not compiled, you do not need to compile different binary programs for each platform. &#x20;

### Low Level vs High Level

Think of computers as having layers. &#x20;

#### Hardware Layer

At the lowest level is the hardware.  Programming at this level is hardest because you have to know the specific hardware and all it's capabilities.  Nothing is done for you.  In real world terms, this is impractical for any type of application.  This level of programming is typically used only by operating systems and device drivers.

#### Operating System Layer

The operating system includes all the components and device drivers and providing a uniform way of accessing all of your hardware's capabilities through a simplified interface.  At this level, the operating system provides APIs (Application Programmer Interface).&#x20;

Programming languages that work on this layer are compiled, or built, and run natively with the operating system.  This would include the C/C++/C# languages amongst others.  Compiled languages are generally thought to perform faster but may take more effort to build.

#### Application Layer

There are applications on your computer that allow you to write programs that talk to those applications.  Those applications then talk to the operating system, which talks to the device drivers and hardware layers.  Great examples of this are Microsoft Excel and Python. &#x20;

In Excel, you can write scripts and embed those inside your spreadsheets.  Those scripts cannot run without Excel.

Python is considered an interpreted language, so it does require the Python application to be installed and running in order for your Python script to run.

All interpreted languages are like this.  They do not get compiled so they need an interpreter to read the script and give commands to the operating system.  Which this is slower than compiled languages, the difference is small.

#### Frameworks

Most programming languages support certain frameworks.  Frameworks were created to simplify a programmers ability to perform certain tasks.  For example, if you want to build a Windows application that has form fields, buttons, etc., you want all those things to look the same as they do in other programs.  To make all this easier, Microsoft created a framework called .NET.  It has simplified a lot of the work in programming for windows.  Not all languages support .NET.  If you want to write a native app for Microsoft Windows, you'll want to consider a language that supports .NET.

There are a lot of frameworks for different things.  If you program in JavaScript, they have frameworks.  If you program for mobile devices, those have frameworks.

The idea of a framework is to provide a simplified way to do the most popular things.  That may included database access, graphics card programming, or web pages.









