---
layout: essay
type: essay
title: "The Importance of Asking Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2024-09-11
published: true
labels:
  - Smart Questions
---

<img width="200px" class="rounded float-start pe-4" src="../img/questions.jpg">

## Introduction

In software engineering, asking clear and well thought out questions is really important, especially on platforms like StackOverflow, where people help each other out. Eric Raymond’s essay How to Ask Questions the Smart Way explains that when developers take the time to research and clearly explain their problems, they are more likely to get useful answers. In this essay, I'll explore why asking "smart" questions is very important by looking at examples from StackOverflow. I’ll compare a good question with a not-so-good one to show how asking questions in the right way can lead to better help.

## The Smart Question

**Title: "C++ map with custom comparator not inserting all elements [duplicate]”**

**Content:** This question on StackOverflow talks about a problem where a C++ std::map with a custom comparator isn’t inserting all its elements. The problem is that the custom comparator always returns 1, which messes up the sorting of keys. The comparator isn’t doing what’s needed for std::map to keep keys in order. Since the question was clear and detailed, the StackOverflow community was able to respond with useful information. They point out that the custom comparator is not working because it always returns 1. This means it doesn't actually compare the elements in the map. Without proper comparisons, the map can't order or manage its elements correctly. They also provided links and explanations to help the developer understand why this was happening and how to fix it.

**Link:** [Example of smart question](https://stackoverflow.com/questions/44508059/c-map-with-custom-comparator-not-inserting-all-elements)

## The Not Smart Question

**Title: "Python code doesn't run, I don't know what to do to fix it."**

**Content:** This question is unclear. The developer says their Python code isn’t working but doesn’t explain what the code is supposed to do or what kind of error they’re facing. They mention that they are running the code in PyCharm and is facing issues with the script not executing and that they are using Python 3.7. They also just paste a chunk of code without describing the problem, and they don’t mention any steps they’ve taken to fix it. The response talks about Python rules and standards which was unclear and not useable. It mentions that the code doesn't comply with Python rules without specifying which rules or providing concrete examples. Additionally, it fails to address the specific problem mentioned in the question: why the script is not running in PyCharm and how to fix it. It focuses more on general coding standards and less on practical debugging steps relevant to the issue given.

**Link:** [Example of not-so-smart question](https://stackoverflow.com/questions/61253130/python-code-doesnt-run-i-dont-know-what-to-do-to-fix-it)

## Why Smart Questions Work Better

##### Being Clear and Detailed

In the first example, the developer followed Raymond’s advice by being specific. They explained their problem in a clear way, shared the exact part of the code causing the issue, and showed they had done some research and testing. This made it easy for others to understand the problem and give helpful answers. In the second example, the developer didn’t give enough information. They didn’t explain what the code was supposed to do or what went wrong. As a result, the community couldn’t help as much and the developer might have still been confused. Without enough detail, the answers weren’t useful or helpful for the developer.

##### Respecting Others’ Time

Raymond says that asking smart questions shows respect for the time of others who are trying to help. The developer in the first example did this by providing all the necessary information along with his question. They didn’t waste anyone’s time by making people guess the problem. The second developer, on the other hand, didn’t respect the community’s time. By pasting a chunk of code without explaining the issue, they expected others to figure it out on their own, which made people less willing to help.

##### Problem-Solving Mindset

The first developer approached the question with a problem-solving attitude. Instead of asking someone to fix the problem for them, they asked for help understanding why their solution wasn’t working. This encouraged more thoughtful answers that helped them learn and improve their code. The second developer just wanted someone to fix their code without putting in effort to understand the problem. This attitude made it harder for others to engage and offer useful help.

## What I Learned

This shows that asking smart questions leads to better results. The first question received helpful and detailed answers while the second question led to confusion and useless help. This shows that taking the time to clearly explain your problem, show your own efforts, and ask for understanding makes a big difference in the quality of responses you get. Asking questions the smart way is not just about getting quick answers. It’s about showing respect, building a positive community, and helping yourself and others learn. When you put in the effort to ask smart questions, you make it easier for people to help you.

## Conclusion

For software engineers, asking smart questions is important for getting the help you need and creating a supportive community. Clear and detailed questions lead to faster, more useful answers, while unclear or poorly worded questions can waste time and cause frustration. Following the guidelines from Eric Raymond’s essay can help developers ask better questions and improve the overall quality of their interactions with the community.
