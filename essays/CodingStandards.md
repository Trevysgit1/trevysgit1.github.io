---
layout: essay
type: essay
title: "How to Ask a Smart Question"
# All dates must be YYYY-MM-DD format!
date: 2026/06/08
published: true
labels:
  - Stack Overflow
---

<img width="200px" class="rounded float-start pe-4" src="../img/Question.jpg">

## What is a Smart Question?
  The importance for asking smart questions comes down to getting assistance from knowledgeable people. One of the first guidelines is to search the internet, you should try looking up the questio[...]

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
