# Introduction: Software and Technology
* * *

// [Home](./README.md) //

## Programming Languages
* * *

What is a programming language?

[Wikipedia](https://en.wikipedia.org/wiki/Programming_language)

**Example**:
```
var movies = new Array();
movies.push(
    new Movie(Math.floor(Math.random() * 99999) + 10000,
    "Interstellar",
    "Science Fiction space movie",
    new Director(Math.floor(Math.random() * 99999) + 10000, "Christopher", "Nolan"),
    "10")
);
movies.push(
    new Movie(Math.floor(Math.random() * 99999) + 10000,
    "AeonFlux",
    "Science Fiction action movie",
    new Director(Math.floor(Math.random() * 99999) + 10000, "Karyn", "Kusama"),
    "5"));
movies.push(
    new Movie(Math.floor(Math.random() * 99999) + 10000,
    "Ex Machina",
    "Science Fiction drama horror movie",
    new Director(Math.floor(Math.random() * 99999) + 10000, "Alex", "Garland"),
    "2"));
for (var i=0; i<movies.length; i++)
{
    console.log(movies[i].getValue());
}
```

### Software development: Program Lifecycle Phase
* * *

[Wikipedia](https://en.wikipedia.org/wiki/Program_lifecycle_phase)

As a software developer, he/she would go through the following lifecycle phases

* Edit
* Compile
* Link
* Distribution
* Installation
* Load time
* Run time

Most modern programming languages does the phases for you collectively as one command rather than a developer explicitly execute a command to perform the action.

In our set of examples, we will be using **Javascript** as the programming language.

### Programming Language: Node JS
* * *

[Why the hell Would you Use Node.js](https://medium.com/the-node-js-collection/why-the-hell-would-you-use-node-js-4b053b94ab8e)

Javascript is one of the trending programming languages at the moment (2019).  Based on a [Stackoverflow Insight survey](https://insights.stackoverflow.com/survey/2018/#technology), Javascript is the most popular technology asked about and Node.js is the most popular programming language framework.

**Why should you learn about about Node.js?**

One of the most popular reasons why developers code in Node.js is that as a developer, I can write code in an IDE and run the code instantly when I am finished.  For a new developer learning a programming language, no additional steps are needed to run my application.

* Easy to install and use out of the box.
* A developer can write smaller applications intended for both internet and non-internet.
* Further interest beyond developing applications and into [Raspberry Pi](https://www.raspberrypi.org/), a developer can write cool things to work with [a Raspberry Pi device](https://www.w3schools.com/nodejs/nodejs_raspberrypi.asp).

Note: Once we start getting into more discussion about advanced topics and using build tools and extended Node.js packages and libraries, we can go into more details.  For now, we can focus on the core basics of Node.js.

## IDE - Integrated Development Environment
* * *

What is an IDE?

[Wikipedia](https://en.wikipedia.org/wiki/Integrated_development_environment)

Writing a set of code can be done in any text editor software.  The advantages of writing programming language code in an IDE software include:

* Easier programming code auto completion in real time.  In the process while you are writing code, the IDE software can easily assist you in giving you a matching keyword or command you may be referring to.
* Most IDE software assists you in building and running your script or application within the IDE software.  Without an IDE, a developer would need to run the build and execution commands in a command line terminal.

--

// [Home](./README.md) //

-- End
