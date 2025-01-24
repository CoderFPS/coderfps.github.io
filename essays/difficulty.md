---
layout: essay
type: essay
title: "New Semester Reflection: Reaction to TypeScript and a New Class Format"
# All dates must be YYYY-MM-DD format!
date: 2024-01-2
published: true
labels:
  - Engineering
  - Learning
  - JavaScript
  - TypeScript
---



## Introduction

I have recently been introduced to TypeScript through school. I come from a Java background, so it has been my strong suit or a safe point regarding coding. When I first tried TypeScript, the parallels to Java were super clear, especially in its syntax and the clarity it provides when defining variables and function signatures. But TypeScript isn’t just “JavaScript with types.” It blends how dynamic JavaScript is with a powerful type system, giving coding with it much more freedom.

This essay will reflect on my experiences with TypeScript, explain why I find it pleasant to use, and share thoughts on the “athletic software engineering” approach (with some specific reference to WODs) that has shaped my learning process 2 weeks into my 4th semester as Computer Science Major at the University of Hawaii at Manoa. Throughout the essay, I will highlight what I’ve learned about TypeScript’s functionality, discuss its value from a software engineering standpoint, and attempt to explain how it can enhance productivity and code quality.

<img 
  src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/2048px-Typescript_logo_2020.svg.png" 
  alt="TypeScript Logo" 
  title="TypeScript Logo"
  width="200"
/>

## Why I Enjoy TypeScript

I’ve always enjoyed writing Java, and TypeScript provides a similar style while feeling much more simple and flexible. Unlike basic JavaScript, TypeScript’s ability to specify variable types makes me feel much more secure while coding in the same way I hate doing loops in Python and prefer Java. This means fewer runtime surprises. For example, if I declare a variable as a string, the compiler ensures I don’t accidentally assign it a numeric value later.

TypeScript’s benefits go beyond type safety. One feature I’ve learned to appreciate is type inference. TypeScript can infer a variable's type based on how it’s initialized, which cuts down on length declarations. For instance:
<pre>```typescript
// TypeScript infers 'message' as a string
let message = "Hello, TypeScript!";
```</pre>
Without me explicitly stating that the message is a string, TypeScript infers it from the initial assignment. This balances the best of both worlds: strong typing when I need it and easy, readable code when I don’t.

## From Java to TypeScript (with JavaScipt in Between)

Before starting to learn TypeScript, I knew a fair amount of JavaScript. I knew many ES6 features like arrow functions, template literals, and destructuring. Despite this, going through lessons that explicitly connected JavaScript to TypeScript helped me understand how TypeScript builds on modern JavaScript while adding types, interfaces, and other enhancements.

One new thing I learned about TypeScript’s functionality is its support for advanced types—such as union types (e.g., string | number) and interfaces that allow you to define more complex object shapes. As someone with mainly Java experience, I feel these features are very comfortable. They make my code more expressive than Java at times, particularly when describing objects or functions that may behave differently depending on the context.

## Is TypeScript a Good Language from a Software Engineering Perspective?

In my opinion, TypeScript is an excellent choice from a software engineering standpoint. It has much cleaner code, reduces bugs early through compile-time checks, and makes refactoring far less risky. In large-scale projects, having explicit types means:

- Easier Onboarding: New developers can read method signatures and interface definitions to understand what data flows through the system.
- More Predictable Refactoring: The TypeScript compiler immediately points out mismatches and potential issues.

<img
  src="https://www.aacc.edu/media/college/images/areas-of-study/technology/Computer-Classroom_AACC-03-15_141_optimized_1200x600.jpg"
  alt="Class with Laptops"
  title="Class with Laptops"
  width="400"
/>

  
## Reflections on Athletic Software Engineering

Beyond the language, I’m also a big fan of the athletic software engineering approach. In my experience, the best way to learn any technical topic is by reading a little bit and then just practicing till I feel confident so I understand what I don't know and work out the kinks of these topics in practice, not just in theory. Athletic software engineering forces you to tackle exercises known as WODs (Workouts of the Day) within a certain amount of time. The benefits of this approach are:

- Encourages Mastery: If you genuinely know a concept, you can implement it efficiently under time pressure.
- Builds Confidence: Knowing I can solve a problem in a timed environment reduces my stress when facing accurate testing or production scenarios.
- Keeps It Interesting: There’s less chance of boredom because I’m actively engaged, trying to solve real problems rather than just sitting through a lecture.
- 
These practice WODs are extremely useful because they confirm whether I’ve learned the curriculum. If I miss a concept, I’ll discover it through the WOD.

## Learning Style and Classroom Dynamics

One of the highlights of athletic software engineering is that it also complements the flipped classroom environment. By working on materials at home, I learn what I understand versus what I don't know. Then, during class, I focus on clarifying those parts I am stuck on. This structure:

- Maximizes Class Time: We spend classroom hours solving problems, exchanging ideas, and deepening our understanding.
- Reduces Passive Learning: Instead of attending lectures where I might(will) tune out, I’m constantly engaged and applying new concepts.
- Promotes Efficiency: every moment in class is dedicated to improving my skills rather than repeating what I could learn independently.
  
Ultimately, this style keeps me motivated and ensures I work toward practical competency rather than memorizing facts for a test when I probably cannot even do those in practice.

## Conclusion

In summary, TypeScript has become one of my favorite languages because it combines Java’s type safety with JavaScript’s flexibility. Its features—such as type inference, advanced type definitions, and powerful tooling—make it an excellent choice for large-scale software engineering projects. Combining TypeScript with the athletic software engineering approach has been enjoyable and practical from a personal learning standpoint. I’m more confident, less stressed, and excited to keep building my expertise by practicing and writing real-world applications.

Anyone contemplating investing time in TypeScript and athletic software engineering should do so.



