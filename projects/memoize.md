---
title: Memoize
length: 1 week
tags: javascript, react
---

# Memoize

1 week solo project for FE Mod 2 (Week 6)

## Background and Description

For this project you will be working on your own to write a program in React. Specifically, you will be creating an application that solves a common problem that most students face when reviewing course material/concepts - finding effective study techniques to optimize learning retention and recall.

Check out some of these learning tools from the wild:  

* [Visualizing the Call Stack](http://latentflip.com/loupe/?code=JC5vbignYnV0dG9uJywgJ2NsaWNrJywgZnVuY3Rpb24gb25DbGljaygpIHsKICAgIHNldFRpbWVvdXQoZnVuY3Rpb24gdGltZXIoKSB7CiAgICAgICAgY29uc29sZS5sb2coJ1lvdSBjbGlja2VkIHRoZSBidXR0b24hJyk7ICAgIAogICAgfSwgMjAwMCk7Cn0pOwoKY29uc29sZS5sb2coIkhpISIpOwoKc2V0VGltZW91dChmdW5jdGlvbiB0aW1lb3V0KCkgewogICAgY29uc29sZS5sb2coIkNsaWNrIHRoZSBidXR0b24hIik7Cn0sIDUwMDApOwoKY29uc29sZS5sb2coIldlbGNvbWUgdG8gbG91cGUuIik7!!!PGJ1dHRvbj5DbGljayBtZSE8L2J1dHRvbj4%3D)
* [Git Branching](https://learngitbranching.js.org/)
* [FlexBox Froggy](https://flexboxfroggy.com/)
* [Flow Chart Click-Through](http://learntocode.westminster.ac.uk/codeVisAlpha.php)

While the application you build doesn't have to be as complex as the examples above, know that you have the freedom to be ambitious and take your study tool in whatever direction you choose.

## Goals and Objectives

- Build an application with React and Sass
- Construct dataset to be used to implement array mutator and iterator methods to work with data
- Demonstrate your ability to communicate expert-level knowledge on a technical topic
- Write modular, reusable code that follows SRP (Single Responibility Principle)

# Requirements

## Technologies

* **the web storage API** for persisting data
* **the fetch API** for sending/receiving data
* **ReactJS** for organizing your application into components
* **JSX** for writing your component templates
* **Sass** for getting fancy with your CSS

Technologies not listed above *require* instructor approval

## Custom Dataset

* You must create one dataset that will represent your application data.

* Your dataset must have at least 15 records (If your dataset is an object, it should have 15 keys. If it's an array, it should have 15 elements)

* You must run your dataset through a [JSON validator](https://jsonlint.com/) before submitting a pull request for your dataset [here](). Your datasets should be added in a single file to the `/datasets` directory. Be sure to export at the bottom of your file.

## Interactivity

* App must have some form of interactivity for the user
  * it should **not** just be text on a page with links, though it may include some instructions or resources to learn more
  * interactivity should help your users understand the topic you've selected (e.g. if your topic is DOM manipulation with jQuery, maybe the user can click an element on the page and some text would appear to show them how they would select it with jQuery code) 

## Local Storage

* Your application should have a use-case for persisting information client-side

## README

Your README should include the following, in this order:

- Abstract at the top (A sentence or two describing the project)
- Install/Setup instructions
- Everything else (must include wireframes and screenshot/GIF of finished project)

## Topic

* App must be centered around a technical topic that you've learned or heard about in Mod 1/2, and:
  * demonstrate your expert knowledge on the concept
  * allow others to learn and practice the concept

### Potential Topic Ideas

* DOM Manipulation with jQuery
* Recursion
* The Call Stack
* Prototypal Inheritance
* Sass/CSS (Should be narrowed down to something specific, like flexbox, pseudoselectors or how the specificity/cascade works)
* Scope
* Prototype Methods
* Git/GitHub Workflow
* Terminal Commands/Navigating the Terminal
* Technical Vocabulary
* Sorting Algorithms
* Pseudocoding/Whiteboarding
* LocalStorage

You are free to pick from this list, use it as inspiration, or pitch your own topic. As you go to pick your topic, take the following into consideration:

* What type of tool do you want to build? are there any topics that lend themselves easily to that learning format?
* What topics were you hoping to learn more thoroughly or what topics did you feel fuzzy on? this is a good opportunity to give yourself a chance to explore them further (e.g. if you have a hard time remembering terminal commands - building a study tool will help you get better at them!)
* Your topic should be specific and focused - the more specific your topic, the easier it will be to build a manageable study tool to demonstrate it

# Rubric

## Specification Adherence

* [ ]  Novice - The application is missing multiple features/requirements outlined above. 
* [ ]  Advanced Beginner - The application is in a useable state, but is missing part of one or more of the technologies outlined above.
* [ ]  Proficient - The application uses the above technologies to a professional level. 
* [ ]  Exceptional - Meets all expectations of `Proficient`. In addition, the application has additional features/extenstions implemented that are not specified.

## UI/UX

* [ ] Novice - The application is confusing or difficult to use. The UI is incomplete.
* [ ] Advanced Beginner - The application may be confusing or difficult to use at times. The application shows effort in the interface, but the result is not effective because UX and/or UI still present an application that is incomplete or difficult to use.
* [ ] Proficient - The application has many strong pages/interactions. The application can stand on its own to be used by instructor without guidance from a developer on the team. The application is fully responsive.
* [ ] Exceptional - Meets all expectations for `Proficient`. In addition, the application has clearly had special consideration around usability on devices. 

## JavaScript / React Style

* [ ] Novice - There is a significant amount of duplication and one or two major bugs. JavaScript does not follow the principles of `DRY` (Don't Repeat Yourself)
* [ ] Advanced Beginner - There is some duplication and there may be one or two major bugs. The application has large components and logic could be broken apart into smaller, function components. JavaScript may be hard to read/follow.
* [ ] Proficient - Application has little to no duplication and no major bugs. Application has several components built out that logically break apart the functionality. JavaScript may be hard to follow at times but is generally easy to read/understand. 
* [ ] Exceptional - Application has exceptionally well-factored code with little or no duplication and all components separated out into logical components. There are zero instances where an instructor would recommend taking a different approach to design and component architecture. DRY and SRP (Single Responsibility Principle) practices are incorporated, making JavaScript very easy to follow/read.

## CSS/Sass Style

* [ ] Novice - There are several (10+) instances of duplication and one or two major bugs. Developers write code with unnecessary selectors or tags which do not increase clarity.
* [ ] Advanced Beginner - There is some duplication (5-10 instances) in the codebase. There may be one to two minor bugs. There may be some unncessary selectors or tags. Application adds organization for the whole stylesheet and within rules.
* [ ] Proficient - Application is thoughtfully put together with comments to help guide organization. There may be some duplication (fewer than 5 instances) present. Comments are present to assist with organization of code.
* [ ] Exceptional - Meets all expectations for `Proficient`. The application has exceptionally well-factored CSS/Sass with all styles separated out into logical stylesheets. There are zero instances where an instructor would recommend taking a different approach.