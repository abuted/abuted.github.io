---
layout: essay
type: essay
title: "The Blueprint for Writing Better Code"
# All dates must be YYYY-MM-DD format!
date: 2024-12-4
published: true
labels:
  - Software Engineer
  - Design Patterns
---

<img width="200px" class="rounded float-start pe-4" src="../img/code.webp">

## Introduction

The first time I heard the term "design patterns" in computer science, I didn't understand what it meant. Over time, I figured out that design patterns are like blueprints or templates that solve common coding problems. Instead of coming up with a new solution every time, developers can follow these patterns as ways to handle challenges in their code.

The main categories of design patterns are: **Creational**, **Structural**, and **Behavioral**. Creational patterns help with creating objects, structural patterns focus on organizing code, and behavioral patterns deal with the interaction between different parts of the code.

## Why Design Patterns Matter

One of the most important things I learned about design patterns is the way they make the code more readable and maintainable. Each programmer could find his or her own solution to the same problem, turning the code into chaos, with inconsistencies everywhere. Design patterns also help simplify things. Instead of figuring out a new solution every time, I can use a pattern that has already been tested and works well. This saves me time and makes my code more reliable since I'm building on something that others have used successfully.

## Useful Design Patterns: Creational, Structural, and Behavioral

One example of a creational pattern is the **Factory Method. It is great when you need to create objects, but you don't want to hardcode everything in different parts of your program. For example, if I need to set up different types of users in some system, I can keep the user creation logic in one place. That way, I don't have to go back and change multiple sections of the code if I happen to need to add a new user type later.

For structural patterns, there is the **Adapter**. Sometimes, two parts of my code just don’t fit together, like when I’m using an external library or API that works differently than my code. The Adapter acts like a bridge or translator between the two, letting them work together without me having to rewrite everything.

One behavioral pattern is the **Observer**. This is helpful for applications that need to refresh automatically in response to changes. If data in my application gets updated, the Observer notifies all the parts of the application that should know. This saves me from having to manually update each part, which makes the code cleaner and less vulnerable to errors.

## How I've Used Design Patterns

I used design patterns to improve my code in many projects. In the final project we are currently working on, we applied the **Observer** pattern which can be used to notify different parts of the app when new jobs are posted or when students update their profiles. For example, if a company posts a job, the system can notify all students who match the job criteria.

Additionally, we had to handle different user roles like student, company, and admin. The **Factory Method** can be used to manage the creation of these user objects by centralizing the logic in one place. This approach makes the code more organized, easier to maintain, and flexible for adding new user roles in the future.

For our final project, we built on a pre-existing Next.js template that was provided to us. This template served as a foundation, allowing us to focus on adding the necessary features and files for our application. It made the development process much easier and more efficient since many of the important components were already set up for us.

## Conclusion

Design patterns are the ready-made solutions for common coding problems. They help make code cleaner, easier to maintain, and more efficient. When using design patterns like **Factory Method**, **Observer**, and **Adapter**, you are able to solve problems more smarter and in a more organized way. I will continue using design patterns in my future projects to make my code even better and my work more efficient.

**Sources:**
- [Refactoring Guru: Design Patterns](https://refactoring.guru/design-patterns) 
- [GeeksforGeeks: Introduction to Design Patterns](https://www.geeksforgeeks.org/design-patterns-set-1-introduction/)
