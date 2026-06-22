---
layout: essay
type: essay
title: "What is the Point of Coding Standards?"
# All dates must be YYYY-MM-DD format!
date: 2026/06/21
published: true
labels:
  - VS Code
  - ESLint
---

<img width="200px" class="rounded float-start pe-4" src="../img/Question.jpg">

## What are Coding Standards?
  Coding standards improve the readability of code and allow increase the chances of code being more useful in the future. For example, you may make variables that have nothing to do with the elemnt it's holding and in the future, it's hard to improve the code because you have to look at everything that it's connected to instead of writing a comment that describe what it does. Writing comments is one example of good practice of coding standards, it not only helps yourself but also allows for other people to understand the purpose of each line. One line of code can have many different purposes or use cases and just writing a label of what the code is used for and what it affects can help you or someone else look back in the future and understand what it does without investigating every connection it has to find the purpose.
  
  Another example of a coding standard is to make code more "readable". This is similar to adding comments to code because the purpose of both is to make future revisions or reviews of the code easier for the programmer, if they can easily tell what is going on they can start working on the problem quicker. Improving the readability of code also goes hand in hand with making the code more simple, for the most part less lines of code leads to easier readability. If you are able to solve the same problem or complete the goal of the code in less lines this should be a priority because adding unecessary elements decreases the readability because there are more elements they programmers have to process. Inconsistent indents between the same types of code can be an example of bad readability like having 4 spaces instead of 2 spaces at the next line of a loop or having inconsistent spaces between assignments like both sides of the equal sign not having the same spacing.
    
    
This is a simple example of bad code readability,
    
````
for(i= 0;i<5; i++) 
{
print i; }
````
        
This is an example of good code readability

````
for(i = 0: i < 5; i++) //loop will run 5 times until i = 5
{
print i;               //printing out value of i
}
````

## What does ESLint do?
The purpose of ESLint is to condition programmers into having better readability for their code.

## Finding a Bad Question
This is the example I found for finding a [question](https://stackoverflow.com/questions/1653958/why-are-ifndef-and-define-used-in-c-header-files) asked in a "not smart way". The question was "Why[...]

## Conclusion
When looking for examples on Stack Overflow I found that the more detail the poster was able to include about their question and the more descriptive they were with their goal, it led to more and [...]
