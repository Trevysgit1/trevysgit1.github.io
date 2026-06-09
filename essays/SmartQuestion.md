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
  The importance for asking smart questions comes down to getting assistance from knowledgeable people. One of the first guidelines is to search the internet, you should try looking up the question that you have on the internet to check if a solution already exists before asking people to take time to assist you. If you are unable to find a solution that already exists the next step is to formulate the question clearly. This includes a goal, steps that were already taken, a problem if it exists, and other context like the programming language, problem conditions and assumptions, or operating system, and the most important would be to ask the question in the right place. The importance of asking smart question is for the benefit of the person who is asking and answering the question. If you are asking a question and it is not clear what you are asking you may not find an answer that applies to your question because you constructed the question improperly or no one is able to answer your question becuase you are not asking it in the right place. If someone is answering the question, smart questions are important because your time may be wasted by someone being able to easily look up a question that already has a solution that exists, or if it is missing details like steps that have already been taking or the goal is unclear may not benefit either person. 

  I feel like I had experience asking smart questions and I didn't realize it at first. One example that I can think of is when I have a question for my teacher I would look it up first and check if I could find the answer on my own. If I couldn't find an already existing solution I would consult a classmate or a friend to see if they have the answer and are able to explain it to me. The final step would be to bring the question to my teacher with the work I have already done and the exact problem that I'm facing so they can best help me. This is the process that Eric Raymond describes to ask a smart question and it made me realize that smart questions apply to anything not just getting help with a programming solution. 

<img width="200px" class="rounded float-start pe-4" src="../img/StackOverflow.jpg">

## Finding a Good Smart Question
On stack overflow, I chose to lookup the problem that we recently had for identifying unique characters in a string.[This is the post for the question](https://stackoverflow.com/questions/15623573/check-if-string-has-unique-characters), I picked this question because it followed all of the requirements and the question was asking how to differentiate capital letters from lowercase letters when checking for uniqueness. The example that is provided was string = "dhAra" and he would like it to return "NOT UNIQUE" but "UNIQUE" is being returned. This is the snippet of code that he provided to show the progress he currently has.
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
The solution to this question would be to convert all of the characters in the string to uppercase or lowercase. The top answer suggests that you can do this by by using either ```` toupper(str[i]) ```` or ```` tolower(str[i]) ```` This is a good example of following the guidelines of a smart question to get an answer that helps you best. 


## Finding a Bad Question
This is the example I found for finding a [question](https://stackoverflow.com/questions/1653958/why-are-ifndef-and-define-used-in-c-header-files) asked in a "not smart way". The question was "Why are #ifndef and #define used in C++ header files". This breaks on of the first principles established by Raymond of attempting to look up the answer on the internet. When I looked up the question on the internet I was able to find many sources answering the question that that explains what guard code is. Although, the post was able to get an answer explaining what guard code is and how it works, it can save time for the responders if the poster is able to find the answer themself by looking it up.

## Conclusion
When looking for examples on Stack Overflow I found that the more detail the poster was able to include about their question and the more descriptive they were with their goal, it led to more and better answers and also more views and upvotes indicating a lot of people benefitted from the post. I feel like it is important to ask smart questions because you are asking people with more knowledge and experience to take time and effort to explain the problem to you. So the more you can help them and make it easier to help you the more help you would recieve and everybody will benefit more from questions that are asked properly with detail than not. 
