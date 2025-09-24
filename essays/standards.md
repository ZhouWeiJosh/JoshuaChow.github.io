---
layout: essay
type: essay
title: "Everything in One Line, a Simple Standard"
# All dates must be YYYY-MM-DD format!
date: 2025-09-23
published: false
labels:
  - Software Engineering
  - Coding Standards
---

<img width="500px" class="rounded float-start pe-4" src="../img/software.png">

## A Standard I Believe In

Where are your brackets when coding a function? Do you have one in the same line as the function declaration? 

```
int addNum(int a, int b) {
  return a + b;
}
```
Or do you have it on separate line?
```
int addNum(int a, int b)
{
  return a + b;
}
```
Personally I prefer the former as it was the standard that I started with. However, many people do it in the latter way and there is nothing inherently wrong until it clashes with someone elses coding standard. It creates confusion and breaks the consistency that you expect with code, therefore when working on large codebases it is important to establish a foundation of rules. Unless you are required to write the most efficient code in the world, it is important that you and most important other people can understand it. The goal is to make code that is easy to follow and adaptable, for the overall development cycle. If you make something that is confusing and convoluted, it deters many from wanting to help you or assist you when you have a bug. It is just extra work for me to try to figure out what you are doing, limiting the scope of efficency and reliability. 

## Return of the Keyboard Warrior

There are many obvious types ways to make ones code more readable and consistent, but you have to portray it to others as well. You can not expect one person to adhere to the way you code without letting them know the reasoning and the function behind it. Besides that some standards that are important to all programmers is giving variables names that make sense. I understand if the code that you are making is rough, but having finalized code with variables declared with just single letter is not acceptable. Imagine looking back at code you wrote months ago to find that you had 'a' and 'b' as variable names and have to take even longer to figure out what it means. The same applies to function names as well, simply name a function 'doesSomething()' does not really bring any ease to your life. Every function does something, but you have to be somewhat specific. Another thing to note is having functions that do too much things. I have made the mistake many times where I have a function that does too much things. The goal is to keep a function to do exact what you named it to do. If you it starts getting convoluted, consider making another function that simplifies what you are doing. The last thing you want is to have someone use your function and it return something unexpected. Be clear and consise. Moving on to consistence with variable and function naming is camelCase, capitalization, and underscores. 

```
const int PI = 3.14 // Usually used for constants
int ledOn = true // camelCase
int led_on = true  // underscores

int AddNum(int a, int b) {    // Capitalization
  return a + b;
}

int addNum(int a, int b) {    // camelCase
  return a + b;
}

```
Using camelCase and underscore are standards that are used to specify variable names with more than one word. As show above, camelCase involves always a lower case word followed by a capitalized first letter. While underscores are used to separate the words. What is shown above is based on rules or standards provided by the group/company, but constant are usually maintained with all capitalized letters. Functions however can either be camelCase or capitalized for each word, and that is still based on how the specific group/company want it to be formatted. A final note that bares quite importance is how you space out your code, some choose to have no spaces but other choose to break the continous lines with spaces. Personally speaking, I prefer using spaces as it helps with readability which I find really important. However, some people do not use spaces or indents which can make it hard to read at times. 

## Learning Over Multiple Lines

In a world where there is a lot of confusing and seemingly impossible tasks, being able to articulate is more important than ever. And code is just one way of expressing that you understand the art of it. I aim to write code that is digestable and allows for maintainability. And at this moment in time that part is still difficult to me. I am a novice in many ways and I understand that. However, if I keep working towards the path of spending the time to make things just a bit more convinent, does everyone a bit of justice. So I impore you to take the steps to write good code that allows for growth and learning, I know I will. 
