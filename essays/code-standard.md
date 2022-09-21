---
layout: essay
type: essay
title: "Coding Standards: Why you Should Consider Coding like Everybody else"
# All dates must be YYYY-MM-DD format!
date: 2022-09-20
published: true
labels:
  - Code Standards
  - ESLint
  - Javascript
---

## The Importance of Coding Standards
 
In coding, there are often many different ways to arrive at the solution to a problem. Some would argue that it does not matter if the solution is “pretty” or not, as long as it gets the job done. Technically, this is true. The code will still produce the correct output if you have an unused variable, or if you have two blank lines after the final line of code instead of one. For this reason, many do not care much about coding standards, which are sets of rules and requirements that developers follow when writing code. However, there are many ways in which coding standards can be extremely useful to software engineers. Having coding standards can help improve the readability of code, making it easier for people to understand the code of their peers or coworkers. On the other hand, if people did not follow a set of coding standards, it may be very difficult for a person to understand code that was developed by a different person. If this were the case, maintenance and further development of the project would be challenging without the help of the person who wrote the original code. Additionally, having coding standards can help simplify the debugging process, as finding the lines or blocks of code that are causing errors will be much easier. To summarize, coding standards can be quite helpful to the development process, even if they are technically unnecessary. 

## IntelliJ and ESLint

Prior to a week ago, I had never worked with any sort of integrated development environment (IDE) that actually “cared” about coding standards. I could have unused variables, inconsistent amounts of whitespace, or any other coding standard “violation” as long as the code produced the correct output. None of my previous professors would deduct points based on coding standards, so they were not something I was ever really concerned with. Nothing could be further from this lack of standards than IntelliJ with ESLint. When using the IntelliJ IDE with ESLint, every violation of the ESLint coding standard gets flagged as an error. Many of these violations would not even show up as a warning in other IDEs that I have used previously. Things like whitespaces, declaring a variable as a let or const, and variable usage suddenly go from not mattering at all to extremely important. Learning to account for ESLint’s coding standards will be an adjustment, to say the least. 

As for my personal thoughts on IntelliJ and ESLint so far, it is a bit of a mixed bag. On one hand, I can clearly see where ESLint is helpful in cleaning up code to make it more efficient and concise. Getting to see what functions and variables are unnecessary to the program is quite useful, and seeing what data type a variable should be initialized as can help me better understand what the purpose of that variable is. As I continue to work on more complex projects, I will likely find other ESLint coding standards that will help with the development process. On the other hand, there are a number of ESLint coding standards that I am not the biggest fan of. Some of the standards that involve whitespace are a little excessive to me. For example, I do not really understand why it is necessary to have a space between the “for” and the open parenthesis when using a for loop. It does not improve readability in my opinion and seems inconsistent with the formatting for functions, which does not have a space between the function name and the open parenthesis. Standards like this one are a little painful to follow. 

## Conclusion

While coding standards are considered insignificant by many, they can be incredibly helpful for improving the readability and comprehension of code. This is especially important when many coding projects involve thousands, if not millions of lines of code. Using coding standards will help with creating both readable and efficient code, not just something that works or does not work. 
