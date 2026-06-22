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

  I feel like I had experience asking smart questions and I didn't realize it at first. One example that I can think of is when I have a question for my teacher I would look it up first and check [...]

<img width="200px" class="rounded float-start pe-4" src="../img/StackOverflow.jpg">

## Finding a Good Smart Question
On stack overflow, I chose to lookup the problem that we recently had for identifying unique characters in a string.[This is the post for the question](https://stackoverflow.com/questions/15623573[...]
````
#include<iostream>

int main()
{
string str = "dhAra";
bool arr[128] = {0};

for (unsigned int i = 0; i < str.length() ; i++)
{
 int val = str[i];  //i think something needs to change here 
 cout << val << endl; 

 if(arr[val])
 { 
  cout << " not unique" ; 
  return 0; 
 }
 else
 { arr[val] = 1;} 
}
cout << "unique" ; 
return 0 ; 
}
````
The solution to this question would be to convert all of the characters in the string to uppercase or lowercase. The top answer suggests that you can do this by by using either ```` toupper(str[i][...]


## Finding a Bad Question
This is the example I found for finding a [question](https://stackoverflow.com/questions/1653958/why-are-ifndef-and-define-used-in-c-header-files) asked in a "not smart way". The question was "Why[...]

## Conclusion
When looking for examples on Stack Overflow I found that the more detail the poster was able to include about their question and the more descriptive they were with their goal, it led to more and [...]
