---
layout: essay
type: essay
title: "Aloha Archives: Your Window into Hawaii’s Data and Insights"
# All dates must be YYYY-MM-DD format!
date: 2024-12-16
published: true
labels:
  - Software Engineering
  - AI
---

<img width="200px" class="rounded float-start pe-4" src="https://i.postimg.cc/YpQ0cdnF/d66076d0-b28e-4856-bf49-7f8cc24cd302.webp">

<br><br>

# Reflection of AI in 314: AI as a Tool for Learning

The use of AI has seen rapid growth in recent years, with the boom of its capabilities seen with the advent of the ever-famous learning language model ChatGPT. In this essay, I will highlight my use of AI in ICS 314: Software Engineering, and give an ethical analysis of that use. I will give examples of the use of it in WOD (Work of the Day) assignments, as well as its help in stylistic choices in essays.

In terms of the breadth of the AI technology which I utilized this semester, I only ever used ChatGPT and opted not to use GitHub Copilot since it's a paid service alongside it. Specifically, I primarily used the GPT-4 model, as I’m not as familiar with the newer 4.1 model. While I played around with Claude—whose benchmarks in capabilities like math and writing exceed ChatGPT’s considerably—I was mostly interested in using Claude for its ability to control the computer on a prompt. This proved difficult and unsafe to do without also installing a virtual machine with lower privileges.

## AI in WOD Assignments
In an example of using ChatGPT to help out with a WOD, let’s take a look at the first Jamba Juice assignment from early on in the class. This assignment was threefold, which was to:

1. Create a class called `MenuItem`, with a constructor that takes:
   - A name (string),
   - An array of ingredients (strings),
   - An object whose keys are `small`, `medium`, `large` and whose values are the associated prices, and
   - Another object with the above keys and the associated calories.
2. Create instances of `MenuItem` for `PapayaSunrise`, `PeachPerfection`, `StrawberryDragon`, and `StrawberryWhirl` (an array of different juices, essentially) using the console to check that they represent their item correctly.
3. Create a class called `Menu`, which provides access to one or more `MenuItem` instances. It has an `addMenuItem()` method to add a `MenuItem` subclass to the menu as well as a `findMenuItems(ingredient)` method that takes an ingredient string and returns all of the `MenuItems` that contain that ingredient.

In essence, the goal of this assignment was to create TypeScript classes to represent four menu items and use them to define another class called `Menu`.

As long as one is familiar with TypeScript syntax, the program for this assignment is rather simple. To save me time, I used ChatGPT by copying the contents of the WOD instructions and generating an answer similar to what I would have written myself but in considerably less time. This process saved me from redundancy but also taught me to a greater extent. Whenever I used a prompt like this to complete an assignment, I always made sure to ask questions about the code or the assignment to best understand it. I never submitted anything until I understood it sufficiently.

## AI in In-Class Practice WODs and In-Class WODs
For in-class practice and timed WODs, ChatGPT was primarily a backup tool. When I struggled with specific array methods or syntax in JavaScript or TypeScript, I used it to generate quick examples or clarify functionality. For example, during a practice WOD involving array filtering, I consulted ChatGPT to review the `.filter()` method, which helped me avoid unnecessary debugging during the timed session.

## AI in Essays and Writing
As another example, in the essay that I made for the class titled _The Flowing Philosophy of Coding Standards: Far Greater than Formatting_, I highlighted the importance of having proper syntax and its consequences within Software Engineering. While I did ask for ChatGPT’s help in improving some sentences, the writing is my own. ChatGPT served as an editing tool, suggesting ways to make the essay flow better and adhere to formal writing conventions.

## AI in the Final Project
In the final project, I utilized it to give skeleton code and suggestions for React components while I ironed out where the components were to be placed. For instance, in creating the Favorite Datasets functionality of the ALoha Archives website, it gave me skeleton code that gave basic functionality to add a heart React component and the ability for it to change to a filled heart symbol when clicked. I handled the styling and further functionality of adding it to the favorite datasets page after many, I must say grueling, hours.

## AI for Learning Concepts and Tutorials
Outside of assignments, I used ChatGPT as a tutorial tool to learn new concepts. For example, I asked ChatGPT to explain `.pluck()` from Underscore.js, which I found useful when working on coding problems that required extracting data from arrays of objects. Additionally, when I asked it to create a Python program to simulate the odds of a plane crash, it gave me a helpful overview of Python’s basic syntax, including print statements, loops, and conditionals, which I hadn’t encountered before.

## AI in Asking and Answering Questions
This was an instance that I never used AI.

## AI in Explaining and Documenting Code
When it came to explaining code, ChatGPT helped me articulate the purpose and functionality of specific blocks of code. For example, when documenting a function in a WOD assignment, I used ChatGPT to suggest concise explanations for my comments, ensuring they were both accurate and easy to understand.

## AI in Quality Assurance
Quality assurance was another critical area where it was useful. In the same way that comments are essential for other developers understanding of the code (and the saving our sanity, to be honest), AI being able to come up with such clear comments of the written code was a good use of the tool.

## Ethical Use of AI
At the same time, it is important to consider that it is easy to become complicit and lazy in the use of such technology. If I so wanted, I wouldn’t need to ask ChatGPT to explain the work, mindlessly spitting out the answer it gave for the programming when it could very well be garbage. In my endeavor to learn, I attempt to mitigate this at all times and so make sure that I have properly understood the material before submitting.

## Conclusion
In conclusion, while ChatGPT and its use as a tool for learning is great, it can be used in an unmindful way and have a negative impact on learning in general through being complicit in its use. I have utilized it, to the best of my ability, to teach me the principles of which this class set out to achieve in the minds of its students. This was done through utilizing its suggestions and formatting its ideas to my own work and style. Whether assisting in WODs, essays, the final project, or learning new concepts, ChatGPT has proven to be a valuable learning aid when used thoughtfully and ethically.
