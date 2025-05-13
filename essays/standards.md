---
layout: essay
type: essay
title: "Break the Rules"
# All dates must be YYYY-MM-DD format!
date: 2025-02-13
published: true
labels:
  - Software Engineering
  - Coding Standards
---

<img width="200px" class="rounded float-start pe-4" src="../img/standards/standards.jpeg">

*"You don't learn to walk by following rules. You learn by doing, and falling over."* — Richard Branson

In my college software engineering class, we're currently learning how to use integrated development environments (IDEs) to write code more efficiently. IDEs are built specifically for programming, having capabilities such as compiling and running code, being able to detect the programming language we are writing in and being able to detect some errors in real time as we type the source code. There are some other extensions that can be downloaded from other sources as well for further assistance. One such extension we are using in this class is ESLint.
 
## Isn't That the Thing from My Dryer?

Nope, different lint. ESLint is a tool used to ensure that our code follows certain *Coding Standards*. These standards are a set of guidelines that developers follow to make code more readable, maintainable, and consistent. Since software development is often a collaborative effort with other software engineers, it’s crucial for team members to be able to read and understand each other’s code easily. From my experience, ESLint focuses on improving readability and enforcing best practices for the language in use.

While working on assignments, ESLint would frequently suggest small adjustments — like changing 'let' to 'const' when a variable wasn’t being modified, or when I was only pushing values to an array. These nudges helped me pause and think more critically about the purpose and behavior of each line of code. The feedback it gave was usually clear, pointing directly to the issue and explaining the reasoning behind why the change was recommended. That being said, not every rule felt necessary. For example, ESLint insisted that I place a space before the opening curly brace '{' in functions, loops, or other blocks that required brackets. Not doing so would underline a large section of code in red, which at first made me think something was seriously broken in the code. In my opinion, that one space didn’t really improve the readability of the code and felt more nitpicky than helpful.

<div class="text-center p-4">
  <img width="400px" 
       src="../img/standards/Screenshot 2025-02-12 224234.png" 
       class="img-thumbnail" >
  <img width="400px" 
       src="../img/standards/Screenshot 2025-02-12 224312.png" 
       class="img-thumbnail" >
</div>

## Beyond the Classroom

While I agree that coding standards are helpful in creating readable code, especially in environments where teamwork is required, I feel that some of the rules enforced by ESLint can feel excessive. Minor style preferences like spacing before brackets don’t always impact the clarity of the code. Still, ESLint has also been helpful in ways that have helped me to write better code and better understand best coding practices when going through the error messages provided. 

Overall, my short experience with ESLint has shown to be helpful to my learning. Even if I don’t agree with every single rule, I plan to continue to utilize it to my benefit.
